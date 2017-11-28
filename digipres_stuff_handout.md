# Digital Preservation Basics
Written by [Jonathan Farbowitz](https://jfarbowitz.github.io/)</br>
Last Updated November 2017

## Introduction
<img src="https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/a85.jpg" alt="There is no escape from digital preservation!" width="400">

Welcome to the world of digital preservation! On a long enough timeline there is no escape from dealing with digital files in archival collections. Whether you find yourself working with born-digital video content or analog material that has been digitized, understanding the principles of digital preservation is key to maintaining an accessible collection and preserving it over the long-term. Digital preservation sometimes requires a different way of thinking that may not seem intuitive to those familiar with preservation practices for analog materials. But not to worry, many of the core principles of preserving non-digital materials still apply to digital.

Institutions that are putting significant amounts of time and money into digitization programs or projects must ensure that the files they receive are well-taken care of. Otherwise, those hard-earned files risk becoming inaccessible (and the digitization process was all for naught). Unlike analog formats such as film and videotape, digital files will not persist through "benign neglect". Data on a hard drive that's left untouched on a shelf for twenty years stands little chance of actually being saved. Digital materials require a series of ongoing maintenance activities if they are to persist over time.

This document will describe the threats to digital information and the strategies that archivists, librarians, and IT professionals have developed to mitigate those threats.

## Quick Tips for Digital Preservation 
1. **Keep multiple backup copies of all digital files** (ideally in three copies in three different geographic locations). For more information, see the section on backup
2. **Use a consistent file naming system**. The most important part of a filename is that it should be unique. For more information, see the section on filenaming and directory structure.
3. **Store your files in a consistent and easy-to-understand directory structure**. Try to make it as easy to understand as possible, put yourself in the shoes of someone who doesn't work your institution and see if they would be able to figure it out. For more information, see the section on filenaming and directory structure.
4. **If possible, create checksums for all files in your collection and check them at regularly scheduled intervals.** This will ensure the integrity of your files. For more information, see the section on File Fixity. 
5. **Use sustainable file formats and monitor formats for obsolescence**. For more information, see the sections on sustainable file formats and obsolescence.  

## Threats to Digital Information
Like vinegar syndrome, sticky shed syndrome, and mold, digital information has its own set of risk factors that threaten long-term preservation. 

### Data Degradation/Data Rot
Data degradation, also known as "data rot," occurs when the data in a file changes unintentionally. Some people may also call this phenomenon "file corruption." On a long enough timeline, with a large enough set of data, bits within the stored files may "flip." In other words, one bit of a file changes from the original—a bit that was originally a 0 becomes a 1, or a 1 becomes a 0. There are many possible reasons for this, including read/write errors with hard drives or other storage devices or the physical decay of the storage device; some even suggest that ![cosmic rays can flip bits](https://en.wikipedia.org/wiki/Soft_error#Cosmic_rays_creating_energetic_neutrons_and_protons).

So, why does it matter that a single bit in a file has flipped? First, from an archival perspective, the file is no longer the original, the zeros and ones that make up the file have fundamentally changed. There are also practical concerns. In a video file a single flipped bit may never even be noticeable to a viewer. However, that depends on where the bit was flipped. The image below shows how one flipped bit can potentially cause glitches in an image. In the worst case scenario, a flipped bit in the header of a video file may render the file unplayable.

![](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/bit_flipped.jpg)

### Obsolescence
Even if exact copies of digital files are kept intact, there is no guarantee that contemporary computer systems will be able to read and properly render these files. In digital preservation there are two kinds of obsolescence to consider: the obsolescence of storage media and the obsolescence of file formats.

#### Storage Media Obsolescence
Storage media refers to the physical carriers on which data is stored. These could be hard drives, floppy disks, optical discs, or even punch cards.  Consider this example: how would you go about transferring data contained on computer punch cards onto your brand new laptop? While this isn't impossible, it would be quite a challenge. From time to time, individual companies have created their own specialized storage media and when the company goes out of business or the format becomes unpopular it may be difficult to find drives to read that media. For example, how people have Iomega Zip disk drives on their current computers? How many even have CD/DVD drives? Storage media on computer systems changes all the time and often older storage media is not compatible with newer systems and digital preservationists must account for this inconvenient situation.

#### File Format Obsolescence
Consider how quickly computing technology has progressed in the last few decades. Different computer programs that were popular in 1995 have now fallen into obscurity. Perhaps these programs had their own file formats that cannot be read by newer programs. Did you ever design a greeting card in Print Shop Deluxe, write a document in WordPerfect, or create a spreadsheet in Lotus 1-2-3? How would you go about accessing these files today? 

Digital preservationists must monitor consider the file formats they acquire for their collections and monitor the file formats they already have in their collections. Understanding the characteristics of file formats helps an individual chose the best target formats and understand the risks related to less sustainable formats and plan for them. 

### Data Loss
Data loss may refer to catastrophic events that could destroy physical equipment like computers, servers, or hard drives. Data deletion or data modification could also be the result of malicious hacking. Just as a flood, hurricane, or tornado could destroy collection materials like books and paper, these natural disasters can impact the safety of data as well if proper measures are not taken. 

Libraries, museums, and archives typically have measures for protecting their physical materials in the event of a disaster. However, every cultural heritage institution must also consider its digital components in its disaster plan. Institutions may need to consider their network security protocols and the security of their digital files as well. How well are the computers where you store your files protected from natural disasters? How secure are these computer and storage systems?

## Digital Preservation Strategies
The following strategies respond to the threats outlined above. Following these strategies allows cultural heritage institutions to store data safely for the long haul.

### Redundant Storage (aka "Backing Up")
As far as archivists are concerned, perhaps the single greatest advantage of materials is the abilty to make an infinite number of copies with 100% fidelity to the original. It's kind of like their superpower. The single most effective action one can take when trying to preserve digital files is to make multiple exact copies. Taking this step can mitigate both bit flipping and catatrosphic data loss. Backing up is a powerful preservation measure. 

#### Best Practice for Redundant Storage
Archivists have determined that keeping three identical copies of files, in three geographically separated locations . This prevents a situation where a natual disaster destroys all copies of a collection itme. It is generally preferred that the three copies be stored on different types of storage media. For example, one copy could exist on a spinning disk hard drive, one copy on a solid state hard drive, and yet another on an LTO data tape.

## Checking the Data Integrity of Files
Intergrity (or fixity) checks are periodic attempts to determine if a copy of a file is an exact copy, or if the bits of a file have changed over time. In order to accomplish this feat, specialized values called "checksums" (also sometimes called " hashes") are used to compare files.

### What is a Checksum?
A checksum is an algorithm (a process ) that calculates a unique alphanumeric value based on the file's contents. A checksum is a bit like a file's fingerprint, however, it is event more unqiue. If one bit of the file changes, the checksum will change dramatically

<img src="https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/Checksum.svg" alt="Checksum image" width="400">
![]()

### Why create Checksums?
### Checksum Algorithms
Know which algorithm produced a checksum is critical. Future checksum verification requires the use of the same algorithm to get the same result. Two checksum algorithms currently in use by archives are MD5 (Message Digest 5) and SHA-1 (Secure Hash Algorithm 1). An MD5 checksum is significantly faster to calculate. However, there is a trade off. A checksum collision (two files with different data producing the exact same checksum) is more likely with MD5 than with SHA-1.

### Scheduling Fixity Checks
Collecting and storing the data about fixity checks over time ensures the authenticity of the file. With this information, the archive can prove an unbroken chain of custody. By collecting regular fixity data they can prove that the file they have stored in 2050 is exactly the same as the file they received from the creator in 2017. 

## File Naming and Directory Structure
Files that cannot be found in a filesystem are as good as lost. And often in the digital world files that cannot be understood are as good as lost.

If you're putting 

### Why are File Naming and Directory Structure Important?
If a particular file cannot be located within the filesystem or if future users cannot figure out what a file represents its as good as lost.

### Best Practices for File Naming 
The most important aspect of file naming is that every file should have a unique ID. 

### Best Practices for Directory Structure
A well-thought-out directory structure will be easily understandable by future users. When determining a directory structure, engage in a short thought exercise: "If we all left this organization could future staff still find the files that they need?"

## File Formats
### Why is a Choice of File Format Important?
### What to Look for in a File Format
### File Format Normalization or Migration

## Additional Resources
The National Digital Stewardship Alliance's (NDSA) Levels of Digital Preservation: 

