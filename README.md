# Vulgar Conlang Fancy PDF Template
A template making the TeX/PDF output from Vulgar Conlang generator a little prettier

There are a couple of things you'll need to know to get the most out of this LaTeX template.  
First, and possibly the most important point, this template was developed and meant for use via Overleaf.  It can be uploaded to Overleaf and then copied for use with your Vulgar Conlang projects in place of the one they shared.

Second, if you have any problems with the layout, make sure that you've selected XeLaTeX as the compiler and 2020 for the TeX Live Version.  Having the wrong settings here will completely mangle the fancy cover page.

Third, you need to add some things to the output from Vulgar Conlang to include the additional chapters\sections:
<br><b>To add the fancy front cover:</b>  \input{Cover}  NOTE: This must come before the Title page!
<br><b>Automatically added to Vulgar Conlang TeX output:</b>  \input{Title} NOTE: This MUST be included for the rest of the file to generate correctly!
<br><b>To include a Grammar section:</b>  \input{Grammar}
<br><b>To include a Common Phrases section:</b>   \input{Phrases}

Fourth, all the colors are defined in the Preamble.tex and can be updated there.  Hopefully, the labels will make it clear which colors will change which sections of the final PDF.


I was inspired to make a "prettier" by my large collection of phrasebooks directed at tourists, in particular the Lonely Planet series of phrasebooks.  I tend to make artifacts that I can imagine being used in fictional worlds, especially a conlang that might be spoken in a fictional country or world.  As I work with the output, I'll add more styling and some of my "to do" list will show the ideas I have there.  
