useful links:
https://developer.mozilla.org/ru/docs/Web/API/Screen_Capture_API/Using_Screen_Capture
https://developer.mozilla.org/ru/docs/Web/API/MediaDevices/getDisplayMedia
https://developer.mozilla.org/ru/docs/Web/API/MediaDevices/getUserMedia
https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API
https://webrtc.github.io/samples/
https://github.com/shanet/WebRTC-Example

https://github.com/webrtc/samples/blob/gh-pages/src/content/devices/input-output/js/main.js


certs:
openssl req -newkey rsa:2048 -new -nodes -keyout key.pem -out csr.pem
openssl x509 -req -days 365 -in csr.pem -signkey key.pem -out server.crt

adapter is for compatibility:
https://github.com/webrtcHacks/adapter