rustaMsgBox
============================

Simple un-obtrusive popup message box

Call it like this (specifying the content to display):

$.rustaMsgBox({ "content" : "hi I'm the rusta message box" });

You can also provide the following overrides in addition to just the content to control how the nox behaves (defaults shown below):

closeButton: false,
fadeOut: true,
fadeTimer: 1500,            
content: 'Add some content here...',
zindex: 3022,
width: '70%',
maxWidth: '300px',
mode: 'info', /* warning, success, error, info */
bottom: '-90px',
opacity: 0.9


## The To Do List

- provide an option to have the fadeTimer length based on the character count of the message that is displayed
- update the 'delivered' styles to have that "flat" look we all love
- provide a mechanism to override the defaults centrally (rather than just when the function is called)