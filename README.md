# HTML-EMAIL TEMPLATES
___
This repository will host a small collections of email templates as I try to learn more about HTML-based email development


## CHALLENGES WITH HTML EMAIL
___
HTML based Email are difficult to properly create as coding standards simply do not exist for it.
Different email clients can support whatever they desire and drop support for anything else they don't need.


###TABLES ARE BACK!
These lack of standards consequently means that modern HTML techniques such as div, section, article simply do not work as intended, or are not supported at all. Thus we're back to the old 90's days of nesting table with a couple additional restrictions such as colspan and rowspan being unsupported. 

Stacking td on top of each other to build respsonsive email is also not fully supported by every email client.


###CSS RESTRICTIONS
CSS follows a similar fate as most email clients forbids using <link> and/or requires all styles to be inlined within the element itself.
Luckily there are some email sending services which offers automatic conversion to inline CSS.

Some email clients also does not support media queries, so building responsive emails can be tricky.


###SPECIAL CASES
MS Outlook must be treated as a special case in the HTML file, so conditional codes are guarenteed to be used just to make MS Outlook render things the same way as any other email clients.
