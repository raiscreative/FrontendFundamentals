Frontend Fundamentals Project #2 

This is an attempt to recreate Netflix homepage using only HTML and CSS. As expected, the result is not functional. But it does resemble the original to a certain extent.

What I had to do:

Background
I figured a Halloween themed background (even considered to change the primary-color to something orange-y/purple-ish, but it didn’t look as good as I expected) fits best for the moment.
I used box-shadow inset to get the inner shadow effect and z-index to send the shadow behind the text.

Logo
It was a little tricky (see what I did here?) to position. Used transform: translate to put it in its place (probably not exactly right but close).

Sign In button
This one needed just a bit of border-radius.
Both buttons have a cursor: pointer property so it looks like in the original, even though they don’t do anything.

The text
I used Poppins font and it looks a bit slimmer than the original.
There’s a h1 with a font-size: 4.2rem and a h2 with a font-size: 1.9rem

The input field and the submit button
I gave the field a size: ’60’ and resized the placeholder using
::-webkit-input-placeholder (1rem font-size looks a lot better than the default; however it doesn’t work on all browsers and I had to use the special syntax to fix that).
For the button I used a font-awesome icon
(<i class=”fas fa-chevron-right”></i>).
Having the html inline removed the gap between the input field and the submit button.

the footer
This is a list of links styled with grid.

Responsiveness
I added some @media rules to make it mobile friendly.


