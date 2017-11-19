# Explanation of Video Kit Elements

## Equipment List

1. Time Base Corrector (TBC)
2. Distribution Amplifier
3. Capture Card
4. CRT Monitor
5. Direct Box
6. Audio Mixer
7. Speakers / Headphones
8. All of the cables and connectors (link to cable bible?)
9. Video Deck (not included in kit)
10. Laptop running vrecord or Blackmagic Media Express (link to vrecord github page)
11. Option for external scopes (waveform monitor and vectorscope)


## Time Base Corrector (TBC)
The "heartbeat" of the video digitization system, the Time Base Corrector (or TBC for short) is important stabalizing the video signal during the transfer process. The TBC can also correct for some processing errors inherent to the original analog video signal, including compenating for minor droouts. With a TBC, one can also make adjustments to the video signal (and also the audio signal depending on the TBC), including adjusting the brightness, contrast, hue, and saturation. Making these signal adjustments with a TBC can help ensure the values of the video signal are within legal broadcast range. 

## Distribution Amplifier
A distriubtion amplifier can send the same single video input to multiple locations simultaneously. For example, using a distribution amplifier, one can view a video on a monitor screen while also sending the same signal to a capture card for digitization. Regardless of how many places the signal is going, it will retain its strength and quality in each piece of equipment. 

## Capture Card
This is where the magic happens! The capture card is the device that converts the video and audio signals from analog waves to digital information. There are different types of capture cards available that can work with different kinds of computers and software.

## Direct Box
A direct box is used to convert unbalanced audio (such as from an RCA connection) to balanced left and right audio (such as from an XLR connection) for higher quality recordings. Depending on what kind of deck you are using to digitize and whether or not it is professional or consumer-grade, you may not need to use a direct box. If your deck has XLR outputs, a direct box is not necessary. If your deck only has RCA audio outputs, then it is recommended to use a direct box to create a balanced audio signal. 

## Audio Mixer
The audio mixer is used to make adjustments to the audio levels. This includes raising or lowering the audio levels (making them louder or quieter), adjusting the gain, and monitoring mono and stereo channels. Depending on what kind of TBC you are using, some of these adjustments could be made on the TBC instead of the audio mixer.

## Speakers / Headphones
The audio levels should be checked on both the pre-digitization and post-digitization sides of the video digitization system in order to ensure that the integrity and qualiyu of the audio signal is maintained throughout. Headphones can be attached to the audio mixer to monitor the pre-digitization audio levels. Speakers can be attached to the capture card or the digitizing computer to monitor the post-digitization audio levels during transfer. Note that there may short delay when listening to the audio on the post-digitizing side of the station. It is not a cause for alarm if the post-digitized audio is delayed a few seconds from the pre-digitized audio. 

## Computer and Digitization Software

In order to digitize video, you need a computer and software that is compatible with both the capture card  and computer you are using. There are many different types of software you can use. The BlackMagic Ultra Studio Express capture card comes with its own digitization software called Blackmagic Media Express. There is also vrecord, which is a free and open source software written by archivists for archivists. Currently, vrecord can only be used with BlackMagic capture cards, but it is constantly being updated and may be compatible with other cards in the future. You can also use regular video editing software for digitization such as Adobe Premiere, DaVinci Resolve, and Final Cut Pro. There are also other brands of capture cards, such as those made by the company AJA, that come with their own digitization software. 

