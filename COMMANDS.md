Commands:
=========

X specifies a number  
Arguments between ( ) are optional


Manager+
--------

|Command | Arguments |  Description | Converted to Node |
|:------:|:---------:|:--------------------------------------:|
|!add | @user | add user to the waitlist | X |
|!afklimit | X | sets the maximum afk time | X |
|!afkremoval | | toggles the afk check | X |
|!autofav | | make !fav display on a timer | X |
|!autolotto | | make !lotto display on a timer | X |
|!autorcs | | make !rcs display on a timer | X |
|!autorules | | make !rules display on a timer | X |
|!autoskip | | skips songs automatically when they're done (use when the circles-bug happens) | X |
|!autotwitch | | make !twitchlive be displayed on a timer (use when TehSmileys is livestreaming) | X |
|!botname | (botname) | change the default bot name | X |
|!bouncer+ | | disable/enable bouncer+ | X |
|!clearchat | |clears the chat | X |
|!cycle | | toggle DJ cycle | X |
|!cycletimer | X | set the maximum DJ cycle time for when cycleguard is enabled | X |
|!deletechat | @user | delete all the chats by a certain user | X |
|!language | (language) | specify the language you would like the bot to use | X |
|!lock | | lock the waitlist | X |
|!lockdown | | lock down the room: only staff can chat | X |
|!locktimer | X | set the maximum time the waitlist can be locked if lockguard is enabled | X |
|!logout | | logs out account bot is hosted on | X |
|!lotto | | start the Lotto | X |
|!maxlength | X | specify the maximum length a song can be when timeguard is enabled | X |
|!move | @user (X) | moves user to position X on the waitlist, default is position 1 | X |
|!refresh | | refreshes the browser of whoever runs the bot | X |
|!remove | @user | remove user from the waitlist | X |
|!songstats | | toggle song statistics | X |
|!unlock | | unlock the waitlist | X |
|!usercmdcd | X | set the cooldown on commands by grey users | X |
|!usercommands | | toggle user commands | X |
|!voteskip | (X) | when no argument is specified, returns the current voteskip limit, when X is specified, voteskip limit is updated to the new specified limit | X |
|!welcome | | toggle the welcome message on user join | X |

Bouncer
-------

|Command | Arguments |  Description | Converted to Node |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default | X |
|!afkreset | @user | resets the afk time of user | X |
|!afktime | @user | shows how long user has been afk | X |
|!autodisable | | toggle the autodisable | X |
|!autos | | displays the status of automated messages | X |
|!ban | @user | bans user for 1 day | X |
|!blacklist / !bl | blacklistname | add the song to the specified blacklist | X |
|!blinfo | | get information required to blacklist a song | X |
|!cycleguard | | toggles the cycleguard | X |
|!dclookup / !dc | (@user) | do dclookup for user | X |
|!english | @user | ask user to speak english (asked in the language they set plug to) | X |
|!eta | (@user) | shows when user will reach the booth | X |
|!filter | | toggles the chat filter | X |
|!forceskip | | forceskips the current song | X |
|!jointime | @user | shows how long the user has been in the room | X |
|!kick | (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds) | X |
|!kill | | shut down the bot | X |
|!lockguard | | toggle the lockguard | X |
|!skip | (reason) | skips, locks and moves the dj back up (the position can be set with !skippos) | X |
|!motd | (X)/(message) | when no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message | X |
|!mute | @user (X) | mute user, for X minutes if X is specified, otherwise for an undefined period | X |
|!reload | | reload the bot | X |
|!restricteta | | toggles the restriction on eta: grey users can use it once an hour | X |
|!sessionstats | | display stats for the current session | X |
|!skip | (reason) | skips the dj using smartskip. actions such as locking and moving user depends on various factors (the position the dj is moved to can be set with !skippos) | X |
|!skippos | X | set the position to which skip and lockskip moves the dj | X |
|!status | | display the bot's status and some settings | X |
|!timeguard | | toggle the timeguard | X |
|!togglebl | | toggle the blacklist | X |
|!togglemotd | | toggle the motd | X |
|!togglevoteskip | | toggle the voteskip | X |
|!unban | @user | unban user | X |
|!unmute | | unmute user | X |
|!uptime | | displays the bot uptime | X |
|!voteratio | @user | display the vote statistic for a user | X |
|!whois | @user | returns plug related information about user | X |

Resident DJ
-----------

|Command | Arguments |  Description | Converted to Node |
|:------:|:---------:|:--------------------------------------:|
|!link | | give a link to the current song | X |



User
----

|Command | Arguments |  Description | Converted to Node |
|:------:|:---------:|:--------------------------------------:|
|!8ball | (message) | ask the bot a question, the bot will return random variations of a yes or no answer | X |
|!abuse | | explains how to use the !dc command properly, rather than abusing it | X |
|!acronym | | 6 random letters will be made, try to make an acronym out of them | X |
|!autowoot | | links to RCS, the advised script/plugin to use for autowooting | ✓ |
|!ba | | explains the Brand Ambassador rank | ✓ |
|!candy | (@user) | give a random candy to a user | X |
|!commands | | gives a link to the commands | ✓ |
|!cookie | (@user) | give a cookie to someone | X |
|!cycleinfo | | explains what the djcycle setting does | X |
|!dcinfo | | information about the dc command | X |
|!dclookup / !dc | | use dclookup on yourself | X |
|!discord | | links to our discord room where you can come and talk to us | X |
|!emoji | | a link to a list with emoji's | X |
|!eta | | shows how long before you reach the booth | X |
|!fav | | remind people to favorite the room | X |
|!fb | | links to the room's Facebook page (not set in settings) | X |
|!flip | | flips a coin | X |
|!fortune | | get or give a fortune from the fortune teller | X |
|!ghostbuster | @user | checks if user is ghosting | X |
|!gif | (message) | returns a gif (from giphy) related to the tag provided, Returns a random gif if no tags are provided | X |
|!git | | returns a link to the bot's repository | X |
|!guidelines | | sends the list for what is expected of a staff member in this community | X |
|!join | | join the Lotto if it's up | X |
|!leave | | leave the Lotto if you joined | X |
|!link | | when the user is the DJ, give a link to the current song | X |
|!lottoinfo | | explains the Lotto to people who don't know what it is | X |
|!op | | links to the OverPlayed list | X |
|!ping | | pong! | ✓ |
|!props | | give a song "props" made to show appreciation to a good song | X |
|!rcs | | provides information for the RCS Extension | X |
|!ref | | the "I.T" support command for plug.dj | X |
|!roll | | rolls the dice | X |
|!rps | [Choice] | play rock, paper, scissors, lizard, spock | X |
|!rules | | links to the rules | X |
|!shots | (@user) | give someone a shot | X |
|!staff | | small things that will improve your chances of getting staff in our community | X |
|!theme | | links to the room's theme | X |
|!twitch | | TehSmileys twitch link | X |
|!twitchlive | | TehSmileys twitch link when she is live | X |
|!version | | Returns the bot's current version | ✓ |
|!weed | (@user) | give someone weed | X |
|!website | | links to the room's website (not set in settings) | X |
|!subinfo | | explain what the plug.dj subscription service means | X |
|!youtube | | links to TehSmileys youtube page | X |


All Sub-Commands
-----------------

|MainCommand | Sub-Command | Description |
|:------:|:---------:|:--------------------------------------:|
|!skip | history | if the song is in the "DJ history" |
|^ bouncer+|nsfw | if the song played contained an NSFW image or sound |
||sound | if the song played had horrible sound quality or no sound |
||theme | if the song doesn't fit the room theme  |
||unavailable | if the song is not available for some, most or all users |

Coming Soon... Hop3fully
-------------------------

|Command | Description | Estimated Time |
|:------:|:---------:|:---------------:|:-----------------------:|
|!catfact | | returns a random cat fact |
|!gamble | amt | gambling game |
|!poll | | starts a poll for users to vote on |
|!urban | | urban dictionary integration |
|!streamalert | | automatically alert when streamer goes live |
|idk|why not suggest something!||
