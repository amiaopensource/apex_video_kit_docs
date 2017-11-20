# Explanation of Video Kit Elements

Written by [Savannah Campbell](https://github.com/savcampbell).

Last updated November 2017. 

## Equipment List

1. [Video Deck (not included in this kit)](#video-deck)
2. [Time Base Corrector (TBC)](#time-base-corrector)
3. [Distribution Amplifier](#distribution-amplifier)
4. [CRT Monitor (not included in this kit)](#crt-monitor)
5. [Optional Analog Waveform Monitor and Vectorscope (not included in this kit)](#optional-analog-waveform-monitor-and-vectorscope)
6. [Direct Box](#direct-box)
7. [Audio Mixer](#audio-mixer)
8. [Speakers and Headphones](#speakers-and-headphones)
9. [Capture Card](#capture-card)
10. [Cables and Connectors](#cables-and-connectors)
11. [Computer and Digitization Software](#computer-and-digitization-software)



## Video Deck 
This traveling video digitization station was designed to be small enough to fit inside of a suitcase, and include everything necessary to digitize an analog video tape with the exception of a playback device. What kind of video deck you need depends on the format of video tape you want to digitize. This basic digitization station set up will work with most formats of analog video, from 1/2" open reel to cassette formats like VHS, U-Matic, Betacam, and many others. For some smaller tape formats like Hi8 and MiniDV, it is possible to use a camera, rather than a deck, to digitize from. 

## Time Base Corrector
The "heartbeat" of the video digitization system, the Time Base Corrector (or TBC for short) is important for stabalizing the video signal during the transfer process. The TBC can also correct for some processing errors inherent to the original analog video signal, including compensating for minor dropout. With a TBC, one can also make adjustments to the video signal (and also the audio signal depending on the TBC), including adjusting the brightness, contrast, hue, and saturation. Making these signal adjustments with a TBC can help ensure the values of the video signal are within legal broadcast range. 

The Time Base Corrector used in this video kit is the AV Toolbox AVT-8710 (available here: https://www.bhphotovideo.com/c/product/276891-REG/AV_Toolbox_AVT_8710_AVT_8710_Multi_Standard_Time_Base.html). It is a small and compact TBC that has less features than a more professional-grade TBC, but will get the job done. This particular TBC can only adjust video levels and not audio levels. 

Some professional video deck models have a Time Base Corrector built in. If you are using one of these video decks, using an external TBC may not be necessary. 

## Distribution Amplifier
A distriubtion amplifier can send the same video signal to multiple locations simultaneously. For example, using a distribution amplifier, one can view a video on a monitor screen while also sending the same signal to a capture card for digitization. Regardless of how many places the signal is going, it will retain its strength and quality in each piece of equipment. 

The distribution amplifier used in this kit can be found here: https://www.amazon.com/C2G-Cables-Go-41066-Distribution/dp/B0002J2Q10/

## CRT Monitor
The goal of digitization is to produce a digital video file that looks as close as possible to the original analog tape. Analog video will always look different in digital form, but using a CRT monitor during digization can help maintain the authenticity of the original. Using a CRT as a reference monitor, one can make adjustments to the signal in order to make the post-digitized video match as closely as possible to the pre-digitized video. Note that before digitization, it is necessary to calibrate the monitor you are using to view the content to ensure that the monitor is accurately displaying the video.

## Optional Analog Waveform Monitor and Vectorscope
Scopes such as waveform monitors and vectorscopes are an important tools for calibrating the video signal prior to digitization. Though some digitization software such as vrecord includes digital representations of these scopes, using analog scopes can be useful to monitor the video signal before it enters the capture card. The waveform monitor displays the luminance of the video signal (the black and white levels) and the vectorscope displays the chrominance (color) information of the video signal. Using these tools, one can make proper adjustments to the brightness, contrast, hue, and saturation of the video signal with the Time Base Corrector (TBC). Though not included in this video kit, an ideal video digitization station would include both an external waveform monitor and vectorscope to monitor the pre-digitized signal, as well as the digital versions of these scopes in vrecord and other software in order to ensure that the quality and integrity of the video signal is maintained during digitization. 

## Direct Box
A direct box is used to convert unbalanced audio (such as from an RCA connection) to balanced left and right audio (such as from an XLR connection) for higher quality recordings. Depending on what kind of deck you are using to digitize and whether or not it is professional or consumer-grade, you may not need to use a direct box. If your deck has XLR outputs, a direct box is not necessary. If your deck only has RCA audio outputs, then it is recommended to use a direct box to create a balanced audio signal. 

The direct box used in this kit can be found here: https://www.amazon.com/Pyle-Pro-PDC22-Instrument-Balanced-Unbalanced/dp/B0027V760M/

## Audio Mixer
The audio mixer is used to make adjustments to the audio levels. This includes raising or lowering the audio levels (making them louder or quieter), adjusting the gain, and monitoring mono and stereo channels. Depending on what kind of TBC you are using, some of these adjustments could be made on the TBC instead of the audio mixer.

The audio mixer used in this kit: https://www.amazon.com/YAMAHA-6-channel-mixing-console-MG06/dp/B00I0Q8JNQ/

## Speakers and Headphones
The audio levels should be checked on both the pre-digitization and post-digitization sides of the video digitization system in order to ensure that the integrity and qualiy of the audio signal is maintained throughout. Headphones can be attached to the audio mixer to monitor the pre-digitization audio levels. Speakers can be attached to the capture card or the digitization computer to monitor the post-digitization audio levels during transfer. Note that there may be a short delay when listening to the audio on the post-digitizing side of the station. It is not a cause for alarm if the post-digitized audio is delayed a few seconds from the pre-digitized audio. 

## Capture Card
This is where the magic happens! The capture card is the device that converts the video and audio signals from analog to digital information. There are different types of capture cards available that can work with different kinds of computers and software.

For this digitization kit, we are using the BlackMagic Design UltraStudio Express capture card (https://www.bhphotovideo.com/c/product/857462-REG/Blackmagic_Design_BDLKULSDEXPRESS_UltraStudio_Express.html). This particular card can only be used with Mac computers as it requires a Thunderbolt connection. This capture card also comes with its own video digitization software called BlackMagic Media Express, but it can be used with other digitization software as well.

## Cables and Connectors
So, you have all of the equipment listed in this document, but how do you assemble it into a functional digitization station? That's where cables and connectors come in! The brand and type of each piece of equipment you use will determine what kinds of video and audio cables and conntectors you will need. You may need BNC cables for the video and XLR for the audio, or maybe there are some RCA inputs and outputs in your system, or possibly S-Video! Plus you might need a Thunderbolt or FireWire connection going into your computer! To identify different types of cables and connectors and determine which you will need for your digitization station, an excellent resource is The Cable Bible: https://amiaopensource.github.io/cable-bible/.

## Computer and Digitization Software
In order to digitize video, you need a computer and software that is compatible with both the capture card and the computer you are using. There are many different types of software you can use. The BlackMagic Ultra Studio Express capture card comes with its own digitization software called Blackmagic Media Express. There is also [vrecord](https://github.com/amiaopensource/vrecord), which is free and open source software for analog tape digitization written by archivists for archivists. Currently, vrecord can only be used with BlackMagic capture cards, but it is constantly being updated and may be compatible with other cards in the future. You can also use regular video editing software for digitization such as Adobe Premiere, DaVinci Resolve, or Final Cut Pro. There are also other brands of capture cards, such as those made by the company AJA, that come with their own digitization software. 
