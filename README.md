#Face Detection Algorithm with OpenCV and Node.js in Javascripts

A simple application for face detection.

This can be considered a simple way compared with Facebook in displaying an uploaded photo back to a user with the faced detect and asking people to tag them.

This application uses the open-source [OpenCV](http://opencv.org/) library and particularly the [Viola-Jones object detection algorithm](https://en.wikipedia.org/wiki/Viola%E2%80%93Jones_object_detection_framework). 

TO be able to run OpenCV in Nodejs you should refer to [opencv](https://www.npmjs.com/package/opencv) package.

Also in this application a tutorial has been provided: [Build a Face Detection App Using Nodejs and OpenCV](http://www.sitepoint.com/face-detection-nodejs-opencv)

##Quick Start of the algorithm

```bash
git clone https://github.com/smajida/facedetectionCV-nodejs-OpenCV
cd facedetectionCV-nodejs-OpenCV
vagrant up
vagrant ssh
cd /vagrant
npm install
node index.js 
```

Then in webbrowser refer to:
```
http://192.168.10.10:8080/
```
