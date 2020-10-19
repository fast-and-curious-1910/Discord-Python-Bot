## Discord Python Bot
## Requirementes
- Python 3.6 Or Higher
- PRAW Module


```bash
pip install praw
```



## Preperations

### Reddit Side
Create and app at https://reddit.com/prefs/apps

Enter some stuff like this:

Name : (Anything)
<br>
Type : Script
<br>
Description : (Anything)
<br>
About : http://localhost:8080
<br>
Redirect URI : http://localhost:8080

Now you have done that go to the Python Script and edit:
<br>
client_id = "(THE ID SPECIFIED UNDER YOUR APP NAME IN reddit.com/prefs/apps)"
<br>
like this:
```
client_id="SI8pN3DSbt0zor"
```
now fill the secret
<br>
client_secret="(Go To Edit App , Then In The Description , there will be secret. Copy and Paste it here)"
<br>
like this:
```
client_secret= "xaxkj7HNh8kwg8e5t4m6KvSrbTI"
```
now fill password of your reddit account like:
```
password="1guiwevlfo00esyy"
```
fill your user_agent like this if appname is testscript and username is fakebot3:
```
user_agent="testscript by u/fakebot3
```
fill your reddit username like:
```
username="fakebot3"
```
all of this will look like:
```
client_id="SI8pN3DSbt0zor"
client_secret="xaxkj7HNh8kwg8e5t4m6KvSrbTI"
password="1guiwevlfo00esyy"
user_agent="testscript by u/fakebot3"
username="fakebot3"

```
with this info replace [this](https://github.com/fast-and-curious-1910/Discord-Python-Bot/blob/44875f6a1adc4ef3fdb487484e5f29db1f10b024/config.py#L19-L23) with this :point_up: info



### Discord Side

For this you need Admin privilages
<br>
Go to:
<br>
Server Settings < Integrations < Webhooks < New Webhook

Enter Your details like:
<br>
<br>
<img src=https://i.imgur.com/o3Bo9Ea.png width=500 height=200>

Customise As Per You then , Click "Copy Webhook URL" 
<br>
then go [here](https://github.com/fast-and-curious-1910/Discord-Python-Bot/blob/44875f6a1adc4ef3fdb487484e5f29db1f10b024/config.py#L5) and enter your webhook URL


#### Rembember Web Hooks Can Only Acess A Single Channel!

