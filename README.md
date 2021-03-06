# CricView

In this project we aim to give the user a personal viewing experience of the places where human intervention is not feasible at given time or of the places that are comparatively difficult to reach by humans.

It consists of 2 modules:
1. VR (Virtual Reality)
2. OCYV (On Command Youtube View)

APIs mainly used for collecting youtube comments are:<br>
1. https://www.googleapis.com/youtube/v3/liveBroadcasts/?part=snippet&broadcastStatus=active&broadcastType=persistent
2. https://www.googleapis.com/youtube/v3/liveChat/messages?liveChatId=EiEKGFVDMExWM0xVSk9YYlozSEF3T3I2SG9sQRIFL2xpdmU&part=snippet

APIs data is processed and the relevant data is made live to cloud from where servo motors take in the input 
and rotate the camera's direction as per user's will.

Processings done:
1. Zoom in out feature by commenting / moving forward and backward
2. Creating a 360 degree camera (VR view) by 1 camera 

Such technology stack is of much relevance at every place where user experience of the videos need to be precise and more immersive as well as at broadcast level at very cost efficient manner.

Our main focus in this project was to give person the true experience of cricket stadium while sitting up at home.

This tech stack can be used in various other domains. Some of them include:
1. Construction sites (bricklaying etc.) 
2. Office surveillance
3. Tourist places (eg. Qutub Minar, Red Fort etc.)

Presentation Link:<br>
https://github.com/iamjaspreetsingh/SuperView/blob/master/SuperView%20ppt.pdf
