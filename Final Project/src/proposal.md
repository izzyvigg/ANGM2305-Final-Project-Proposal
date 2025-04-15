# Custom Color Palette Generator from Images

## Repository
https://github.com/izzyvigg/ANGM2305-Final-Project-Proposal.git

## Description
This project will allow user's to paste images and color-pick pixels to create their own color palettes. Current tools that are
similar limit users' customization - to solve this issue, this project will grant further freedom in the number of images one can 
eyedrop from, the number of color swatches, and allow users to make several color palettes side-by-side for comparison. 

## Features
- pasting and displaying multiple images
	- images will be pasted from clipboard and stored in a list so they can all be displayed onto the same workspace
- color picker tool (aka eyedropper)
	- the program will track the user's cursor and on click, get the RGB value of the selected pixel
- side-by-side palette comparison 
	- using rectangles to display the palettes on the side of the workspace window
- custom color swatch amount
    - there will be a standard number, and users can click a "-" or "+" to add or delete a swatch space (with a set maximum)
- exporting results as jpgs or pngs
    - the program will save the render palettes under a different window that gets saved out as jpgs or pngs when the user wants to export (?)

## Challenges
- how to zoom in on a specific part of an image when a user's cursor hovers over it.
- UI design that is easy to understand and appealing for users.
- since I want multiple palettes, I need to make sure only one palette is active at a time while the user is color picking 
  (and make it obvious which is active to prevent confusion).

## Outcomes
Ideal Outcome:
- The ideal outcome would be a fully functional program with all features enabled without bugs.

Minimal Viable Outcome:
- The bare essentials for a good outcome would be at least the multiple images, eyedropper tool, one color palette, and one export option all working.

## Milestones

- Week 1
  1. create visual mockup
  2. add paste image(s) functionality 

- Week 2
  1. color picker tool (eyedropper) works
  2. palette system basics (add, delete, swatches & drop in colors)

- Week 3
  1. zoom when hovering over image
  2. palette system cont. (swatch reordering, add more palettes & select active)

- Week 4 (Final)
  1. export functionality
  2. UI layout
  3. clean up & final polish