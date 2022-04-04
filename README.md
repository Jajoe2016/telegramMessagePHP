# telegramMessagePHP
uses MadelineProto library to send message to any telegram user.
Full documentation and source is found at: https://github.com/danog/MadelineProto

how to run on terminal
php myphp.php

# First time setup - this one time setup should be completed before we start sending message.
If it is run first time it will open a prompt.
1) Do you want to enter the API id and the API hash manually or automatically? (m/a)
If you already have ApiId and ApiHash (to get one see this link https://github.com/Jajoe2016/telegramMessage), you can chose to manually enter them. Otherwise you can select automcatic which will setup one for you
2) For manual you need to enter the ApiID and ApiHash next

3)next is whether you want to login as bot or normal user - this does not matter. If you have bot you may need to enter ai key generated from botfather (again follow link https://github.com/Jajoe2016/telegramMessage to setup one) after which OTC will be sent to you. Alternatively, if you use normal username OTC will be sent to your telrgam user.

Once this login is succesul - the library will store session information locally so it can use it subsequently.

# Sending message

replace TELEGRAM_USER with the user you wanted the message delivered to.
replace 'message' => "Hi!\nThis is message from bot" with the content
run the script and it will send the message 

Note: cloning the source may give you more options (eg hardcoding the ApiID etc). 
It also contains examples beyond sending a simple message to one user. 
