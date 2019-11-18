This repo demonstrates an apparent bug in firefox extensions where HTML5 video controls don't always display.

You can run the demo like so (assuming you have npm installed)

```bash
npm install -g web-ext
web-ext run
```

The bug-demo.mp4 demonstrates the bug in practice. You can see that the controls don't display about half the time. Also, you can see that even when the controls don't display the "Hide Controls" option is available and the video can be played as if the video did have controls on.