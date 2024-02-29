# Subathon Goal Meter
A simple goal meter for the RAMY Subathon livestream event! Designed and built by theRamoShe as a highly customized version of the CodePen created by [Tommy Creenan](https://codepen.io/TommyCreenan/pen/naxVYV)

## Usage
It was designed for two girls streaming together, getting a little naughty, but it can easily be repurposed with a bit of code editing. Could be used by anyone who wants a manually run meter because they are accepting donations on multiple platforms.

Simply add donations by clicking the button, or entering a custom number of subs ad pressing the "Add Donation" button (or pressing your keyboard "Return/Enter" button).

You can customize the meter for your own subathon with the instrictions below.

## Customization
You can edit the code yourself if you're comfortable with HTML and CSS, or if you'd like a custom version built for you, contact Rachel at https://theramoshe.com

The project consists of three simple files that need minimal adjustments to customize:

1. `index.html` - this is where you'll type in your sub goals in the `<div class="goals">` and rewards in the `<div class="rewards">`

2. `script.js` - the only thing you'll need to adjust here is the `const goal` at the top if your goal isn't 250 subs

3. `style.css` - this is where you might want to customize the most, but please be careful.
 - you can easily change the colors, there are basically 5 used—black, white, lightgray, gray, and hotpink—which can be substituted with other named colors or hex codes
 - **most important** if you adjust the goal from 250, you will need to adjust the `.goals span {margin-bottom: 1.18em}` on line 96. Change the calue and test using the buttons until the lines match up with your entered amounts.

 **Important Note:** With the overall goal set here at 250 Subs, the most changes will need to be made to the code if you're changing that ultimate goal.

## That's It!
Any questions, comments, or requests can be directed to https://theramoshe.com

Thank you!