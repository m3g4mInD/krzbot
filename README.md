# krzbot

Requirements:                              

you need bash, bc, and httpie ( https://httpie.org/ ).
you may need to modify the query in query().
You will need to setup webhooks in discord and then set those up at ther bottom of the script.
If you want a map you need to make an API key and fill it in at the top of the script.
Remember to remove the x from xhttps.
Install the database schema before you use it.
You can decide how and when to run it, i like to use crontab:
* * * * * /home/pi/krzbot/runbot.sh
after you edit runbot.sh and change the directory in the crontab line and runbot.sh script.
This would make it run every minute if it is not already running.
############################################################################
##############Happy hunting###############krzthehunter##########################
############################################################################

I take no responsibility for any harm caused by this script including but not limited to injured cats or nuclear hollocaust. Use it at your own risk. In fact you really should only use this if you understand it because you need to know a little bash to configure conditions for when to send to webhooks. This is released under a custom license im calling the NOSUPPORT license. Basically, do whatever you want with it, just dont ask me to support it! Sorry, I didn't figure out an easy way to abstract the config so normal non unix admin users could configure it. I just wrote it as a quick solution for myself, but I figured why not share with you guys too. Oh and FYI the bot will leak your mapquest key... the only way around that would be to download the image and then attach it to every post.
