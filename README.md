# How to download and encode a YouTube video to be able to use it in Davinci Resolve on macOS

1. Download the latest YouTube-DLP release: https://github.com/yt-dlp/yt-dlp/releases/latest
2. Make it executable: `chmod +x yt-dlp_macos`
3. Run it with the YouTube video URL: `./yt-dlp_macos https://youtube.com/watch?v=…`
4. Wait for the download to complete and find the WebM file named after the video
5. Download the latest FFMPEG release: https://ffmpeg.org/download.html#build-mac
6. Convert WebM to MOV: `ffmpeg -i video.webm video.mov`
