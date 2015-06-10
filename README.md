Politicians to Poop
=============

An extension for the Chrome browser that replaces the names of presidential candidates (US, 2016) with the pile-of-poo emoji (💩) in most web pages that you visit.

Options allow you to "poopify" the names of Democrats, Republicans, or both. (Any major third-party candidates that emerge will also be added to the list.) 



Installation
=============

Coming soon to the Chrome web store, as a free extension. 

Manual installation: 

[Direct download of crx file](https://github.com/evil-mad/politicians-to-poop/blob/master/pol-to-poo.crx?raw=true)

In Chrome, choose Window > Extensions. Drag pol-to-poo.crx into the page that appears.



What about FireFox, Safari, Opera?
=============

Sorry, not yet. Pull requests and/or pointers to versions for those browsers will be happily accepted.



What is the political agenda here? 
=============

This is a public service project from Evil Mad Scientist Laboratories. 

Possible reasons that you might want to use this extension might include:

* You are from outside the US, and don't need to hear these names every day.
* You are temporarily overloaded by the amount of poop that the candidates sling at one another.
* Because it is funny.


No judgement upon any of the named individuals, nor their platforms, parties, or beliefs is either implied or intended. This is an equal-opportunity text replacement tool, for the good of all humanity.


List of named participants
=============

The following individuals are currently identified as "major" political candidates, meeting the necessary criteria for inclusion in this list:

Republicans: Ted Cruz, Carly Fiorina, Ben Carson, Marco Rubio, Rick Santorum, Lindsey Graham, George Pataki, Rand Paul, Mike Huckabee, Rick Perry, and Jeb Bush.

Democrats: Hillary Clinton, Bernie Sanders, Lincoln Chafee, and Martin O'Malley.

Third-party and independent candidates: Roseanne Barr, Zoltan Istvan, Waka Flocka Flame, and Vermin Supreme. (While none of these yet seem "major" to our untrained eyes, it is good to have some names here as placeholders for future use.)



Known issues
=============

Text replacement does not reliably work in some circumstances:
* Text within images or other graphics
* Some pop-up windows and other cases of dynamically loaded content; we are trying to identify and fix these cases
* When a name is interrupted by HTML tags or style changes, for example if the last name is in bold font, but the first name is not.

Text replacement may also work *too well* in some circumstances:
* Text may be inappropriately replaced in text input boxes, for example if you type one of the candidate names.
* The filter may be a little too aggressive in some cases. For example, "Carly" or "Hillary" on their own may match many other names besides those of the actual candidates. In the options, you may wish to keep the "Include short but common abbreviated name forms..." checkbox disabled, in order to reduce the number of "false positives."

If you identify other circumstances where text replacement does not work reliably (or generates too many false positives), please submit an issue on our github project to let us know.





Attribution
=============

A project by Evil Mad Scientist Laboratories: http://www.evilmadscientist.com


Initially Forked from: https://github.com/panicsteve/cloud-to-butt

Inspired by: https://github.com/ericwbailey/millennials-to-snake-people

Further inspired by: This year's crop of presidential candidates

Using: http://benalman.com/projects/jquery-replacetext-plugin/

Special thanks to our dedicated team of beta testers!