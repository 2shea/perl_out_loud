# Voice Driven Development

## Setup
Install `git-lfs` for the large files (videos and images). This is required to clone this repo:
```
brew install git-lfs
```

## Keyboard Shortcuts
Next Slide:  fn + down
Last Slide:  fn + up
Beginning:  home
Presentation Notes:  f10
Presentation Fullscreen: f9
Restart Timer:  f8
Video Fullscreen:  cntrl + enter
Video Play:  tab + space

## Generating PDF slides
decktape remark http://127.0.0.1:8000/presentation.html voice_driven_development_slides.pdf

## Updating Remark
node make bundle
node make minify
cp out/remark.min.js ../perl_out_loud/
