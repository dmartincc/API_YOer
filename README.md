NFL
===

This repo is to demonstrate what can be very easily done with the [Yo API].

To send a Yo to all 49ers subscribers whenever a game starts we run this script with a cron job every minute.  
The script checks if a game starts and if so, sends a Yo using the [Yo API].  

To get your own API token [contact us].

##### Running

    git clone git@github.com:YoApp/NFL.git
    cd NFL
    virtualenv env
    . env/bin/activate
    pip install -r requirements.txt
    ./yo-49ers.py
    

License
----

MIT

[Yo API]:http://bit.ly/yoapi
[contact us]:mailto:api@justyo.co
