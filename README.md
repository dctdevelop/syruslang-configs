# syruslang-configs
Official Syruslang Configuration scripts and snippets for Syrus 4 devices, also known as SyrusJS configuration files.

The app directory folder structure of SyrusJS is as follow:

```
data-folder/
├── appends.syrus.conf
├── configuration.syrus.conf
├── geofences.syrus.conf
└── destinations.syrus.conf
```

* `appends.syrus.conf` auto generated file that includes any command/definition sent to the Syrus remotely.
* `configuation.syrus.conf` user defined file which contains the main configuration of the device.
* `geofences.syrus.conf` is an optional file that has the geofence definitions for the main configuration file.
* `destinations.syrus.conf` has the destination definition of the data.

Head to the Syrus 4 documentation - [Programming your Syrus 4](https://syrus.digitalcomtech.com/syrdocs/syrus4/getting-started/#programming-syruslang) for information on how to load these configurations.