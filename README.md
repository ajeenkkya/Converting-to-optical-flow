# Converting-to-optical-flow
This code snippet records video from webcam and convert it to optical flow video. On pressing "s" it starts recording and gives prints a message 'Started recording' and again on pressing "s" it stops recording and directly starts convering the clip to optical flow.
While conversion the dialog box freezes but it starts again after conversion. Also, the naming is case specific so if you want to linearly name it then just remove the if else on 34-37 lines and change 0.5 to 1 on line 66.

One advantage of this is that you don't need to worry about the background(if it's still ofcourse). Also checkout my hand waving skills
## The video from webcam:
![webcam_vid](https://user-images.githubusercontent.com/35074988/74834392-560e9f80-5341-11ea-8fa0-0be2d78367db.gif)
## The converted video:
![optical_flow_vid](https://user-images.githubusercontent.com/35074988/74834524-953cf080-5341-11ea-9d5a-74de7ce270ed.gif)
