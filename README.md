# Voice Driven Development

## Generating PDF slides
decktape remark http://127.0.0.1:8000/presentation.html voice_driven_development_slides.pdf

## Updating Remark
node make bundle
node make minify
cp out/remark.min.js ../perl_out_loud/
