<!--docs:
title: "Material progress indicators"
layout: detail
section: components
excerpt: "Progress indicators express an unspecified wait time or display the length of a process."
iconId: 
path: /catalog/material-progress-indicators/
-->

# Progress indicators

[Progress indicators](https://material.io/components/progress-indicators) express an unspecified wait time or display the length of a process.


![Progress indicator hero](assets/hero-1.gif)

# Contents

* [Using progress indicators](#using-progress-indicators)
* [Installing progress indicators](#installing-progress-indicators)
* [Making progress indicators accessible](#making-progress-indicators-accessible)
* [Linear progress indicators](#linear-progress-indicators)
* [Circular progress indicators](#circular-progress-indicators)
* [API](#api)

## Using progress indicators

Progress indicators inform users about the status of ongoing processes, such as loading an app, submitting a form, or saving updates. They communicate an app’s state and indicate available actions, such as whether users can navigate away from the current screen.



_**Note: When displaying progress for a sequence of processes, indicate overall progress rather than the progress of each activity.**_

### Installing progress indicators

### Making progress indicators accessible

**Types**

Material Design offers two visually distinct types of progress indicators:  1. [linear](#linear-progress-indicators) 2. [circular](#circular-progress-indicators) progress indicators. Only one type should represent each kind of activity in an app. For example, if a refresh action displays a circular indicator on one screen, that same action shouldn’t use a linear indicator elsewhere in the app.

![Composite image of progress indicator types](assets/composite-1.gif)

## Linear progress indicators

Linear progress indicators display progress by animating an indicator along the length of a fixed, visible track. The behavior of the indicator is dependent on whether the progress of a process is known.


Linear progress indicators support both determinate and indeterminate operations.
* Determinate operations display the indicator increasing in width from 0 to 100% of the track, in sync with the process’s progress.
* Indeterminate operations display the indicator continually growing and shrinking along the track until the process is complete.

For more implementation information, see [linear progress indicator](https://github.com/material-components/material-components-web/tree/master/packages/mdc-linear-progress).

## Circular progress indicators

Circular progress indicators display progress by animating an indicator along an invisible circular track in a clockwise direction. They can be applied directly to a surface, such as a button or card.


Circular progress indicators support both determinate and indeterminate processes.
* Determinate circular indicators fill the invisible, circular track with color, as the indicator moves from 0 to 360 degrees.
* Indeterminate circular indicators grow and shrink in size while moving along the invisible track.

For more implementation information, see [circular progress indicator](https://github.com/material-components/material-components-web/tree/master/packages/mdc-circular-progress).

## API
