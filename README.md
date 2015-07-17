[MouseHunt Autobot REVAMP](https://greasyfork.org/en/scripts/6092-mousehunt-autobot-revamp) and [ENHANCED + REVAMP](https://greasyfork.org/en/scripts/6514-mousehunt-autobot-enhanced-revamp)
=========

######Build for BETA UI is [NOW MOVED TO A/B build](https://greasyfork.org/en/scripts/6092-mousehunt-autobot-revamp)

~~[Original](http://userscripts-mirror.org/scripts/show/78731.html) version made and owned by [Ooi Keng Siang](http://ooiks.com/blog/mousehunt-autobot) \(He no longer develops this code\)~~

######Chrome version is now updated to 2.1.1c script - download it [here](https://github.com/nobodyrandom/mhAutobot/raw/master/chromeExtension.crx)

[REVAMP](https://greasyfork.org/en/scripts/6092-mousehunt-autobot-revamp) version adapts the original, with few bug fixes and etc \(ver a\)

[ENHANCED + REVAMP](https://greasyfork.org/en/scripts/6514-mousehunt-autobot-enhanced-revamp) version adapted from version made and owned by [CNN](https://devcnn.wordpress.com/) \(ver b\) \(Just a note, he was **banned** for making and using the ENHANCED version, so up to you if you dare use it\)

To install this version, please use [greasyFork](https://greasyfork.org/en/scripts/6092-mousehunt-autobot) or [OpenUserJS](https://openuserjs.org/scripts/nobodyrandom/MouseHunt_AutoBot_REVAMP)
Note: this version of the code includes two separate files which should automatically install itself. If features such as 'Send to GDoc' does not work, please install [the second file](https://greasyfork.org/en/scripts/6094-mousehunt-autobot-additional-thing) as well.

#####PRECAUTION: Use this script at your own risk as this is against the rule of Mousehunt.
*****
Report all bugs to [GitHub](https://github.com/nobodyrandom/mhAutobot/issues) or email me @ <iamnobodyrandom@yahoo.com>   
>	A sidenote ~ Since I am creating this version pretty actively, updates will come in from a 5 mins interval up to a weekly interval. Please make sure you update your install frequently   
>	Want to contribute to the code or have ideas? Email me \^.\^

Changelog - [GitHub](https://github.com/nobodyrandom/mhAutobot/commits/master)
*****
Features:
>*  Support for NEW beta UI
>*	Living Garden Spreadsheet -> [Google Drive](https://docs.google.com/spreadsheet/ccc?key=0Ag_KH_nuVUjbdGtldjJkWUJ4V1ZpUDVwd1FVM0RTM1E&usp=sharing) with run forecasting
>*	Area clocks via "Toggle Timers"
>*	Auto Kings Reward popup (check the settings)
>*	Auto return raffle tickets
>*  Cleaned code
>*  Removed not working sound player and replaced with a working HTML5 one
>*  Browser notif and tiggers are now fixed ^.^
>*	KR auto resume etc are now fixed
>*  No cheese notif
>*  BETA UI Support
>*  (ver b ONLY) Integrated CnN's bots for automization on areas + automization on G Express
>*	(TODO: write up a instruction manual for the GDoc, but it should be pretty self explanatory)

*****
Explanations of the files included
>   All main code is located in the tamperMonkey folder
>
>   The build in the chromeExtension folder is specifically used to package the core version (REVAMP only) as a chrome installable package, as chrome no longer allows direct installation of user scripts
>
>   Builds within tamperMonkey folder:
>*  MouseHunt AutoBot.user.js => Main core with no enhancements what so ever
>*  MouseHunt AutoBot blended.user.js => Build with CNN's enhancements to automize trap arming/ cheese change etc.
>*  parse-1.4.2.min.js => API file for server support side of the bot
>*  MouseHunt AutoBot Additional thing.user.js => Addon file to the core (No longer needed as of v2.0 and up)
>*  MouseHunt AutoBot beta.user.js => Main core with no enhancements for the MH BETA UI (Merged onto A/B build v2.1 and up)
>*  MouseHunt AutoBot Additional thing beta.user.js => Addon file to the beta core (Also no longer need as of v2.0 and up)

*****
#####Sorrry I am new to GitHub, GM and actually anything at all so if there's something wrong pls email me or submit a bug report asap so I can fix it
