# buildComplete
Push notification from xcode on build complete using Pushbullet

Usage:
In xcode, go to preferences -> Behaviors. Under Build-> Start, add build_time_start.sh to Run, Under Build -> Succeeds add end_time_script.sh to Run.

Download the PushBullet app(https://www.pushbullet.com/apps), create account, under my account on the website create access token.
Paste the access token in the end_time_script placeholder and you're set.
