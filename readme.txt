convert -delay 10 -loop 1 *.JPG result.gif

ffmpeg -i result.gif -vf scale=640:480 result_640x480.gif