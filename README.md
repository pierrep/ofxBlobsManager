BlobsManager
============


A manager for openCV blobs. 
Functionalities: 
- By storing blobs and comparing them with new blobs it can track moving blobs.
- Doing that it will give blobs id's.
- It can give sequential id's (every new blob gets a higher id) or it can find the lowest possible id's.
- It has a easy optional debug draw.
- It has a optional "max undetected time" so it will remember blobs that disappear for a moment.
- It has a optional "min detected time" so it will ignore blobs only appear for a short moment.
- Optionally normalize the movement, making it less "shaky".
It's basically a lot of things you usually need when working with blobs. 
