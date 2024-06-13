# pranklockng

Based on RealOrangeOne's [prankclock](https://github.com/RealOrangeOne/pranklock), which is based on the original work of [@Adimote](https://github.com/adimote) in [this version](https://github.com/trickeydan/dotfiles-ubuntu/blob/master/files/desktop/i3/pranklock.sh).

Locks the screen with a screenshot of the desktop. If any key is pressed, or the mouse moves, display a meme and capture both an image and a video with the webcam, and lock the screen again using that meme.

## Dependencies

- `i3lock`
- `ffmpeg`
- `xdotool`
- some good memes (default memes included)

## Usage

1. Install the above dependencies
2. Run the `pranklock` script to _lock_ your screen

By default, the first webcam (`/dev/video0`) is used. To change this, pass the video device as an argument (eg `pranklock /dev/video1`)

3. To safely unlock without showing the webcam image, press the Escape key. You can then unlock as normal.
