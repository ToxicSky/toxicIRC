toxicIRC
####

A small addon for Elder Scrolls Online with the purpose of changing your name when someone writes it in the chat.
This is to easier notify you when someone want your attention and is inspired by irc-clients such as irssi and mIRC.

It checks the text for the username and then loops through each character and compares all letters in the pattern found with the username.

TODO
####
Will add an external library, probably in C++, to handle the regex.
The current pattern, so far:
(\b(?i)[ToxicSky]{3})
The regex is not yet tested in the program, but rather on a website (myregextester.com).
Will also see about matching several patterns, comparing the entire username and then test various alternatives. Not everyone is bothered by using the full username in a mmorpg.