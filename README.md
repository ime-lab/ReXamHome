
ReXamHome is a small web (html+javascript) program that is used
to record a computer screen and webcam to a video file.
The main purpose of the program is for recording what
happens during an exam done from student's home. The video
can be used to discourage/prevent as well as to detect cheating
(by proctors) during an exam from home.
The program has two parts. The first part handles screen and
webcam recording. The second part is a utility to calculate
a (video) file checksum. All captured information is processed
and stored locally. A student must upload the file immediately after
finishing the exam. In case that video uploading is
not possible or with failure, students must send the video
file checksum to exam proctors instead. An actual
video file can be delivered to a proctor later.
Sending a checksum is sometimes the only possibility for
students who lack internet connection, low-speed connection,
or whose connection is broken or unreliable.
The program is composed of
- startReXam.html : a simple html file to launch the actual recording part.
- ReXamHome.html : an actual recording and checksum part.
- Dependencies: The program requires these javascript libraries
  - jquery-min.js
  - RecordRTC: RecordRTC.js, EBML.js
  - CryptoJS : core.js, md5.js
- ReXamHome_cdn.html : an cloud or hosted version of ReXamHome.html. It links to a CDN version of the above javascript libraries.
