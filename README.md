# Node.js pre-hackathon training @ SST

## Training outline
Please click the links below to view slides associated with the topics:

| Topic  | Time | Trainer |
| ------------- | ------------- |------|
| [Koding setup](http://www.slideshare.net/linovati/koding-setup)  | 9:30 - 10:00  | Lita
| [Javascript primer](http://www.slideshare.net/deepankvora/javascript-sst)  | 10:00 - 11:00  | Deepank |
| [Node.js primer](http://www.slideshare.net/quhan/nodejs-primer-48969602) | 11:00 - 12:00 | Quhan |
| Lunch | 12:00 - 1:00 | |
| [Bluemix setup](http://www.slideshare.net/quhan/bluemix-setup) | 1:00 - 1:30 | Quhan |
| [Express web app development](http://www.slideshare.net/AeshanWijetunge/sst-hackathon-express) | 1:30 - 3:00 | Aeshan |

## Note
Due to restrictions on the SST WiFi network, only port 80 is available for access on your browser. This is especially important when attempting to run your web apps via Koding.

A workaround would be to disable Apache on Koding (running on the default port 80) using this command in your Terminal window:
```
sudo service apache2 stop
```

Please also ensure that your Node web apps are listening on port 80 (e.g. `.listen(80)`). To run your app on Koding, please use `sudo` as well. For example:
```
sudo node index.js
```
You should then be able to view your web app on your browser using:
```
http://mykodingusername.koding.io
```
