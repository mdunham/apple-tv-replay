# NowlinOrtho Replay

tvOS application that converts an Apple TV into to a digital signage / kiosk

## Highlight Features

- Plays video on launch and runs in a loop
- Caches video for replay, conserving network bandwidth 
- Allows for airplay mirroring on top of the video and resumes once session is terminated
- In conjunction with MDM, can be locked onto screen without any input from remote or remote app (on iPhone) to be a true Kiosk!

## Description

The application is designed to start a video on launch and keeping running in an infinite loop. The video being played can be hosted in any public facing server. If you don't have any servers that you can host the videos on, a free AWS S3 account (Free storage up to 5GB) can be used.

## How does Replay cache videos?

Videos are cached locally as application data with one complete run of the video (advise two just to be safe)

## Supported Video Formats

-	H.264 video up to 1080p, 30 frames per second, High or Main Profile level 4.0 or lower, Baseline profile level 3.0 or lower with AAC-LC audio up to 160 Kbps per channel, 48kHz, stereo audio in .m4v, .mp4, and .mov file formats
-	MPEG-4 video up to 2.5 Mbps, 640 by 480 pixels, 30 frames per second, Simple Profile with AAC-LC audio up to 160 Kbps, 48kHz, stereo audio in .m4v, .mp4, and .mov file formats 
-	Motion JPEG (M-JPEG) up to 35 Mbps, 1280 by 720 pixels, 30 frames per second, audio in ulaw, PCM stereo audio in .avi file format


# NowlinConnect
