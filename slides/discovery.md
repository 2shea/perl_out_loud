class: middle, center, painvert
Voice??

---
class: middle, discovery
I was expecting writing perl by voice to go something like this...

---
class: center, middle, black
<video id='vista_perl' class='video-js' controls preload='auto' width='700' data-setup='{}'>
  <source src="videos/vista_perl_cut.mp4" type="video/mp4">
</video>

.attribution_vista[[Windows Vista Speech Recognition Tested - Perl Scripting, by scrubadub1](https://youtu.be/MzJ0CytAsec)]

???
Windows Vista Speech Recognition Tested Perl Scripting
scrubadub1
original video is 10 mins, i have cut it

---
class: center, middle, discovery
But it actually works like...

---
class: center, middle, black
<video id='can_do_better' class='video-js' controls preload='auto' width='700' data-setup='{}'>
  <source src="videos/I_can_do_better.mp4" type="video/mp4">
</video>

???
same code
intentionally left errors

---
class: center, middle, painvert
But... How??
---
class: discovery
## The Tech

Microphone 🎤

Dragon Dictation <img src="images/dragon_logo.gif" height="50px" 
alt="alphabet sounds">

Talon <img src="images/talon_logo.png" height="50px" alt="alphabet sounds">

???
- for mac
- need decent microphone
---
class: discovery
## What Is Talon?
* Hands-free input
* Uses Dragon Dictation API
* Programmatically configured with Python
* Free!
* https://www.patreon.com/lunixbochs

???
Software that allows you to use hands free input to interact with your computer
it's very new (2018), and currently only mac
* (voice/noise commands, eye tracking)
free, but patreon support

This talk is not about Talon... it's an example of how Talon can be used. All 
the commands and tools you will see are built on top of Talon's API.
* Mention what dragon is
* Also has a built-in voice engine
---
