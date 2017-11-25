# Video Digitization Workflow

Written by Eddy Colloton

*Dear reader, very very rough doc right now, please feel free to comment, track changes, or just edit. Open to suggestions on content format etc thanks - eddy*


Last Updated November 2017


## Step 1: What do I have?

* **Which formats?**

	Is it a VHS tape? Maybe miniDV? Not sure? Check out the [Texas Commission on the Arts Videotape Identification and Assessment Guide](http://www.arts.texas.gov/video/) for pictures and descriptions of different tapes.

* **How much?**

	Do you have 10 tapes or 100? Are there 2 minutes on a tape or 120? Many tapes will have their max capacity written on them.

* **What is it?**
	
	Are the tapes labeled? Is there a list? It’s a good idea to create an inventory of the tapes in a spreadsheet as a first step.

				⏫⏫Knowing this will help you with each step after this one⏫⏫


![](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/tapes_table_white_web.jpg "Magnetic Media Formats Chart by Ashley Blewer")

[Magnetic Media Formats Chart by Ashley Blewer](https://github.com/ablwr/media-id-posters)
<a href="url"><img src="https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/BY.png" align="left" height="48" ></a>

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)


## Step 2: How do I play it?

* **Can you play the tape?**
	
	Different formats have different playback devices, often called “decks.” Sourcing a playback device for an older format means looking for used equipment, typically on ebay or craigslist. A camera that uses the right tape format is often just as good as a deck, especially with DV and miniDV!
	
				⏫⏫Sometimes a camera will be easier to find than a deck⏫⏫
				
* **What type of signal?**
	
	Some videotapes record analog video, but many record digital video too. No need to re-digitize DV or miniDV tapes! Just connect the playback device to your computer via firewire.
	
* **How do I connect this?**
	
	So many cables! You want to make sure you have the right connectors for your playback device and your analog-to-digital converter (more on those in Step 4). When finding equipment, take note of connector types, so that you can get signal from end-to-end. Check out the [AMIA Open Source Cable Bible](https://amiaopensource.github.io/cable-bible/) for help ID-ing cables.


## Step 3: How do I monitor what I’m digitizing?

* **How does it sound?**
	Playback devices will often have “meters” that show sound levels of the media being played back. Better still, look for a headphone output so you can listen in. Best case scenario, run the audio from the playback device through a mixer so you can monitor and adjust audio independent of the playback device.
	
* **What does it look like?**
	Send the video signal to a monitor before sending it to the computer so you can see the picture as it is playing back. Consider using a distribution amplifier to split the video signal, so you can send one signal directly to the computer and one signal to the monitor.
* **How does it look?**
	Use objective measurements to assess the video signal, not your eye. Waveform monitors and vectorscopes are the best way to do this, if you have access to them. If you don’t have these devices, use a digital waveform monitor and vectorscope in your video capture software (more on software in the next step).
	
	
## Step 4: How do I get it in the computer?

* **What do I need?**
	There are two ingredients needed for digitization: (1) hardware, most typically an analog to digital converter or A/D (pronounced A-to-D), and (2) capture software. 

* **Which signal types are there?**
	Remember the connectors and cable types from Step 2, and keep these in mind. You may need to find adapters to get from one connection to another. Be sure to understand what type of signal your playback device is sending out, different video and audio signals must be captured differently: composite video signals only require 1 video cable, whereas component signals need 3, DV signals can be captured as data over firewire, but SDI signals, which are also digital, must be captured similar to an analog signal.

* **How does it work?**
	An analog signal is digitized through a process called sampling.  Sampling takes multiple points on a wave as reference points.
	There’s two metrics for measuring the quality of a sample this analog source - the sampling rate and the bit depth. The rate is how many samples taken, the bit depth is how much information is in each sample. So basically how much, and how often.
![](https://github.com/amiaopensource/apex_video_kit_docs/blob/master/digipres_images/800px-Signal_Sampling.png)
	
[Image in the Public Domain available here](https://www.google.com/url?q=https://commons.wikimedia.org/wiki/File:Signal_Sampling.png&sa=D&ust=1511628713638000&usg=AFQjCNHzLLTgPN8SiiRog4am68aoJrSzwg)
	

* **Which hardware and software is best?**
	Most capture software is unfortunately hardware dependent, so best to make a choice on an A/D first (if you need one). Budget, but also media type, will be the two biggest factors in selecting a device. Check out the [Minimum Viable Station Documentation](https://ablwr.github.io/blog/2016/12/02/minimum-viable-transfer-station-documentation/) on Ashley Blewer’s website for recommendations.


## Step 5: How do I create a video file?

* **Which file format do I choose?**
	Two factors to consider when selecting a format are: data storage and use of the material. Most file formats (such as MP4s) will cause a loss of information due to compression. Some archivist find this unacceptable and insist on uncompressed or “lossless” file formats (check out ffv1/mkv!). These files tend to take up a lot of storage space, although lossless files are much smaller than uncompressed ones. When selecting a file format, consider available storage space, the size of the collection, the intended use of the collection, and the significance of audiovisual quality. If storage space is limited, consider selecting a sample of tapes to digitize until more storage space is available.

				⏫⏫Some inexpensive A/D setups may limit options on file format⏫⏫ 
				
* **What other factors affect file size?**
	Sampling rate is essentially the frequency that samples are taken from an analog signal, 48 kHz is a common sample rate for audio signals. Bit depth is how much information is in that sample, 8- and 10-bit depth are common for video, 24-bit depth for audio. Color (or chroma) subsampling refers to the ratio between the color information to black & white information in a picture. 4:2:2 subsampling is recommended for preservation.
	
* **How do I name the files?**
	File naming is very important to be able to properly ID the content in your files. It is recommended that you link the information in your inventory from Step 1 to your file name, and include the filename in your inventory.
	
	
## Step 6: How do I check my work?

* **How do I look make sure the picture isn't clipping?**
	"Clipping" refers to the loss of picture information outside of broadcast range. Any values outside of this range become pure white or pure black, losing the gradients present in the source tape. The free and open source tool [QCTools](https://www.bavc.org/preserve-media/preservation-tools/qctools) is great for checking files to find values outside of broadcast range (QCTools does lots of other stuff too, like help you spot artifacts such as [dropout](https://bavc.github.io/avaa/artifacts/video_dropout.html)). The graphs visible in the GUI version of the software gives you a nice "macro perspective" of the whole file, giving you a general idea of how high the levels are. The playback filters, which you open by clicking on the thumbnail images at the bottom of the GUI let you spot check more percisely. To see values outside of broadcast range highlighted, use the "Broadcast Range Pixels" filter, or, to only see parts of the image that are outside of broadcast range use the "Broadcast Illegal Focus" filter.

MediaInfo?

## Step 7: How do I share?

Privacy/copyright concerns
Recommended formats for streaming





