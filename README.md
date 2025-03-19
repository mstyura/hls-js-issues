# hls-js-issues

## Playback of segments with single video sample

HLS stream with single black video frame per mpeg-ts fragment, pronunciation of sequence of "b", "c", "d", "e", "f", "g", "a", "b".

* [hls.js latest (at the moment of check is v1.6.0-beta.4.0.canary.11066)](https://hlsjs-dev.video-dev.org/demo/?src=https%3A%2F%2Fmstyura.github.io%2Fhls-js-issues%2Fsegments-with-single-video-sample%2Fgithub.m3u8&demoConfig=eyJlbmFibGVTdHJlYW1pbmciOnRydWUsImF1dG9SZWNvdmVyRXJyb3IiOnRydWUsInN0b3BPblN0YWxsIjpmYWxzZSwiZHVtcGZNUDQiOmZhbHNlLCJsZXZlbENhcHBpbmciOi0xLCJsaW1pdE1ldHJpY3MiOi0xfQ==) - plays 3 of 6 seconds "b", "c", "d", "e"
* [hls.js v1.5.20](https://5982f183.hls-js-dev.pages.dev/demo/?src=https%3A%2F%2Fmstyura.github.io%2Fhls-js-issues%2Fsegments-with-single-video-sample%2Fgithub.m3u8&demoConfig=eyJlbmFibGVTdHJlYW1pbmciOnRydWUsImF1dG9SZWNvdmVyRXJyb3IiOnRydWUsInN0b3BPblN0YWxsIjpmYWxzZSwiZHVtcGZNUDQiOmZhbHNlLCJsZXZlbENhcHBpbmciOi0xLCJsaW1pdE1ldHJpY3MiOi0xfQ==) - plays 3 of 6 seconds "b", "c", "d", "e"
* [hls.js v1.2.5](https://hls-js-acf592b8-566a-4553-aa84-d2d6adcdc0db.netlify.app/demo/?src=https%3A%2F%2Fmstyura.github.io%2Fhls-js-issues%2Fsegments-with-single-video-sample%2Fgithub.m3u8&demoConfig=eyJlbmFibGVTdHJlYW1pbmciOnRydWUsImF1dG9SZWNvdmVyRXJyb3IiOnRydWUsInN0b3BPblN0YWxsIjpmYWxzZSwiZHVtcGZNUDQiOmZhbHNlLCJsZXZlbENhcHBpbmciOi0xLCJsaW1pdE1ldHJpY3MiOi0xfQ==) - plays 3 of 6 seconds "b", "c", "d", "e"
* [hls.js v1.2.4](https://hls-js-357e5663-c334-422c-88d9-fcfbf938b5dc.netlify.app/demo/?src=https%3A%2F%2Fmstyura.github.io%2Fhls-js-issues%2Fsegments-with-single-video-sample%2Fgithub.m3u8&demoConfig=eyJlbmFibGVTdHJlYW1pbmciOnRydWUsImF1dG9SZWNvdmVyRXJyb3IiOnRydWUsInN0b3BPblN0YWxsIjpmYWxzZSwiZHVtcGZNUDQiOmZhbHNlLCJsZXZlbENhcHBpbmciOi0xLCJsaW1pdE1ldHJpY3MiOi0xfQ==) - does not play at all;
* [hls.js v1.2.3](https://hls-js-a7277301-16b6-4ae9-b56a-dbb2ae208a9c.netlify.app/demo/?src=https%3A%2F%2Fmstyura.github.io%2Fhls-js-issues%2Fsegments-with-single-video-sample%2Fgithub.m3u8&demoConfig=eyJlbmFibGVTdHJlYW1pbmciOnRydWUsImF1dG9SZWNvdmVyRXJyb3IiOnRydWUsInN0b3BPblN0YWxsIjpmYWxzZSwiZHVtcGZNUDQiOmZhbHNlLCJsZXZlbENhcHBpbmciOi0xLCJsaW1pdE1ldHJpY3MiOi0xfQ==) - does not play at all;
* [hls.js v1.2.2](https://hls-js-e9b6f668-5edb-4682-a6af-034455d028b1.netlify.app/demo/?src=https%3A%2F%2Fmstyura.github.io%2Fhls-js-issues%2Fsegments-with-single-video-sample%2Fgithub.m3u8&demoConfig=eyJlbmFibGVTdHJlYW1pbmciOnRydWUsImF1dG9SZWNvdmVyRXJyb3IiOnRydWUsInN0b3BPblN0YWxsIjpmYWxzZSwiZHVtcGZNUDQiOmZhbHNlLCJsZXZlbENhcHBpbmciOi0xLCJsaW1pdE1ldHJpY3MiOi0xfQ==) - does not play at all;
* [hls.js v1.2.1](https://hls-js-c682795c-032a-4c39-9374-225b776c04f6.netlify.app/demo/?src=https%3A%2F%2Fmstyura.github.io%2Fhls-js-issues%2Fsegments-with-single-video-sample%2Fgithub.m3u8&demoConfig=eyJlbmFibGVTdHJlYW1pbmciOnRydWUsImF1dG9SZWNvdmVyRXJyb3IiOnRydWUsInN0b3BPblN0YWxsIjpmYWxzZSwiZHVtcGZNUDQiOmZhbHNlLCJsZXZlbENhcHBpbmciOi0xLCJsaW1pdE1ldHJpY3MiOi0xfQ==) - does not play at all;
* [hls.js v1.2.0](https://hls-js-bbdf933d-da48-407d-aaf3-68cc4ee058e7.netlify.app/demo/?src=https%3A%2F%2Fmstyura.github.io%2Fhls-js-issues%2Fsegments-with-single-video-sample%2Fgithub.m3u8&demoConfig=eyJlbmFibGVTdHJlYW1pbmciOnRydWUsImF1dG9SZWNvdmVyRXJyb3IiOnRydWUsInN0b3BPblN0YWxsIjpmYWxzZSwiZHVtcGZNUDQiOmZhbHNlLCJsZXZlbENhcHBpbmciOi0xLCJsaW1pdE1ldHJpY3MiOi0xfQ==) - does not play at all;
* [hls.js v1.1.5](https://hls-js-eb7b4375-60e8-4617-93ce-d0d9ef584df1.netlify.app/demo/?src=https%3A%2F%2Fmstyura.github.io%2Fhls-js-issues%2Fsegments-with-single-video-sample%2Fgithub.m3u8&demoConfig=eyJlbmFibGVTdHJlYW1pbmciOnRydWUsImF1dG9SZWNvdmVyRXJyb3IiOnRydWUsInN0b3BPblN0YWxsIjpmYWxzZSwiZHVtcGZNUDQiOmZhbHNlLCJsZXZlbENhcHBpbmciOi0xLCJsaW1pdE1ldHJpY3MiOi0xfQ==) - plays well;
```json
{
  "debug": true,
  "enableWorker": false,
  "lowLatencyMode": true,
  "backBufferLength": 0,
  "liveMaxLatencyDurationCount": 12,
  "liveSyncDurationCount": 6,
  "liveDurationInfinity": false,
  "maxBufferLength": 12
}
```

## Playback of segments with TS continuity check failure

HLS stream with recording of stopwatch

* [hls.js 1.5.20](https://5982f183.hls-js-dev.pages.dev/demo/?src=https%3A%2F%2Fmstyura.github.io%2Fhls-js-issues%2Fmpeg-ts-continuity-check-failure%2Fgithub.m3u8&demoConfig=eyJlbmFibGVTdHJlYW1pbmciOnRydWUsImF1dG9SZWNvdmVyRXJyb3IiOnRydWUsInN0b3BPblN0YWxsIjpmYWxzZSwiZHVtcGZNUDQiOmZhbHNlLCJsZXZlbENhcHBpbmciOi0xLCJsaW1pdE1ldHJpY3MiOi0xfQ==)
```json
{
  "debug": true,
  "enableWorker": false,
  "lowLatencyMode": true,
  "backBufferLength": 0,
  "liveMaxLatencyDurationCount": 12,
  "liveSyncDurationCount": 6,
  "liveDurationInfinity": false,
  "maxBufferLength": 12
}
```