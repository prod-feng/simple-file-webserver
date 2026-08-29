# simple-file-webserver

Rocky Linux 9, Python 3. Onlypure HTML. Good for internal network small files quick share.

Run it as a regular user, mapping to higher port.

```
./run_me.sh start

./run_me.sh status

./run_me.sh stop
```

Once the service is started, then the files are directly available as:

```
http://YOUR-SERVER:8899/files/logo.png
http://YOUR-SERVER:8899/files/icon.png
```

Other websites can use them directly:

```
<img src="http://YOUR-SERVER:8899/files/logo.png">
```

<img width="493" height="198" alt="image" src="https://github.com/user-attachments/assets/0875f21c-0c10-4939-82ed-2a444166042b" />
