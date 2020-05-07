### Jitsi

- https://jitsi.org/jitsi-meet/
- https://github.com/jitsi
- https://github.com/jitsi/libjitsi
- https://github.com/jitsi/lib-jitsi-meet
- https://github.com/jitsi/jitsi-meet/blob/master/doc/api.md

### Jitsi Example

- https://github.com/jitsi/lib-jitsi-meet
- API Docs: https://github.com/jitsi/lib-jitsi-meet/blob/master/doc/API.md#jitsi-meet-api
- Getting Started: https://github.com/jitsi/lib-jitsi-meet/blob/master/doc/API.md#getting-started
- Example from Jitsi: https://github.com/jitsi/lib-jitsi-meet/tree/master/doc/example

---

[Meeting URL](:?meetingURL)
[Participant Name](:!participantName)


```javascript /playable/autoplay
//smartdown.import=https://code.jquery.com/jquery-3.4.1.slim.min.js
//smartdown.import=https://meet.jit.si/libs/lib-jitsi-meet.min.js

const log = this.log;

smartdown.set({
  meetingURL: 'https://jitsi.emeraldbroadband.com/VirtualTownSquare',
  participantName: 'DoctorBud',
});

this.dependOn.meetingURL = () => {
  log('meetingURL', env.meetingURL);
  this.div.innerHTML =
`
<h4>${env.meetingURL}</h4>
`;
};

  const options = {

  };
  JitsiMeetJS.init(options);

  // log('JitsiMeetJS.mediaDevices.enumerateDevices');
  // JitsiMeetJS.mediaDevices.enumerateDevices(devices => {
  //   // enumerateDevices(callback) - returns list of the available devices as a parameter to the callback function. Every device is a MediaDeviceInfo object with the following properties:
  //   // label - the name of the device
  //   // kind - "audioinput", "videoinput" or "audiooutput"
  //   // deviceId - the id of the device
  //   // groupId - group identifier, two devices have the same group identifier if they belong to the same physical device; for example a monitor with both a built-in camera and microphone
  //   log(devices);
  // });

  const connectionOptions = {};
  const connection = new JitsiMeetJS.JitsiConnection(null, null, connectionOptions);

```

---

[Back to Home](:@Home)
