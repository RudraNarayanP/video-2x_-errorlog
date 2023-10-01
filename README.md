[32m[+] INFO: Loading files into processing queue[0m
[90m2023-10-01 16:38:16.002454 [+] INFO: Input path(s): C:\Users\Administrator\Videos\Captures\2023-09-30 22-51-45.mp4 2023-10-01 01-59-57.mp4[0m
[90m2023-10-01 16:38:16.005452 [+] INFO: File MIME type: video/mp4[0m
[32m[+] INFO: Loaded files into processing queue[0m
[90m2023-10-01 16:38:16.011873 [+] INFO: Input file: C:\Users\Administrator\Videos\Captures\2023-09-30 22-51-45.mp4 2023-10-01 01-59-57.mp4[0m
[32m[+] INFO: Reading file information[0m
[90m2023-10-01 16:38:16.017924 [+] INFO: Executing: C:\Users\ADMINI~1\AppData\Local\Temp\Rar$EXa0.564\video2x-4.8.1-win32-full\dependencies\ffmpeg\bin\ffprobe -v quiet -print_format json -show_format -show_streams -i C:\Users\Administrator\Videos\Captures\2023-09-30 22-51-45.mp4 2023-10-01 01-59-57.mp4[0m
[90m2023-10-01 16:38:19.347111 [+] INFO: Creating cache directory C:\Users\ADMINI~1\AppData\Local\Temp\video2x[0m
[90m2023-10-01 16:38:19.348094 [+] INFO: Extracted frames are being saved to: C:\Users\ADMINI~1\AppData\Local\Temp\video2x\tmpd1b1rltj[0m
[90m2023-10-01 16:38:19.349109 [+] INFO: Upscaled frames are being saved to: C:\Users\ADMINI~1\AppData\Local\Temp\video2x\tmp196vb903[0m
[32m[+] INFO: Starting upscaling video/GIF[0m
[32m[+] INFO: Getting total number of frames in the file[0m
[32m[+] INFO: Calculating scaling parameters[0m
[90m2023-10-01 16:38:19.350090 [+] INFO: Framerate: 60.0[0m
[90m2023-10-01 16:38:19.350090 [+] INFO: Width: 1024[0m
[90m2023-10-01 16:38:19.350090 [+] INFO: Height: 680[0m
[90m2023-10-01 16:38:19.351091 [+] INFO: Total number of frames: 1847[0m
[90m2023-10-01 16:38:19.351091 [+] INFO: Output width: 2048[0m
[90m2023-10-01 16:38:19.351091 [+] INFO: Output height: 1360[0m
[90m2023-10-01 16:38:19.351091 [+] INFO: Required scale ratio: 2.0[0m
[90m2023-10-01 16:38:19.351091 [+] INFO: Upscaling jobs queue: [2][0m
[90m2023-10-01 16:38:19.352090 [+] INFO: Executing: C:\Users\ADMINI~1\AppData\Local\Temp\Rar$EXa0.564\video2x-4.8.1-win32-full\dependencies\ffmpeg\bin\ffmpeg -hwaccel auto -y -i C:\Users\Administrator\Videos\Captures\2023-09-30 22-51-45.mp4 2023-10-01 01-59-57.mp4 -pix_fmt rgb24 C:\Users\ADMINI~1\AppData\Local\Temp\video2x\tmpd1b1rltj\extracted_%0d.png[0m
[90m2023-10-01 16:38:22.550367 [+] INFO: Main process waiting for subprocesses to exit[0m
ffmpeg version 4.3.1-2020-11-19-full_build-www.gyan.dev Copyright (c) 2000-2020 the FFmpeg developers
  built with gcc 10.2.0 (Rev5, Built by MSYS2 project)
  configuration: --enable-gpl --enable-version3 --enable-static --disable-w32threads --disable-autodetect --enable-fontconfig --enable-iconv --enable-gnutls --enable-libxml2 --enable-gmp --enable-lzma --enable-libsnappy --enable-zlib --enable-libsrt --enable-libssh --enable-libzmq --enable-avisynth --enable-libbluray --enable-libcaca --enable-sdl2 --enable-libdav1d --enable-libzvbi --enable-librav1e --enable-libwebp --enable-libx264 --enable-libx265 --enable-libxvid --enable-libaom --enable-libopenjpeg --enable-libvpx --enable-libass --enable-frei0r --enable-libfreetype --enable-libfribidi --enable-libvidstab --enable-libvmaf --enable-libzimg --enable-amf --enable-cuda-llvm --enable-cuvid --enable-ffnvcodec --enable-nvdec --enable-nvenc --enable-d3d11va --enable-dxva2 --enable-libmfx --enable-libcdio --enable-libgme --enable-libmodplug --enable-libopenmpt --enable-libopencore-amrwb --enable-libmp3lame --enable-libshine --enable-libtheora --enable-libtwolame --enable-libvo-amrwbenc --enable-libilbc --enable-libgsm --enable-libopencore-amrnb --enable-libopus --enable-libspeex --enable-libvorbis --enable-ladspa --enable-libbs2b --enable-libflite --enable-libmysofa --enable-librubberband --enable-libsoxr --enable-chromaprint
  libavutil      56. 51.100 / 56. 51.100
  libavcodec     58. 91.100 / 58. 91.100
  libavformat    58. 45.100 / 58. 45.100
  libavdevice    58. 10.100 / 58. 10.100
  libavfilter     7. 85.100 /  7. 85.100
  libswscale      5.  7.100 /  5.  7.100
  libswresample   3.  7.100 /  3.  7.100
  libpostproc    55.  7.100 / 55.  7.100
Input #0, mov,mp4,m4a,3gp,3g2,mj2, from 'C:\Users\Administrator\Videos\Captures\2023-09-30 22-51-45.mp4 2023-10-01 01-59-57.mp4':
  Metadata:
    major_brand     : mp42
    minor_version   : 0
    compatible_brands: mp41isom
    creation_time   : 2023-09-30T20:30:57.000000Z
    artist          : Microsoft Game DVR
    title           : 2023-09-30 22-51-45.mp4
  Duration: 00:01:02.77, start: 0.000000, bitrate: 3627 kb/s
    Stream #0:0(und): Video: h264 (Main) (avc1 / 0x31637661), yuv420p, 1024x680 [SAR 1:1 DAR 128:85], 3361 kb/s, 29.43 fps, 60 tbr, 30k tbn, 59.94 tbc (default)
    Metadata:
      creation_time   : 2023-09-30T20:30:57.000000Z
      handler_name    : VideoHandler
      encoder         : AVC Coding
    Stream #0:1(und): Audio: aac (LC) (mp4a / 0x6134706D), 48000 Hz, stereo, fltp, 128 kb/s (default)
    Metadata:
      creation_time   : 2023-09-30T20:30:57.000000Z
      handler_name    : SoundHandler
[h264 @ 0000020162d7e040] Using auto hwaccel type dxva2 with new default device.
Stream mapping:
  Stream #0:0 -> #0:0 (h264 (native) -> png (native))
Press [q] to stop, [?] for help
Output #0, image2, to 'C:\Users\ADMINI~1\AppData\Local\Temp\video2x\tmpd1b1rltj\extracted_%0d.png':
  Metadata:
    major_brand     : mp42
    minor_version   : 0
    compatible_brands: mp41isom
    title           : 2023-09-30 22-51-45.mp4
    artist          : Microsoft Game DVR
    encoder         : Lavf58.45.100
    Stream #0:0(und): Video: png, rgb24, 1024x680 [SAR 1:1 DAR 128:85], q=2-31, 200 kb/s, 29.97 fps, 29.97 tbn, 29.97 tbc (default)
    Metadata:
      creation_time   : 2023-09-30T20:30:57.000000Z
      handler_name    : VideoHandler
      encoder         : Lavc58.91.100 png
frame=   60 fps=0.0 q=-0.0 size=N/A time=00:00:01.83 bitrate=N/A dup=1 drop=1 speed=3.66x    
frame=  121 fps=120 q=-0.0 size=N/A time=00:00:03.80 bitrate=N/A dup=1 drop=1 speed=3.77x    
frame=  178 fps=118 q=-0.0 size=N/A time=00:00:05.70 bitrate=N/A dup=1 drop=1 speed=3.77x    
frame=  235 fps=117 q=-0.0 size=N/A time=00:00:07.60 bitrate=N/A dup=1 drop=1 speed=3.77x    
frame=  295 fps=117 q=-0.0 size=N/A time=00:00:09.57 bitrate=N/A dup=2 drop=1 speed=3.79x    
frame=  354 fps=117 q=-0.0 size=N/A time=00:00:11.54 bitrate=N/A dup=2 drop=1 speed=3.81x    
frame=  412 fps=116 q=-0.0 size=N/A time=00:00:13.48 bitrate=N/A dup=2 drop=1 speed=3.81x    
frame=  471 fps=117 q=-0.0 size=N/A time=00:00:15.44 bitrate=N/A dup=2 drop=1 speed=3.82x    
frame=  530 fps=117 q=-0.0 size=N/A time=00:00:17.41 bitrate=N/A dup=3 drop=1 speed=3.83x    
frame=  588 fps=117 q=-0.0 size=N/A time=00:00:19.35 bitrate=N/A dup=3 drop=1 speed=3.83x    
frame=  648 fps=117 q=-0.0 size=N/A time=00:00:21.35 bitrate=N/A dup=3 drop=1 speed=3.85x    
frame=  707 fps=117 q=-0.0 size=N/A time=00:00:23.32 bitrate=N/A dup=3 drop=1 speed=3.85x    
frame=  767 fps=117 q=-0.0 size=N/A time=00:00:25.32 bitrate=N/A dup=4 drop=1 speed=3.86x    
frame=  823 fps=117 q=-0.0 size=N/A time=00:00:27.19 bitrate=N/A dup=4 drop=1 speed=3.85x    
frame=  882 fps=117 q=-0.0 size=N/A time=00:00:29.16 bitrate=N/A dup=4 drop=1 speed=3.86x    
frame=  942 fps=117 q=-0.0 size=N/A time=00:00:31.16 bitrate=N/A dup=5 drop=1 speed=3.86x    
frame= 1001 fps=117 q=-0.0 size=N/A time=00:00:33.13 bitrate=N/A dup=5 drop=1 speed=3.87x    
frame= 1060 fps=117 q=-0.0 size=N/A time=00:00:35.10 bitrate=N/A dup=5 drop=1 speed=3.87x    
frame= 1119 fps=117 q=-0.0 size=N/A time=00:00:37.07 bitrate=N/A dup=6 drop=1 speed=3.87x    
frame= 1181 fps=117 q=-0.0 size=N/A time=00:00:39.13 bitrate=N/A dup=8 drop=1 speed=3.88x    
frame= 1244 fps=118 q=-0.0 size=N/A time=00:00:41.24 bitrate=N/A dup=12 drop=1 speed= 3.9x    
frame= 1305 fps=118 q=-0.0 size=N/A time=00:00:43.27 bitrate=N/A dup=15 drop=1 speed= 3.9x    
frame= 1363 fps=118 q=-0.0 size=N/A time=00:00:45.21 bitrate=N/A dup=17 drop=1 speed= 3.9x    
frame= 1420 fps=117 q=-0.0 size=N/A time=00:00:47.11 bitrate=N/A dup=17 drop=1 speed= 3.9x    
frame= 1482 fps=118 q=-0.0 size=N/A time=00:00:49.18 bitrate=N/A dup=22 drop=1 speed= 3.9x    
frame= 1542 fps=118 q=-0.0 size=N/A time=00:00:51.18 bitrate=N/A dup=26 drop=1 speed=3.91x    
frame= 1601 fps=118 q=-0.0 size=N/A time=00:00:53.15 bitrate=N/A dup=27 drop=1 speed=3.91x    
frame= 1660 fps=118 q=-0.0 size=N/A time=00:00:55.12 bitrate=N/A dup=30 drop=1 speed=3.91x    
frame= 1720 fps=118 q=-0.0 size=N/A time=00:00:57.12 bitrate=N/A dup=33 drop=1 speed=3.91x    
frame= 1779 fps=118 q=-0.0 size=N/A time=00:00:59.09 bitrate=N/A dup=36 drop=1 speed=3.91x    
frame= 1838 fps=118 q=-0.0 size=N/A time=00:01:01.06 bitrate=N/A dup=36 drop=1 speed=3.91x    
frame= 1883 fps=117 q=-0.0 Lsize=N/A time=00:01:02.82 bitrate=N/A dup=37 drop=1 speed=3.91x    
video:483251kB audio:0kB subtitle:0kB other streams:0kB global headers:0kB muxing overhead: unknown
[90m2023-10-01 16:38:38.755907 [+] INFO: Subprocess 14480 exited with code 0[0m
[32m[+] INFO: Starting to upscale extracted frames[0m
[90m2023-10-01 16:38:38.880884 [+] INFO: [upscaler] Subprocess 15076 executing: C:\Users\ADMINI~1\AppData\Local\Temp\Rar$EXa0.564\video2x-4.8.1-win32-full\dependencies\waifu2x-ncnn-vulkan\waifu2x-ncnn-vulkan -n 2 -s 2 -t 400 -m C:\Users\ADMINI~1\AppData\Local\Temp\Rar$EXa0.564\video2x-4.8.1-win32-full\dependencies\waifu2x-ncnn-vulkan\models-cunet -g 0 -j 1:1:1 -f png -i C:\Users\ADMINI~1\AppData\Local\Temp\video2x\tmpd1b1rltj -o C:\Users\ADMINI~1\AppData\Local\Temp\video2x\tmp196vb903[0m
[90m2023-10-01 16:38:39.740198 [+] INFO: Starting progress monitor[0m
[90m2023-10-01 16:38:39.740198 [+] INFO: Starting upscaled image cleaner[0m
[90m2023-10-01 16:38:39.740198 [+] INFO: Main process waiting for subprocesses to exit[0m

Processing: 2023-09-30 22-51-45.mp4 2023-10-01 01-59-57.mp4 (pass 1/1):   0%|                 | 0/1847 [00:00<?, ?it/s][31m[1m[!] ERROR: Subprocess 15316 exited with code 3221225781[0m
[31m[1m[!] ERROR: Subprocess execution ran into an error[0m
[33m[1m[!] WARNING: Terminating all processes[0m
[90m2023-10-01 16:38:39.865241 [+] INFO: Killing progress monitor[0m

Processing: 2023-09-30 22-51-45.mp4 2023-10-01 01-59-57.mp4 (pass 1/1):   0%|                 | 0/1847 [00:01<?, ?it/s]
[90m2023-10-01 16:38:40.787053 [+] INFO: Killing upscaled image cleaner[0m
Cleaning up cache directory: C:\Users\ADMINI~1\AppData\Local\Temp\video2x\tmpd1b1rltj
Cleaning up cache directory: C:\Users\ADMINI~1\AppData\Local\Temp\video2x\tmp196vb903
Cleaning up cache directory: C:\Users\ADMINI~1\AppData\Local\Temp\video2x
Traceback (most recent call last):
  File "video2x_gui.py", line 105, in run
  File "upscaler.py", line 1022, in run
  File "upscaler.py", line 849, in run
  File "upscaler.py", line 416, in _upscale_frames
  File "upscaler.py", line 408, in _upscale_frames
  File "upscaler.py", line 489, in _wait
  File "upscaler.py", line 467, in _wait
subprocess.CalledProcessError: Command '['C:\\Users\\ADMINI~1\\AppData\\Local\\Temp\\Rar$EXa0.564\\video2x-4.8.1-win32-full\\dependencies\\waifu2x-ncnn-vulkan\\waifu2x-ncnn-vulkan', '-n', '2', '-s', '2', '-t', '400', '-m', 'C:\\Users\\ADMINI~1\\AppData\\Local\\Temp\\Rar$EXa0.564\\video2x-4.8.1-win32-full\\dependencies\\waifu2x-ncnn-vulkan\\models-cunet', '-g', '0', '-j', '1:1:1', '-f', 'png', '-i', 'C:\\Users\\ADMINI~1\\AppData\\Local\\Temp\\video2x\\tmpd1b1rltj', '-o', 'C:\\Users\\ADMINI~1\\AppData\\Local\\Temp\\video2x\\tmp196vb903']' returned non-zero exit status 3221225781.
