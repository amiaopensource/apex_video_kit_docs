# Explanation of Video Kit Elements

## Equipment List

1. Video Deck (not included in kit)
2. Time Base Corrector (TBC)
3. Distribution Amplifier
4. Capture Card
5. CRT Monitor
6. Direct Box
7. Audio Mixer
8. Speakers / Headphones
9. All of the cables and connectors (link to cable bible?)
10. Laptop running vrecord or Blackmagic Media Express (link to vrecord github page)
11. Option for external scopes (waveform monitor and vectorscope)


## Video Deck (not inluded in kit)
This traveling video digitization station was designed to be small enough to fit inside of a suitcase, and include everything necessary to digitize an analog video tape with the exception of a playback device. What kind of video deck you need depends on the format of video tape you want to digitize. This basic digitization station set up will work with most formats of analog video, from 1/2" open reel to cassette formats like VHS, U-Matic, Betacam, and many others. For some smaller tape formats like Hi8 and MiniDV, it is possible to use a camera, rather than a deck, to digitize from. 

## Time Base Corrector (TBC)
The "heartbeat" of the video digitization system, the Time Base Corrector (or TBC for short) is important stabalizing the video signal during the transfer process. The TBC can also correct for some processing errors inherent to the original analog video signal, including compenating for minor droouts. With a TBC, one can also make adjustments to the video signal (and also the audio signal depending on the TBC), including adjusting the brightness, contrast, hue, and saturation. Making these signal adjustments with a TBC can help ensure the values of the video signal are within legal broadcast range. 

The Time Base Corrector used in this video kit is the AV Toolbox AVT-8710 (available here: https://www.amazon.com/Blackmagic-Design-BDLKULSDEXPRESS-UltraStudio-Express/dp/B008RTY2XC). It is a small and compact TBC that has less features than a more professional-grade TBC, but will get the job done. This particular TBC can only adjust video levels and not audio levels. 

Some professional video deck models have a Time Base Corrector built in. If you are using one of these video decks, using an external TBC may not be necessary. 

## Distribution Amplifier
A distriubtion amplifier can send the same single video input to multiple locations simultaneously. For example, using a distribution amplifier, one can view a video on a monitor screen while also sending the same signal to a capture card for digitization. Regardless of how many places the signal is going, it will retain its strength and quality in each piece of equipment. 

The distribution amplifier used in this kit can be found here: https://www.amazon.com/C2G-Cables-Go-41066-Distribution/dp/B0002J2Q10/ref=sr_1_3?ie=UTF8&qid=1492536660&sr=8-3&keywords=rca+video+distribution+amplifier

## Capture Card
This is where the magic happens! The capture card is the device that converts the video and audio signals from analog waves to digital information. There are different types of capture cards available that can work with different kinds of computers and software.

## Direct Box
A direct box is used to convert unbalanced audio (such as from an RCA connection) to balanced left and right audio (such as from an XLR connection) for higher quality recordings. Depending on what kind of deck you are using to digitize and whether or not it is professional or consumer-grade, you may not need to use a direct box. If your deck has XLR outputs, a direct box is not necessary. If your deck only has RCA audio outputs, then it is recommended to use a direct box to create a balanced audio signal. 

The direct box used in this kit can be found here: https://www.amazon.com/Pyle-Pro-PDC22-Instrument-Balanced-Unbalanced/dp/B0027V760M/ref=sr_1_1?ie=UTF8&qid=1492456929&sr=8-1&keywords=Pyle-Pro%2BPDC22%2BDual%2B1%2F4%27%27%2BInstrument%2BTo%2BBalanced%2B%26%2BUnbalanced%2B(1%2F4%27%27%2FXLR)%2BDirect%2BBox&th=1

## Audio Mixer
The audio mixer is used to make adjustments to the audio levels. This includes raising or lowering the audio levels (making them louder or quieter), adjusting the gain, and monitoring mono and stereo channels. Depending on what kind of TBC you are using, some of these adjustments could be made on the TBC instead of the audio mixer.

The audio mixed used in this kit: https://www.amazon.com/YAMAHA-6-channel-mixing-console-MG06/dp/B00I0Q8JNQ/ref=sr_1_4?ie=UTF8&qid=1492116756&sr=8-4&keywords=audio+mixer+yamaha

## Speakers / Headphones
The audio levels should be checked on both the pre-digitization and post-digitization sides of the video digitization system in order to ensure that the integrity and qualiyu of the audio signal is maintained throughout. Headphones can be attached to the audio mixer to monitor the pre-digitization audio levels. Speakers can be attached to the capture card or the digitizing computer to monitor the post-digitization audio levels during transfer. Note that there may short delay when listening to the audio on the post-digitizing side of the station. It is not a cause for alarm if the post-digitized audio is delayed a few seconds from the pre-digitized audio. 

## CRT Monitor
The goal of digitization is to produce a digital video file that looks as close as possible to the original analog tape. Analog video will always look different in digital form, but using a CRT monitor during digization can help maintain the authenticity of the original. Using a CRT as a reference monitor, one can make adjustments to the signal in order to make the post-digitized video match as closely as possible to the pre-digitized video. Note that before digitization, it is necessary to calibrate both the monitor you are using to view the content to ensure that the CRT monitor is accurately displaying your tape.

## Analog Waveform Monitor and Vectorscope (Optional)
Scopes such as waveform monitors and vectorscopes are an important tool in calibrating the video signal prior to digitization. Though some digitization softwares such as vrecord include digital representations of these scopes, using analog scopes can be useful to monitor the video signal before it enters the capture card. The waveform monitor displays the luminance of the video signal (the black and white levels) and the vectorscope displays the chrominance (color) information of the video signal. Using these tools, one can make proper adjustments to the brightness, contrast, hue, and saturation of the video signal with the Time Base Corrector (TBC). Though not included in this video kit, an ideal video digitization station would include both external waveform monitors and vectorscopes to monitor the pre-digitized signal, as well as the digital versions of these scopes in vrecord and other softwares in order to ensure that the quality and integrity of the video signal is maintained during digitization. 

## Cables and Connectors
So you have all of the equipment listed in this document, but how do you assemble them into a digitization station? That's where cables and connectors come in! The brand and type of each piece of equipment you use will determine what kinds of video and audio cables and conntectors you will need. You may need BNC cables for the video and XLR for the audio, or maybe there are some RCA inputs and outputs in your system, or possibly S-Video! Plus you might need a ThunderBolt or FireWire connection going into your computer! To identify different types of cables and connectors and determine which you will need for your digitization station, The Cable Bible is a fantastic resource. 

## Computer and Digitization Software

In order to digitize video, you need a computer and software that is compatible with both the capture card  and computer you are using. There are many different types of software you can use. The BlackMagic Ultra Studio Express capture card comes with its own digitization software called Blackmagic Media Express. There is also vrecord, which is a free and open source software written by archivists for archivists. Currently, vrecord can only be used with BlackMagic capture cards, but it is constantly being updated and may be compatible with other cards in the future. You can also use regular video editing software for digitization such as Adobe Premiere, DaVinci Resolve, and Final Cut Pro. There are also other brands of capture cards, such as those made by the company AJA, that come with their own digitization software. 

