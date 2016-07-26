# face-tracker
web component to check if there is a face detected by the camera. Wrapper of js-objectdetect

It takes a videoElement as input and returns a boolean value depending on if a face has been detected

You can use the debouncesecs property to avoid false positives
```html

<video-camera videoelement="{{video}}"></video-camera>
<face-tracker video="{{video}}" detected="{{detect}}" debouncesecs="2"></face-tracker>
<br>
Detected: {{detect}}

```

You can see it working here: https://fernandezpaco.github.io/face-tracker/index.html
