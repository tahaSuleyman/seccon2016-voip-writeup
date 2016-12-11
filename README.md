# seccon2016-voip-writeup
SECCON 2016 VoIP Write Up

VoIP<br/>
Extract a voice.<br/>
The flag format is SECCON{[A-Z0-9]}.<br/>


First we open .cap file with Wireshark which is given in the question.<br/>

![alt tag](https://github.com/tahaSuleyman/seccon2016-voip-writeup/blob/master/voip1.png)


From <b>Telephony</b> menu we selected the <b>VoIP Calls</b> option.<br/>

![alt tag](https://github.com/tahaSuleyman/seccon2016-voip-writeup/blob/master/voip2.png)

In Wireshark popup we were able to play stream.<br/>


![alt tag](https://github.com/tahaSuleyman/seccon2016-voip-writeup/blob/master/voip3.png)

In stream the flag was given.<br/>

Flag : <b>SECCON{9001IVR}</b>
