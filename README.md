# Subathon Goal Meter
A goal meter for the RAMY Subathon livestream event! Designed and built by theRamoShe as a highly customized and feature-added version of the CodePen created by [Tommy Creenan](https://codepen.io/TommyCreenan/pen/naxVYV)

## Purpose
It was designed for [AmyBabyZ](https://kick.com/amybabyz) and [theRamoShe](https://kick.com/theramoshe) streaming together, getting a little naughty, but it can easily be repurposed with a bit of code editing for anyone who wants a manually run meter because they are accepting donations on multiple platforms, and/or splitting profits between multiple streamers.

## Usage
Simply add donations by selecting the streamer who recieved the sub, then clicking the appropriate button, or entering a custom number of subs and pressing the "Add Subs" button (or hitting your keyboard "Return/Enter" button).

The meter fills accordingly and counts the number of subs per streamer as you go. If you've forgotten to select a streamer first, you'll get an alert to remind you.

Be careful not to refresh the page, as this will reset all counts. The meter only works locally.

Capture the meter on your stream by using a window capture of your browser window and cropping out the form and everything on the right side.

## Customization
You can edit the code yourself if you're comfortable with HTML and CSS, or if you'd like a custom version built for you, contact Rachel at https://theramoshe.com

The project consists of three simple files that need minimal adjustments to customize:

1. `index.html` - change the goals and streamers
  - type in your sub goals for each level in the `<div class="goals">` (if you're changing the total goal from 250 subs, you'll have to add or remove goals as needed also)
  - put your rewards for 5, 10, and 20 subs in the `<div class="rewards">`
  - customize/add streamer names in the `<fieldset id="streamer-selector">` and the `<div id="streamer-counts">`.

2. `script.js` - the only thing you'll need to adjust here is the `const goal` at the top if your goal isn't 250 subs

3. `style.css` - this is where you might want to customize the most, but please be careful.
  - you can easily change the colors, there are basically 5 used—black, white, lightgray, gray, and hotpink—which can be substituted with other named colors or hex codes
  - **most important** if you adjust the goal from 250, you will need to adjust the `.goals span {margin-bottom: 1.18em}`. Change the value and test using the buttons until the lines match up with your entered amounts

 **Important Note:** With the overall goal set here at 250 Subs, the most changes will need to be made to the code if you're changing that ultimate goal.

# That's It!
Any questions, comments, or requests can be directed to https://theramoshe.com. If you're using this meter for your own subathon, I would definitely love to know about it!

Thank you!