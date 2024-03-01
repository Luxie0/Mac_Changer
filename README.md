Tabii ki, işte İngilizce olarak README metni:

---

# MAC Changer

This Python program allows users to change the MAC addresses of their network interfaces. The MAC address can be randomly generated or a custom address can be specified. This can be used to enhance network privacy or to avoid being tracked on specific networks.

## Usage

Python 3 is required to run the program. Usage is straightforward:

```
python mac_changer.py --interface <interface_name> --mac <new_mac_address>
```

- `<interface_name>`: The name of the network interface whose MAC address you want to change (e.g., eth0, wlan0).
- `<new_mac_address>`: The new MAC address. "random" can be used for a randomly generated address.

For example:

```
python mac_changer.py --interface wlan0 --mac 00:11:22:33:44:55
```
---
