### Flash multiple devices

```sh
esphome -s devicename livingroom -s upper_devicename Livingroom run --device 10.0.50.51 d1_bme280.yml
esphome -s devicename bedroom -s upper_devicename Bedroom run --device 10.0.50.54 d1_bme280.yml
esphome -s devicename hallway -s upper_devicename Hallway run --device 10.0.50.55 d1_bme280.yml
```
