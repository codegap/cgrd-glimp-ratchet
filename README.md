cgrd-glimp-ratchet
=======================

Ratchet version of Glimp prototype application.

The prototype is iPhone only, Ratchet doesn't support other platforms very well.
Developing a simple UI is _very_ easy, so will probably used again in the future for quick proof of concepts.

Two index files: one with a list of name + thumbnails, the other (index-slider.html) with an image slideshow.

The latter is somewhat broken: ontouchstart and onclick don't play nice together. Won't fix at this point; it's not the point of this exercise to make this prototype work flawlessly.


For simple, free html hosting, you can use Pancake.io (http://pancake.io) or Google Drive (https://googledrive.com/host/0B716ywBKT84AMXBENXlnYmJISlE/GoogleDriveHosting.html)



Local hosting
Find out what's your current IP address:

ipconfig getifaddr en1
(en1 = wireless, use en0 if using UTP)


Host current directory:

python -m SimpleHTTPServer 9999


Point browser to

[ip address]:9999

On iPhone, use 'Add to Home Screen' to create an icon on the 'desktop' and cache the app locally.

