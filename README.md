
# ReXamHome : Screen recorder for proctoring exam from home

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
not possible or failed at the time the exam finishing, a student must send the video
file checksum to exam proctors instead. An actual
video file can be delivered to a proctor later to check exam integrity.
Sending a checksum as a proof of video authenticity is sometimes needed for
students who lack internet connection, low-speed connection,
or whose connection is broken or unreliable.
The program is composed of
- startReXam.html : a simple html file to launch the actual recording part.
- ReXamHome.html : an actual recording and checksum part.
- Dependencies: The program requires these javascript libraries
  - jquery-min.js
  - RecordRTC: RecordRTC.js, EBML.js
  - CryptoJS : core.js, md5.js
- ReXamHome_cdn.html : a cloud & hosted version of ReXamHome.html. It contains links to a CDN version of the above javascript libraries.

For more information on related libaries see:
- https://github.com/muaz-khan/RecordRTC
- https://cryptojs.gitbook.io/docs/

See also related blogs below.
- [การจัดสอบในที่พักของผู้สอบ](https://medium.com/@nop_itkmitl/การจัดสอบในที่พักของผู้สอบ-exam-from-home-ตอนที่-1-55508acc735f)
- [ReXamHome : โปรแกรมบันทึกหน้าจอการทำข้อสอบจากที่บ้าน](https://medium.com/@nop_itkmitl/rexamhome-โปรแกรมบันทึกหน้าจอการทำข้อสอบจากที่บ้าน-d3d34582a5f6)

The program was developed for use at the Faculty of Information Technology (IT), King Mongkut's Institute of Technology Ladkrabang (KMITL). It is part of the research project on online learning and examination at the Interactive Media and Security Lab (ime-lab), [Faculty of IT, KMITL.](http://www.it.kmitl.ac.th)
