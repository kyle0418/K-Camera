# K-Camera
A camera that can take photos, record videos and face recognition.

# How to use

1.Automatically scans connected camera hardware when opening software

2.Click "Connect" to open the selected camera

3.Click "Photo" to take a photo

4.Click "Record" to record a video

5.Click "Face Recognition" to recognize faces

6.Click "Add New Face" to add new face data to database

7.Click "Disconnect" to disable the camera connection

# Tips

When generating the video, ffmpeg was used to merge the video and audio. There are some problems with the audio track.

Since no suitable ffmpeg wrapper was found, the project included a complete "ffmpeg.exe".

The software release method is essentially a 7z compression package with self-extracting format. So the project startup time will be slightly longer.

Face recognition calls Baidu.AI, so please make sure the network connection is normal when using this function.

