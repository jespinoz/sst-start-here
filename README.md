# Node.js pre-hackathon training @ SST

## Training outline

| Topic  | Time | Trainer |
| ------------- | ------------- |------|
| Koding setup  | 9:30 - 10:00  | Lita
| Javascript primer  | 10:00 - 11:00  | Deepank |
| Node.js primer | 11:00 - 12:00 | Quhan |
| Lunch | 12:00 - 1:00 | |
| Bluemix setup | 1:00 - 1:30 | Quhan |
| Express web app development | 1:30 - 3:00 | Aeshan |

## Note
Due to the restrictions on the SST WiFi network, only port 80 is available for access. This is especially important when running web apps via Koding.

A workaround would be to disable Apache on Koding (running on the default port 80) using this command in your Terminal window:
```
sudo service apache2 stop
```

Please also ensure that your Node web apps are listening on port 80. To run your app on Koding, please use `sudo` as well. For example:
```
sudo node index.js
```
