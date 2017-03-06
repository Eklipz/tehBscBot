Commands:
=========

X specifies a number  
Arguments between ( ) are optional

✘ - Not yet
✓ - Done

Manager+
--------

|Command | Arguments |  Description | Converted to Node |
|:------:|:---------:|:--------------------------------------:|:---:|
|!add | @user | add user to the waitlist | ✘ |
|!afklimit | X | sets the maximum afk time | ✘ |
|!afkremoval | | toggles the afk check | ✘ |
|!autofav | | make !fav display on a timer | ✘ |
|!autolotto | | make !lotto display on a timer | ✘ |
|!autorcs | | make !rcs display on a timer | ✘ |
|!autorules | | make !rules display on a timer | ✘ |
|!autoskip | | skips songs automatically when they're done (use when the circles-bug happens) | ✘ |
|!autotwitch | | make !twitchlive be displayed on a timer (use when TehSmileys is livestreaming) | ✘ |
|!botname | (botname) | change the default bot name | ✘ |
|!bouncer+ | | disable/enable bouncer+ | ✘ |
|!clearchat | |clears the chat | ✘ |
|!cycle | | toggle DJ cycle | ✘ |
|!cycletimer | X | set the maximum DJ cycle time for when cycleguard is enabled | ✘ |
|!deletechat | @user | delete all the chats by a certain user | ✘ |
|!language | (language) | specify the language you would like the bot to use | ✘ |
|!lock | | lock the waitlist | ✘ |
|!lockdown | | lock down the room: only staff can chat | ✘ |
|!locktimer | X | set the maximum time the waitlist can be locked if lockguard is enabled | ✘ |
|!logout | | logs out account bot is hosted on | ✘ |
|!lotto | | start the Lotto | ✘ |
|!maxlength | X | specify the maximum length a song can be when timeguard is enabled | ✘ |
|!move | @user (X) | moves user to position X on the waitlist, default is position 1 | ✘ |
|!refresh | | refreshes the browser of whoever runs the bot | ✘ |
|!remove | @user | remove user from the waitlist | ✘ |
|!songstats | | toggle song statistics | ✘ |
|!unlock | | unlock the waitlist | ✘ |
|!usercmdcd | X | set the cooldown on commands by grey users | ✘ |
|!usercommands | | toggle user commands | ✘ |
|!voteskip | (X) | when no argument is specified, returns the current voteskip limit, when X is specified, voteskip limit is updated to the new specified limit | ✘ |
|!welcome | | toggle the welcome message on user join | ✓ |

Bouncer
-------

|Command | Arguments |  Description | Converted to Node |
|:------:|:---------:|:--------------------------------------:|:---:|
|!active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default | ✘ |
|!afkreset | @user | resets the afk time of user | ✘ |
|!afktime | @user | shows how long user has been afk | ✘ |
|!autodisable | | toggle the autodisable | ✘ |
|!autos | | displays the status of automated messages | ✘ |
|!ban | @user | bans user for 1 day | ✘ |
|!blacklist / !bl | blacklistname | add the song to the specified blacklist | ✘ |
|!blinfo | | get information required to blacklist a song | ✘ |
|!cycleguard | | toggles the cycleguard | ✘ |
|!dclookup / !dc | (@user) | do dclookup for user | ✘ |
|!english | @user | ask user to speak english (asked in the language they set plug to) | ✘ |
|!eta | (@user) | shows when user will reach the booth | ✘ |
|!filter | | toggles the chat filter | ✘ |
|!forceskip | | forceskips the current song | ✘ |
|!jointime | @user | shows how long the user has been in the room | ✘ |
|!kick | (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds) | ✘ |
|!kill | | shut down the bot | ✘ |
|!lockguard | | toggle the lockguard | ✘ |
|!skip | (reason) | skips, locks and moves the dj back up (the position can be set with !skippos) | ✘ |
|!motd | (X)/(message) | when no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message | ✘ |
|!mute | @user (X) | mute user, for X minutes if X is specified, otherwise for an undefined period | ✘ |
|!reload | | reload the bot | ✘ |
|!restricteta | | toggles the restriction on eta: grey users can use it once an hour | ✘ |
|!sessionstats | | display stats for the current session | ✘ |
|!skip | (reason) | skips the dj using smartskip. actions such as locking and moving user depends on various factors (the position the dj is moved to can be set with !skippos) | ✘ |
|!skippos | X | set the position to which skip and lockskip moves the dj | ✘ |
|!status | | display the bot's status and some settings | ✘ |
|!timeguard | | toggle the timeguard | ✘ |
|!togglebl | | toggle the blacklist | ✘ |
|!togglemotd | | toggle the motd | ✘ |
|!togglevoteskip | | toggle the voteskip | ✘ |
|!unban | @user | unban user | ✘ |
|!unmute | | unmute user | ✘ |
|!uptime | | displays the bot uptime | ✘ |
|!voteratio | @user | display the vote statistic for a user | ✘ |
|!whois | @user | returns plug related information about user | ✘ |

Resident DJ
-----------

|Command | Arguments |  Description | Converted to Node |
|:------:|:---------:|:--------------------------------------:|:---:|
|!link | | give a link to the current song | ✘ |



User
----

|Command | Arguments |  Description | Converted to Node |
|:------:|:---------:|:--------------------------------------:|:---:|
|!8ball | (message) | ask the bot a question, the bot will return random variations of a yes or no answer | ✘ |
|!abuse | | explains how to use the !dc command properly, rather than abusing it | ✘ |
|!acronym | | 6 random letters will be made, try to make an acronym out of them | ✘ |
|!autowoot | | links to RCS, the advised script/plugin to use for autowooting | ✓ |
|!ba | | explains the Brand Ambassador rank | ✓ |
|!candy | (@user) | give a random candy to a user | ✘ |
|!commands | | gives a link to the commands | ✓ |
|!cookie | (@user) | give a cookie to someone | ✘ |
|!cycleinfo | | explains what the djcycle setting does | ✘ |
|!dcinfo | | information about the dc command | ✘ |
|!dclookup / !dc | | use dclookup on yourself | ✘ |
|!discord | | links to our discord room where you can come and talk to us | ✘ |
|!emoji | | a link to a list with emoji's | ✘ |
|!eta | | shows how long before you reach the booth | ✘ |
|!fav | | remind people to favorite the room | ✘ |
|!fb | | links to the room's Facebook page (not set in settings) | ✘ |
|!flip | | flips a coin | ✘ |
|!fortune | | get or give a fortune from the fortune teller | ✘ |
|!ghostbuster | @user | checks if user is ghosting | ✘ |
|!gif | (message) | returns a gif (from giphy) related to the tag provided, Returns a random gif if no tags are provided | ✘ |
|!git | | returns a link to the bot's repository | ✘ |
|!guidelines | | sends the list for what is expected of a staff member in this community | ✘ |
|!join | | join the Lotto if it's up | ✘ |
|!leave | | leave the Lotto if you joined | ✘ |
|!link | | when the user is the DJ, give a link to the current song | ✘ |
|!lottoinfo | | explains the Lotto to people who don't know what it is | ✘ |
|!op | | links to the OverPlayed list | ✘ |
|!ping | | pong! | ✓ |
|!props | | give a song "props" made to show appreciation to a good song | ✘ |
|!rcs | | provides information for the RCS Extension | ✘ |
|!ref | | the "I.T" support command for plug.dj | ✘ |
|!roll | | rolls the dice | ✘ |
|!rps | [Choice] | play rock, paper, scissors, lizard, spock | ✘ |
|!rules | | links to the rules | ✘ |
|!shots | (@user) | give someone a shot | ✘ |
|!staff | | small things that will improve your chances of getting staff in our community | ✘ |
|!theme | | links to the room's theme | ✘ |
|!twitch | | TehSmileys twitch link | ✘ |
|!twitchlive | | TehSmileys twitch link when she is live | ✘ |
|!version | | Returns the bot's current version | ✓ |
|!weed | (@user) | give someone weed | ✘ |
|!website | | links to the room's website (not set in settings) | ✘ |
|!subinfo | | explain what the plug.dj subscription service means | ✘ |
|!youtube | | links to TehSmileys youtube page | ✘ |


All Sub-Commands
-----------------

|MainCommand | Sub-Command | Description | Converted to Node |
|:------:|:---------:|:--------------------------------------:|:---:|
|!skip | history | if the song is in the "DJ history" | ✘ |
|^ bouncer+|nsfw | if the song played contained an NSFW image or sound | ✘ |
||sound | if the song played had horrible sound quality or no sound | ✘ |
||theme | if the song doesn't fit the room theme  | ✘ |
||unavailable | if the song is not available for some, most or all users | ✘ |

Coming Soon... Hop3fully
-------------------------

|Command | Description | Converted to Node |
|:------:|:---------:|:-----------------------:|:---:|
|!catfact | returns a random cat fact | ✘ |
|!gamble | gambling game | ✘ |
|!poll | starts a poll for users to vote on | ✘ |
|!urban | urban dictionary integration | ✘ |
|!streamalert | automatically alert when streamer goes live | ✘ |
|idk|why not suggest something!| |
