# AutoLink IoT

This solution enables fast and secure integration of IoT devices into a network without the need for IT professionals. The IT department can establish the basic network infrastructure, while the setup, modification, and replacement of IoT devices can be performed by non-IT personnel such as family members, warehouse workers, technicians, and other operational staff. Furthermore, the IoT devices can be identified in a human-understandable format. This user-friendly solution simplifies the process of integrating IoT devices into a network.


This solution can support various types of IoT devices such as smart plugs for home automation and private IoT, devices for Industry 4.0, smartphones, network devices such as Wi-Fi cameras, and many others.

Network parameters are set through an online portal. These may include IP addresses or location, network access/Wi-Fi credentials, signal bus (MQTT broker), software version, etc. These are then transferred to at least one IoT device, which can be conveniently done through the browser and via a cable connection or Bluetooth. This is the state of the art for well-designed and new IoT devices.

Every new IoT device that wants to onboard itself will connect via Bluetooth to an already registered device. This new approach has not been applied before, but it can be implemented technologically directly.

The simple onboarding can then take place via an online portal or buttons on the IoT devices. IT personnel is no longer necessary. Assuming that at least one more IoT device is within range, onboarding is possible anywhere. If this is not the case, the configuration can be "distributed" with a portable device such as a smartphone or already configured IoT device.

Each IoT device has a unique, human-readable name, such as cunning_orca or button_taste_red, which can be read on the device, in the web interface, in a QR code, etc.

A geographical map of IoT devices in the physical world can be created using the next neighbor. Areas without their own network infrastructure can be opened up via their own mesh connection.

Misconfigurations can also be easily signaled on the device (LED, display, etc.), making it possible to start onboarding selectively. The distributed infrastructure can be used for additional services.

Bluetooth devices can be directly connected to the structure without additional hardware. Hand scanners, carts, BLE sensors, etc., could thus provide data to an overarching software infrastructure via the IoT nodes. Further gateways are not necessary. Some technologies are already directly available, such as https://esphome.github.io/bluetooth-proxies/
