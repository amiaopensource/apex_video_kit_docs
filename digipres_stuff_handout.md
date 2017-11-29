# Digital Preservation Basics
Written by [Jonathan Farbowitz](https://jfarbowitz.github.io/)</br>
Last Updated November 2017

## Introduction
<img src="https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/a85.jpg" alt="There is no escape from digital preservation!" width="400">

Welcome to the world of digital preservation! Sooner or later there is no escape from dealing with digital files in archival collections. Whether you find yourself working with born-digital video content or analog material that has been digitized, understanding the principles of digital preservation is key to maintaining an accessible collection and preserving it over the long-term. Digital preservation sometimes requires a different way of thinking that may not seem intuitive to those familiar with preservation practices for analog materials. But not to worry, many of the core principles of preserving non-digital materials still apply to digital.

Institutions that are putting significant amounts of time and money into digitization programs or projects must ensure that the files they receive are well-taken care of. Otherwise, those hard-earned files risk becoming inaccessible (and the digitization process was all for naught). Unlike analog formats such as film and videotape, digital files will not persist through "benign neglect". Data on a hard drive that's left untouched on a shelf for twenty years stands little chance of actually being saved. Digital materials require a series of ongoing maintenance activities if they are to persist over time.

This document will describe the threats to digital information as well as the strategies that archivists, librarians, and IT professionals have developed to mitigate those threats.

## Quick Tips for Digital Preservation

1. **Keep multiple backup copies of all digital files** (ideally three copies in three geographically separated locations). For more information, see the section on [backing up](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_stuff_handout.md#redundant-storage-aka-backing-up)
2. **Use a consistent file naming system**. The most important part of a filename is that it should be unique. For more information, see the section on [file naming and directory structure](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_stuff_handout.md#file-naming-and-directory-structure).
3. **Store your files in a consistent and easy-to-understand directory structure**. Try to make the directory structure as straighforward as possible. Put yourself in the shoes of someone who doesn't work your institution and see if they would be able to figure it out. For more information, see the section on [file naming and directory structure](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_stuff_handout.md#file-naming-and-directory-structure).
4. **If possible, create checksums for all files in your collection and check them at regularly scheduled intervals.** This will ensure the integrity of your files. For more information, see the section on [file fixity](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_stuff_handout.md#checking-the-data-integrity-of-files). 
5. **Where possible, use sustainable file formats and monitor formats in your collection for obsolescence**. For more information, see the sections on [sustainable file formats](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_stuff_handout.md#file-formats) and [obsolescence](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_stuff_handout.md#obsolescence).  

## Threats to Digital Information
Like vinegar syndrome, sticky shed syndrome, and mold, digital information has its own set of risk factors that threaten its long-term preservation. 

### Data Degradation/Data Rot
Data degradation, also known as "data rot," occurs when the data in a file changes unintentionally. Some people may also call this phenomenon "file corruption." On a long enough timeline, with a large enough set of data, bits within stored files may "flip." In other words, one bit of a file changes from the original—a bit that was originally a 0 becomes a 1, or a 1 becomes a 0. There are many possible reasons for this, including read/write errors with hard drives or other storage devices or the physical decay of the storage device; some even suggest that [cosmic rays can flip bits](https://en.wikipedia.org/wiki/Soft_error#Cosmic_rays_creating_energetic_neutrons_and_protons).

So, why does it matter that a single bit in a file has flipped? First, from an archival perspective, the file is no longer the original, the zeros and ones that make up the file have fundamentally changed. There are also practical concerns. In a video file a single flipped bit may never even be noticeable to a viewer. However, that depends on where in the file the bit was flipped. The image below shows how one flipped bit can potentially cause glitches in an image. In the worst case scenario, a flipped bit in the header of a video file may render the file unplayable.

![](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/bit_flipped.jpg)

### Obsolescence
Even if exact copies of digital files are kept intact, there is no guarantee that contemporary computer systems will be able to read and properly render these files. In digital preservation there are two kinds of obsolescence to consider: the obsolescence of storage media and the obsolescence of file formats.

#### Storage Media Obsolescence
Storage media refers to the physical carriers on which data is stored. These could be hard drives, floppy disks, optical discs, or even punch cards. Consider this example: how would you go about transferring data contained on computer punch cards onto your brand new laptop? While this isn't impossible, it would be quite a challenge. 

From time to time, individual companies have created their own specialized types of storage media and when the company goes out of business or the format becomes unpopular it may be difficult to find drives to read that type of media. For example, how people have Iomega Zip disk drives on their current computers? How many even have CD/DVD drives? Storage media for personal computers changes all the time and often older storage media is not compatible with newer systems. Digital preservationists must account for this inconvenient situation.

#### File Format Obsolescence
Consider how quickly computing technology has progressed in the last few decades. Different computer programs that were popular in 1995 have now fallen into obscurity. Perhaps these programs had their own proprietary file formats that cannot be read by newer programs. Did you ever design a greeting card in Print Shop Deluxe, write a document in WordPerfect, or create a spreadsheet in Lotus 1-2-3? How would you go about accessing these files today? 

Digital preservationists must consider the file formats they acquire for their collections as well as monitor the file formats that already exist within their collections. Understanding the characteristics of file formats will help an organization chose the best target formats and understand the risks related to less sustainable formats and plan for them. 

### Data Loss
Data loss may refer to catastrophic events that could destroy physical equipment like computers, servers, or hard drives. Data loss could also be the result of malicious hacking or sabotage if files are deleted or modified. Just as a flood, a hurricane, or tornado could destroy collection materials like books and paper, natural disasters can impact the safety of data as well if proper measures are not taken. Likewise, just as a thief or vandal can steal or destroy physical materials from an archive, an intruder to computer systems can do the same to digital materials.  

Libraries, museums, and archives typically have measures for protecting their physical collection items in the event of a disaster. However, every cultural heritage institution must also consider its digital collection in its disaster plan. Institutions may need to consider their network security protocols and the security of their digital files as well. How well are the computers where you store your files protected from natural disasters? How secure are these computer and storage systems?

## Digital Preservation Strategies
The following strategies respond to the threats outlined above. Following these strategies allows cultural heritage institutions to store data safely for the long haul.

### Redundant Storage (aka "Backing Up")
Perhaps the single greatest advantage of materials is the abilty to make an infinite number of copies with 100% fidelity to the original. It's kind of like their superpower. One of the most effective actions archivists can take when trying to preserve digital files is to make multiple exact copies. Taking this step can mitigate both bit flipping and catatrosphic data loss. Backing up is a powerful preservation measure. 

#### Best Practice for Redundant Storage
Keeping three identical copies of files, in three geographically separated locations is considered best practice. This course of action prevents a situation where a natual disaster destroys all copies of a collection item. This means that ideally the three locations should be far away from one another and not be susceptible to the same kinds of natural disasters. Ideally the three copies of the files should be stored on different types of media. For example, one copy of a file could be stored on a spinning disk hard drive (HDD), one copy on a solid state drive (SSD), and yet another on an LTO data tape. This reduces the risk that preservation is dependent on the durability of a single type of media.

## Checking the Data Integrity of Files
Intergrity (or fixity) checks are periodic attempts to determine if a copy of a file is an exact copy, or if the bits of a file have changed over time. In order to accomplish this feat, specialized values called "checksums" (also sometimes called " hashes") are used to compare the contents of files.

### What is a Checksum?
A checksum is an algorithm (a series of mathematical and logical operations) that calculates a unique alphanumeric value based on the contents of a file. A checksum is a little like a file's fingerprint, however, it is much more unqiue than a fingerprint. If even one bit of the file changes, the checksum will change dramatically as illustrated in the image below:

<img src="https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/Checksum.svg" alt="Checksum image" width="400">

The checksum is only based on the contents of the file. It isn't affected by the file's name and what folder it is stored in. Therefore, the file could be renamed or moved and will still produce the same checksum. 

### Why create Checksums?
When an archive receives a new file it should immediately create a checksum for that file (assuming one hasn't already been created). Once the checksum has been calculated, it will become an important reference for the life of the file. If copies of the file are made they can be compared against the checksum. If the copy produces the same checksum as the original file, one can be nearly certain that the two files are identical bit-for-bit. 

The original file can also be checked over time. The same file should always produce the same checksum if its contents have not changed. 

### Checksum Algorithms
Knowing which algorithm produced a checksum is critical. Future checksum verification requires using the same algorithm to get the same result. Two checksum algorithms currently in use by archives are MD5 (Message Digest 5) and SHA-1 (Secure Hash Algorithm 1). An MD5 checksum is significantly faster to calculate. However, there is a trade off. A checksum collision (two files with different data producing the exact same checksum) is more likely with MD5 than with SHA-1.

### Scheduling Fixity Checks
Scheduling fixity checks is an important procedure for ensuring that files have not changed over time. By collecting regular fixity data an archive can prove that a file sitting on a storage system in 2050 is identical to the file they received from the file's creator twenty years earlier. Collecting and storing the data about fixity checks over time ensures the authenticity of the file. With this information, the archive can prove an unbroken chain of custody. 

Even though regular fixity checks are a good idea and can be automated, it may make sense to space them out. Fixity checks that are too frequent could cause excessive wear and tear to the storage media. Having very frequent fixity checks also increases the likelyhood of read/write errors occuring. Depending on the size of the collection, a once per week fixity check might be reasonable. Once a month may also be appropriate. The main idea is to develop a regular schedule for performing fixity checks to ensure that files have remained the same over time.  

## File Naming and Directory Structure
Files that cannot be found within a filesystem are as good as lost. Additionally, if archivists and researchers cannot understand the context of the file  (for example which hard drive a file came from) it's also may be as good as lost. In order to prevent this situation from happening, archivists must create unique filenames within an easy-to-understand directory stucture.

### Best Practices for File Naming 
The most important aspect of file naming is that every file should have a unique identifier. In other words, no two filenames should be alike. In addition, special charcters such as @,#,$,%,&,\*, and + should be avoided in filenames. Particularly in Windows operating systems, these filenames can cause issues. The safest filenames use either numbers or lowercase letters and use underscores or hyphens instead of spaces.  

### Best Practices for Directory Structure
A well-thought-out directory structure will be easily understandable by future users. When determining a directory structure, engage in a short thought exercise: "If we all left this organization, could future staff still find the files that they need?"

## Refreshing Storage Media
All physical storage media like hard drives and disks has a limited lifespan. Storage media also becomes obsolete over time. In order to combat these risks, files must be periodically **refreshed**. This means copying files from older storage media to newer storage media. Of course, any copying requires checksum verification after the copying takes place to ensure that the new storage media has exact copies of the files. 

## File Formats
Choice of file formats can have a big impact on future preservation decisions for digital files. Organizations that have analog materials digitized should think carefully about the target format they are digitizing to. Organizations that collect born-digital content that was never analog in the first place should assess the formats that they have in their collections to plan for future preservation actions.

Wise selection of file formats can migitigate against format obsolesence issues.

### Compression vs. Lossless Compression vs. No Compression
File compression discards data (lossy compression) or writes data in a more concise way without discarding anything (lossless compression). An example of lossy compression is an MP3 or an MP4 file. An example of lossless compression is an FFV1 file or a ZIP file. Compressed files depend on a program that will decompress them to make them readable to the computer. This is an additional dependency. 

In addition, any bit flipping in a compressed file is more likely to cause a glitch than in an uncompressed file. This is due to the fact that each byte of the compressed file holds more unique information (there is more redundancy in the uncompressed file).    

In order to prevent a dependency on decoder software or increased suseptibilty to data rot, some institutions have chosen not to use any kind of compression on their preservation master files. The tradeoff is that uncompressed files require more storage space, often significantly more. 

### What to Look for in a File Format
The basic aspects to consider in file formats are: 
* **Openness** - Does one company control the format (is it proprietary)? Is the format open source? Open source formats may have more of a life than proprietary formats.
* **Documentation** - Is the format well-documented? Are the specifications for how to create a file in the given format easy to find? If these specifications are easy to find there’s a chance of a programmer building software in the future to read the format. Good documentation also typically means that the format is well-standardized. 
* **Self-descriptiveness** - How well does the format's metadata describe the playback specifications of the file? Some files have very little technical metadata embedded within them (for example on older video formats the aspect ratio wasn’t specified so the video player would just guess at how to present the file). In general, more technical metadata within a file is better. Technical metadata within a file needs to specify at minimum - framerate, interlacing, aspect ratio, resolution.
* **Universality/Ubiquity** - How universal or ubiquitious is the file format? Is it being used in the real world? Is it being used in the video production world? Does good software out there for encoding/decoding the format?

The best file formats will be open, well-documented, self-descriptive, and uquititous. These formats stand the best chance of long-term survival.

### File Format Migration and Normalization
An archive may chose to **normalize** its files. This means that when the file, it will be transcoded into a different format (while keeping the original file). Normalization is a strategy meant to reduce the danger of file format obsolesence. For example, Word documents may be turned into PDF files. The PDF format is more open than Word and it may benefit researchers to browse file formats that they can easily open. 

Normalization is a form of **migration**. Migration means changing the format of a file. In practice, this typically means transcoding files from an obsolete format to a more contemporary format. One example might be migrating the audio content of a RealMedia file into a WAV file. Usually the original file is kept as well, but the migrated file may be the one that is presented to researchers. The difference between migration and normalization is that normalization is typically done when the file is brough into the collection. Migration typically occurs later.

## Additional Resources
The National Digital Stewardship Alliance's (NDSA) Levels of Digital Preservation: http://www.digitalpreservation.gov:8081/ndsa/activities/levels.html
The Library of Congress's research on the sustainability of digital formats: https://www.loc.gov/preservation/digital/formats/

