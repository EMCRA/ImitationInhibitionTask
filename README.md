# Online Verion of the Imitation-Inhibition Task

## Description

JsPsych code to run the imitation-inhibition task online. Supports key releases as support and checks whether keys are held down.

## Custom Code and Plugins

- jspsych.js: Added function <i>core.finishTrialWithoutData</i> to jspsych source code. Necessary for <i>jspsych-check-response</i> plugin.
- jspsych-check-response: Simple plugin that presents some text for a specified duration but does not save date (to prevent overload).
- jspsych-image-keyboard-release: Plugin that presents an image and records key releases instead of key presses.
- jspsych-fixation-image-keyboard-release: Plugin that presents two successive images without a flicker in between the images. Records key releases instead of key presses.

## Contact

emiel.cracco@ugent.be
