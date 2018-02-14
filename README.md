# distant-pictures
A simple server that serves webcam pictures to a website. 

What changed
Compare helloYou/server.js and distant-pictures/pictureServer.js. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called diff that compares files.)
Ans. The ‘node-webcam’ package (Available at npmjs.com) was added to enable the camera. It’s functionality was utilized by creating a default constructor ‘opts’ and a webcam object using NodeWebcam.create(). Further, the image was captured in /public folder and then displayed it (io.emit()) on the webapp.



Peephole
Now, edit the pictureServer.js code for a Peephole device. When a person presses the doorbell (here, the button on your Arduino), the application should snap a photo of the person in front of the doorbell, and post it to a remote webpage.
Please submit the code for the Peephole as part of your turn-in.
Ans. Implemented by tracking "light" serial output sent by Arduino and calling "takePicture()" function when that happens.

Your own distributed camera app
As in the previous lab, modify the template for the lab to make it your own. You can do this just through text, better html and reframing the point of view, or you can incorporate technical improvements from the next part of the assignment...
Ans.Played around with HTML and added some CSS (Buttons and Polaroid Image Container.)


Try a new node library/package
Find, install, and try out a node-based library and try to incorporate into your lab.
Document your successes and failures (totally okay!) for your Slack lab#2 turn-in. This will help the class community figure out cool new tools and capabilities. 
Ans. Successes: 
