# ROI Cutter

## GOAL
Take an image and create one or more cropped images. The roi is user-defined by drawing a rectangle with mouse events.

## INPUT
An image.

## OUTPUT
One or more cropped images stored in the *output* directory.

## CONTROLS
- Left mouse button down: select start point.
- Left mouse button up: select end point.
- Right mouse button down: confirm roi and create a roi.
- Middle mouse button down: close program.
- Roi images are saved in the *output* directory.

## HOW TO RUN:
Go to `"/ROI_Cutter/bin/Debug"` and run: `./ROI_Cutter -i=<path to input image>`
e.g. `./ROI_Cutter -i=../../../PCB_bestukker/img/pcb_2.png`
