+++ 

title = R profile tip
author = Erik
date = '2019-08-21' 
math = true 
summary  = "If your r profile is not being sourced properly, try this" share = false

[header] image = "" caption = "This is the caption, this is a much longer one though with some italics and Bolds."

This is a hidden page, testing out. This is a comment https://www.markdownguide.org/extended-syntax use this resource https://sourcethemes.com/academic/docs/writing-markdown-latex/ AND THIS RESOURCE

+++ 

Post in progress:

If you're having trouble with your rprofile, it might be because you don't have a trailing newline.

The last line of the profile is ignored, so you'll want to have some dummy line in there so that the previous ones are recognized.

I wanted to set my r profile to use my anaconda distribution of python, so I had put both lines in.

/end
