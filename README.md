## Introduction

1. This tool is adapted from the Original Video Annotation Tool (please see the other repo) but without the video.js plugin, which saves more than 400 kb. 

2. The build and test setup can be found in the other repo

3. Please see `test/test.html` for how to initialize the tool. 

## TODO

1. **Custom control bar** --  In the original Video Annotation Tool (with video.js), the control bar has marker when a comment is made within certain time segments (please see `js/components/marker.js` and `draggable_marker.js`). Without the video.js plugin, we should customize our control bar and make it work with the two above mention javascript files (this wouldn't be too complicated as there are a lot of resource online documenting how to custom control bars for the default html video player). To disable the default control bar, delete the "controls" tag in the video element in `test.html`.

2. **Annotate button in control bar** -- Currently the Annotate button, which starts the tool, is located outside of the video. If we want to put it back into the custom control bar, please look into `js/components/player_button.js`.