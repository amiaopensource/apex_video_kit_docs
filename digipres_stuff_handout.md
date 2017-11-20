# Digitial Preservation Basics
Written by Jonathan Farbowitz
Last Updated November 2017

## Introduction: There Is No Escape
![](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/a85.jpg "There is no escape from digital preservation!")

Welcome to the world of digital preservation. Whether you find yourself working with born-digital video content or analog material that has become digital through digitization, understanding the principles of digital preservation is key to maintaining an accessible collection and preserving it long-term. Digital preservation sometimes requires a different way of thinking that may not seem intuitive to those familiar with the preservation practices for analog materials. But not to worry, many of core principles of preserving non-digital materials still apply to digital.

Institutions that are putting significant amounts of time and money into digitization programs or projects must ensure that the files they receive are well-taken care of. Otherwise those hard-earned files can become inaccessible. Unlike analog formats like film and videotape, digital files will not persist through "benign neglect". Data on a hard drive that's left on a shelf for twenty years stands little chance of actually being saved for reasons which will be discussed below. Digital materials require a series of ongoing maintenance activities if they are to persist over time.

This handout will describe the threats to digital information and the strategies that archivists and IT professionals have developed to mitigate those threats.

## Threats to Digital Information
Like vinegar syndrome, sticky shed syndrome, and mold digital information has its own set of factors that threaten long-term preservation. 

### Data Degredation/Data Rot
Data degredation, also known as "data rot" occurs when the data in a file changes unintentionally. Some people may also call this phenomenon "file corruption." On a long enough timeline, with a large enough set of data, bits within the stored files may "flip". In other words, one bit of a file changes from the original—a bit that was originally a 0 becomes a 1, or a 1 becomes a 0. There are many possible reasons for this, including read/write errors with hard drives or other storage devices or physical decay of the storage device; some even suggest that cosmic background radiation can flip bits.

So, why does it matter that a single bit in a file has flipped? First, from an archival perspective, the file is no longer the original, the zeros and ones that make up the file now have one small difference. There are also practical concerns. In a video file a single flipped bit may never even be noticable to a viewer. However, that depends on where the bit was flipped. The image below proves that one flipped can potentially cause glitchiness in an image. In the worst case scenario a flipped bit in the header of a video file may render the file unplayable.

![](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/bit_flipped.jpg)

### Obsolescence
Even if exact copies of files are kept intact, there is no guarantee that contemporary computer systems will be able to read and understand these files.

With digital preservation there are two kinds of obsolescence to consider: the obsolescence of storage media and the obsolesence of file formats.

#### Storage Media Obsolesence
Storage media refers to the physical carriers on which data is stored. These could be hard drives, floppy disks, optical discs, or even punch cards.  Consider this example: how would you go about putting data contained in computer punch cards on your brand new laptop? While this isn't impossible, it would be quite a challenge. From time to time individual companies have created their own specialized storage media and when the company goes out of business or the format becomes unpopular it may be difficult to find drives to read that media. For example, how people have Iomega Zip disk drives on their current computers? How many even have CD/DVD drives?

Digital preservation activities must account for the fact that storage media on computer systems changes all the time and often older storage media is not compatible with newer systems.

#### File Format Obsolesence
Consider how quickly computing technology has progressed in the last few decades. Different computer programs that were popular in 1995 have now fallen into obscurity. Perhaps these programs had their own file formats that cannot be read by newer programs. Did you ever design a greeting card in Print Shop Deluxe, write a document in WordPerfect, or create a spreadsheet in Lotus 1-2-3? How would you go about accessing these files today? 

Digital preservationists must monitor consider the file formats they acquire for their collections and monitor the file formats they already have in their collections. 

### Data Loss
Data loss may refer to catatrophic events that could destroy physical equipment like computers, servers, or hard drives. Data deletion or data modification could also be the result of malicious hacking. Just as a flood, hurricane, or tornado could destroy collection materials like books and paper, these natural distasters can impact the safety of data as well if proper measures are not taken. 

Libraries, museums, and archives typically have measures for protecting their physical materials in the event of a disaster. However, every cultural heritage institution must consider its digital components in its disaster plan. Institutions may need to consider its network security protocols and the security of its digital files as well.

## Digital Preservation Strategies
The following strategies respond to the threats outlined above. Following these strategies allows cultural heritage institutions to store data safely for the long haul.

### Redundant Storage (aka "Backing Up")

#### Gold Standard for Redundant Storage
3 identical copies, in three geographically separated locations, on different types of storage media

## Checking the Data Integrity of Files

### What is a Checksum?
A checksum is like a file's fingerprint. If one bit of the file changes, the checksum will change dramatically

![](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/Checksum.svg)

### Why create Checksums?
### Checksum Algorithms
#### MD5
#### SHA1
#### SHA2 (aka SHA256)

### Scheduling Fixity Checks
Having the data about fixity checks over time ensures the authenticity of the file. With this information, the archive can prove an unbroken chain of custody. By collecting regular fixity data they can prove that the file they have stored in 2050 is exactly the same as the file they received from the creator in 2017. 

## File Naming and Directory Structure
Files that cannot be found in a filesystem are as good as lost. And often in the digital world files that cannot be understood are as good as lost.

If you're putting 

### Why are File Naming and Directory Structure Important?
If a particular file cannot be located within the filesystem or if future users cannot figure out what a file represents its as good as lost.

### Best Practices for File Naming 
The most important aspect of file naming is that every file should have unique ID. 

### Best Practices for Directory Structure
A well-thought-out directory structure will be easily understandable by future users. When determining a directory structure, engage in a short thought exercise: "If we all left this organization could future staff still find the files that they need?"

## File Formats
### Why is a Choice of File Format Important?
### What to Look for in a File Format
### File Format Normalization or Migration
