# opx-sdi-api
This repository contains all declarations of the system device interface (SDI) API, and contains all public API declarations for the SDI API. The PAS component utilizes the SDI API to get/set data for platform devices such as fans, power supply units (PSU's), LED's, QSFP's, and so on.

The implementations of the API can be platform-specific and are stored in a separate repositories to facilitate reuse.

The `examples` directory provides a stub library implementation.  

## Build
See [opx-nas-manifest](https://github.com/open-switch/opx-nas-manifest) for more details on the common build tools. 

(c) 2017 Dell
