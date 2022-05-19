<h1 align="center"> ustvgo_to_m3u </h1>

Grabs m3u links from ustv247.tv All I am doing is substituting ustv247.tv as the source. Unfortunately the same channels seem to be blocked to non Nord VPN users. Still it seems to work. I use it in case ustvgo.tv changes. The EPG no longer works. May 19 2022


**NEW UPDATE: If you hate setting up cron jobs, just execute `server.py` (based on Flask, yes it's a webserver) and leave it running.**

### Steps to run `server.py`:
> Have flask installed: `pip install flask`

> Edit the script to add your server device's IP (change the port too, if you wish)

> Assuming port 9000, if your server device's IP is 10.10.10.10, playlist url would be: http://10.10.10.10:9000/ustvgo.m3u

### Usage (The raw script, requires you to set up a cron job every 4 hours)

``` bash
git clone https://github.com/benmoose39/ustvgo_to_m3u.git
cd ustvgo_to_m3u
```
##### To run manually:
```
chmod +x autorun.sh
./autorun.sh
```

##### To run automatically every 3 hours:
```
python3 autoCRON.py
```
![image](https://user-images.githubusercontent.com/29022864/125736630-9f94ed91-ea07-459d-b955-a9dc40f8d50f.png)



### Connect with the community

If you need help setting up the script, connect: https://discord.gg/dmgYmAEdee


### Support

🙂 https://www.buymeacoffee.com/benmoose39
