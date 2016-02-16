node-red-contrib-modbus
========================

A <a href="http://nodered.org" target="_new">Node-RED</a> node to communicate with [Modbus TCP](https://en.wikipedia.org/wiki/Modbus#Protocol_versions).

Install
-------

Run command on Node-RED installation directory

	npm install node-red-contrib-modbus

Pre-reqs
--------

Install first node-jsmodbus. NOTE: Modified files included here, but still some problems with function codes 15 and 16.
Tested with python modbus server (more testing needed for error handling etc.).

Usage
-----

![node-red-modbus-flow] (example.png)