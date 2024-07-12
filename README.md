Video Streaming Proof of Concept Project

Developed a proof of concept to understand video streaming (not live streaming).
Implemented video streaming by sending video data over the internet in small packets, allowing real-time playback without full downloads.
Utilized codecs such as H.264, H.265, and VP9 to compress and decompress video data for efficient transmission.
Employed M3U8 format for adaptive bitrate streaming, optimizing video quality based on internet speed.
Used FFmpeg for video processing tasks including conversion, editing, and streaming, leveraging its support for a wide range of codecs and formats.


How Video Streaming Works
Video streaming works by sending video data over the internet in small packets. These packets are then reassembled on the user's device and played back in real-time. This allows users to watch videos without having to wait for the entire video to download. Video streaming services use specialized servers to deliver video content to users, ensuring a smooth and uninterrupted viewing experience.

Role of Codecs in Video Streaming
Codecs play a crucial role in video streaming by compressing and decompressing video data. They help reduce the size of video files, making it easier to transmit them over the internet. Common video codecs include H.264, H.265, and VP9. Choosing the right codec is essential for ensuring high-quality video streaming with minimal buffering.

M3U8 is a common format used for streaming video content over the internet. It is widely supported by video streaming services and allows for adaptive bitrate streaming, which adjusts the video quality based on the user's internet connection speed.

Role of ffmpeg in Video Streaming
FFmpeg is so far the only open-source software that can handle almost all video and audio formats. It is a powerful tool for video processing and streaming, allowing users to convert, edit, and stream video content. FFmpeg supports a wide range of codecs and formats, making it a versatile tool for video streaming applications.
