### AP

WiFi should be using 20 MHz bandwidth.

### Flash multiple devices

```sh
esphome -s devicename livingroom -s upper_devicename Livingroom run --device 10.0.50.81 d1_bme280.yml
esphome -s devicename bedroom -s upper_devicename Bedroom run --device 10.0.50.84 d1_bme280.yml
esphome -s devicename hallway -s upper_devicename Hallway run --device 10.0.50.85 d1_bme280.yml
```

### Secrets

`secrets.yaml`
```yml
---

wifi_ssid: ""
wifi_password: ""

```
