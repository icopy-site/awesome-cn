<div class="github-widget" data-repo="naimo84/awesome-nodered"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Node-RED [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <a href="https://nodered.org/"><img src="https://nodered.org/about/resources/media/node-red-hexagon.png" width="200" align="right" alt="Node-RED"></a>

> Curated list of useful resources for Node-RED.

[Node-RED](https://nodered.org/) is a programming tool for wiring together hardware devices, APIs and online services in new and interesting ways.

It provides a browser-based editor that makes it easy to wire together flows using the wide range of nodes in the palette that can be deployed to its runtime in a single-click.



## Installation

- [Running locally](https://nodered.org/docs/getting-started/local)
- [Running under Docker](https://github.com/node-red/node-red-docker)
- [c't-Smart-Home](https://github.com/ct-Open-Source/ct-Smart-Home) - A ready-to-use setup for home automation maintained by [german computer magazine c't](https://www.ct.de/smarthome).
- [Home Assistant Community Add-on](https://community.home-assistant.io/t/home-assistant-community-add-on-node-red/55023) - Starts an instance within Home Assistant and communicates with it.
- [ioBroker node-red Adapter](https://github.com/ioBroker/ioBroker.node-red) - Starts an instance within ioBroker and communicates with it.
- [openHAB running on openHABian](https://www.openhab.org/docs/installation/openhabian.html#optional-components) - Install Node-RED using openhab-config from command line, choose it from "Optional Components".
- [RedMatic](https://github.com/rdmtc/RedMatic/wiki/Installation) - Install Node-RED on a CCU3, smart home automation hardware from the manufacturer eQ-3, popular especially in Germany.

## Documentation

- [Getting Started](https://nodered.org/docs/getting-started/)
- [FAQ](https://nodered.org/docs/faq/)
- [Tutorials](https://nodered.org/docs/tutorials/)
- [User Guide](https://nodered.org/docs/user-guide/)
## Nodes

### Analysis

- [badwords](https://github.com/node-red/node-red-nodes/tree/master/analysis/swearfilter) - Analyses the payload and tries to filter out any messages containing bad swear words. This only operates on payloads of type string. Everything else is blocked.
- [wordpos](https://github.com/node-red/node-red-nodes/tree/master/analysis/wordpos) - Analyses the payload and classifies the part-of-speech of each word. The resulting message has msg.pos added with the results. A word may appear in multiple categories (eg, 'great' is both a noun and an adjective).

### Database

- [influxdb](https://github.com/mblackstock/node-red-contrib-influxdb) - Save and query data from an InfluxDB time series database.
- [mssql-plus](https://github.com/bestlong/node-red-contrib-mssql-plus) - Execute queries, stored procedures and bulk inserts in Microsoft SQL Server and Azure Databases SQL2000 ~ SQL2019.
- [stackhero-influxdb-v2](https://github.com/stackhero-io/node-red-contrib-stackhero-influxdb-v2) - Save and query data from an InfluxDB v2 time series database.
- [stackhero-mysql](https://github.com/stackhero-io/node-red-contrib-stackhero-mysql) - Connect to a MySQL or a MariaDB database, using TLS (SSL) and compatible with "Caching SHA2 password" authentication method (MySQL >= 8).
- [leveldb](https://github.com/node-red/node-red-nodes/tree/master/storage/leveldb) - Uses LevelDB for a simple key value pair database.
- [mysql](https://github.com/node-red/node-red-nodes/tree/master/storage/mysql) - Allows basic access to a MySQL database. 
- [sqlite](https://github.com/node-red/node-red-nodes/tree/master/storage/sqlite) - Supports read and write to a local sqlite database.

### Development

- [typescript-starter](https://github.com/alexk111/node-red-node-typescript-starter) - Quick-start template repository for creating new node sets in TypeScript.

### Function

- [datagenerater](https://github.com/node-red/node-red-nodes/tree/master/function/datagenerator) - Generate dummy data in various formats, names, addresses, emails, numbers, words, etc.
- [pidcontrol](https://github.com/node-red/node-red-nodes/tree/master/function/PID) - A PID control node for numeric inputs - provides simple controll loop feedback capability.
- [random](https://github.com/node-red/node-red-nodes/tree/master/function/random) - Random number generator - can generate integers for x to y - or floats between x and y.
- [rbe](https://github.com/node-red/node-red-nodes/tree/master/function/rbe) - Provide report by exception and deadband / bandgap capability for simple inputs.
- [smooth](https://github.com/node-red/node-red-nodes/tree/master/function/smooth) - Provide various functions across several previous values, including max, min, mean, high and low pass filters.

### Hardware

- [arduino](https://github.com/node-red/node-red-nodes/tree/master/hardware/Arduino) - Uses firmata protocol to talk to the board.
- [beaglebone](https://github.com/node-red/node-red-nodes/tree/master/hardware/BBB) - Nodes for the [Beaglebone Black](https://beagleboard.org/black).
- [blink1](https://github.com/node-red/node-red-nodes/tree/master/hardware/blink1) - [Blink1](https://blink1.thingm.com/) USB LED from ThingM.
- [blinkstick](https://github.com/node-red/node-red-nodes/tree/master/hardware/blinkstick) - [BlinkStick](https://www.blinkstick.com/) USB LED device.
- [digirgb](https://github.com/node-red/node-red-nodes/tree/master/hardware/digiRGB) - DigiSpark RGB USB LED.
- [heatmiser](https://github.com/node-red/node-red-nodes/tree/master/hardware/heatmiser) - Temperature and frost protection for Heatmiser thermostats.
- [intel-galileo](https://github.com/node-red/node-red-nodes/tree/master/hardware/intel) - A collection for the Intel Galileo and Edison.
- [ledborg](https://github.com/node-red/node-red-nodes/tree/master/hardware/LEDborg) - [LEDborg](https://www.piborg.org/ledborg) plug on module.
- [makeymakey](https://github.com/node-red/node-red-nodes/tree/master/hardware/makey) - Read from a [MakeyMakey](http://www.makeymakey.com/) input device.
- [pi-gpiod](https://github.com/node-red/node-red-nodes/tree/master/hardware/pigpiod) - An alternative to the default PI GPIO nodes that allows remote access.
- [pi-mcp3008](https://github.com/node-red/node-red-nodes/tree/master/hardware/mcp3008) - Read from MCP300x series Analogue to Digital Converter chips via the SPI bus.
- [pi-neopixel](https://github.com/node-red/node-red-nodes/tree/master/hardware/neopixel) - Drive a strip of NeoPixels directly.
- [pi-unicorn-hat](https://github.com/node-red/node-red-nodes/tree/master/hardware/unicorn) - Controls a Pimorini Unicorn HAT 8x8 LED display.
- [pibrella](https://github.com/node-red/node-red-nodes/tree/master/hardware/Pibrella) - Controls a [Pibrella](https://pibrella.com/) add-on board.
- [piface](https://github.com/node-red/node-red-nodes/tree/master/hardware/PiFace) - [PiFace](https://www.piface.org.uk/) interface module.
- [piliter](https://github.com/node-red/node-red-nodes/tree/master/hardware/PiLiter) - Controls a Pimorini Pi-LITEr 8 LED add-on board.
- [sensortag](https://github.com/node-red/node-red-nodes/tree/master/hardware/sensorTag) - Reads data from the Ti Bluetooth Low Energy SensorTag device.
- [wemo](https://github.com/node-red/node-red-nodes/tree/master/hardware/wemo) - Drive a [WeMo](https://www.belkin.com/us/Products/home-automation/c/wemo-home-automation/) socket and switch.
- [scanBLE](https://github.com/node-red/node-red-nodes/tree/master/hardware/scanBLE) - Scans for a particular Bluetooth Low Energy device.

### I/O

- [discovery](https://github.com/node-red/node-red-nodes/tree/master/io/mdns) - Discovers other Avahi/Bonjour services on the network.
- [emoncms](https://github.com/node-red/node-red-nodes/tree/master/io/emoncms) - Post to an [Emoncms](https://emoncms.org/) server.
- [noble-bluetooth](https://github.com/clausbroch/node-red-contrib-noble-bluetooth) - Based on noble for interaction with Bluetooth Low Energy devices.
- [mindconnect](https://github.com/mindsphere/node-red-contrib-mindconnect) - Upload timeseries, files and events to MindSphere.
- [modbus](https://github.com/biancoroyal/node-red-contrib-modbus) - All in one Modbus TCP and Serial package.
- [mqlight](https://github.com/node-red/node-red-nodes/tree/master/io/mqlight) - Adds nodes to send and receive using MQlight.
- [ping](https://github.com/node-red/node-red-nodes/tree/master/io/ping) - Pings a machine and returns the trip time in mS.
- [s7](https://github.com/st-one-io/node-red-contrib-s7) - Interact with Siemens S7 PLCs.
- [serialport](https://github.com/node-red/node-red-nodes/tree/master/io/serialport) - Send messages to and receive messages from a physical serial port.
- [snmp](https://github.com/node-red/node-red-nodes/tree/master/io/snmp) - SNMP receivers for single OIDs or OID tables.
- [stomp](https://github.com/node-red/node-red-nodes/tree/master/io/stomp) - Publish and subscribe to and from a [STOMP server](https://stomp.github.io/implementations.html#STOMP_Servers).
- [wol](https://github.com/node-red/node-red-nodes/tree/master/io/wol) - Sends a Wake-On-LAN magic packet to the mac address specified.
- [xiaomi-ble](https://github.com/eschava/node-red-contrib-xiaomi-ble) - Single "Xiaomi BLE" node that gets all known data from Xiaomi BLE (Bluetooth 4).

### Parsers

- [base64](https://github.com/node-red/node-red-nodes/tree/master/parsers/base64) - Converts a payload to/from base64 encoded format.
- [geohash](https://github.com/node-red/node-red-nodes/tree/master/parsers/geohash) - Converts a lat, lon payload to/from geohash format.
- [msgpack](https://github.com/node-red/node-red-nodes/tree/master/parsers/msgpack) - Converts a payload to/from msgpack binary packed format.
- [what3words](https://github.com/node-red/node-red-nodes/tree/master/parsers/what3words) - Encodes or Decodes a lat, lon position into what3words text format.

### Smarthome

- [alexa-home](https://github.com/mabunixda/node-red-contrib-alexa-home) - 仅在本地网络中与 Alexa 连接 - 不需要额外的云内容。
- [alexa-home-skill-v3](https://github.com/coldfire84/node-red-contrib-alexa-home-skill-v3) - Controls things via Alexa and Google Home.
    - [alexa-home-skill-v3-web](https://github.com/coldfire84/node-red-alexa-home-skill-v3-web) - Web Service for Alexa and Google Home.
    - [alexa-home-skill-v3-lambda](https://github.com/coldfire84/node-red-alexa-home-skill-v3-lambda) - Lambda function for node-red-alexa-home-skill-v3-web.
- [alexa-remote-cakebaked](https://github.com/cakebake/node-red-contrib-alexa-remote-cakebaked) <i>- Interacting with the Alexa API.</i> <b>- 与 Alexa API 交互。</b> <i>Emulates routine behaviour, control and query your devices.</i><b>模拟日常行为、控制和查询您的设备。</b>
- [avr-yamaha](https://github.com/krauskopf/node-red-contrib-avr-yamaha) - Integrate and control YAMAHA™ audio/video receiver via YNCA protocol.
- [ccu](https://github.com/rdmtc/node-red-contrib-ccu) - Connect with Homematic, a series of smart home automation hardware from the manufacturer eQ-3, popular especially in Germany.
- [deconz](https://github.com/deconz-community/node-red-contrib-deconz) - Access Zigbee 3.0 (Z30), Zigbee Home Automation (ZHA) and Zigbee Light Link (ZLL) lights via deCONZ.
- [fritz](https://github.com/bashgroup/node-red-contrib-fritz) - Provides easy access to your AVM Fritz!Box. Read and write the configuration including the VoIP and Dect configuration.
- [fritzapi](https://github.com/dnknth/node-red-contrib-fritzapi) - Controls smart home DECT devices and guest wifi through an AVM Fritz!Box.
- [harmony](https://github.com/Aietes/node-red-contrib-harmony) - Controls devices connected to a Logitech™ Harmony Hub.
- [home-assistant](https://github.com/AYapejian/node-red-contrib-home-assistant) - Connect with Home Assistant.
- [home-assistant-websocket](https://github.com/zachowj/node-red-contrib-home-assistant-websocket) - Various nodes using websockets to assist in setting up communication with Home Assistant.
- [homebridge-automation](https://github.com/NorthernMan54/node-red-contrib-homebridge-automation) - Integrate Homebridge Accessories into flows.
- [homee](https://github.com/stfnhmplr/node-red-contrib-homee) - Access the homee api and create virtual devices for homee.
- [homekit-bridged](https://github.com/NRCHKB/node-red-contrib-homekit-bridged) - Imitate HomeKit devices.
- [huemagic](https://github.com/Foddy/node-red-contrib-huemagic) - Controls Philips Hue bridges, lights, groups, scenes, rules, taps, switches, buttons, motion sensors, temperature sensors and Lux sensors.
- [lgtv](https://github.com/hobbyquaker/node-red-contrib-lgtv) - Controls LG webOS Smart TVs.
- [loxone](https://github.com/codmpm/node-red-contrib-loxone) - Connect to the Loxone Miniserver.
- [knx-ultimate](https://github.com/Supergiovane/node-red-contrib-knx-ultimate) - Controls KNX intallation. With optional ETS group address importer and gateway simulation. 
- [openhab3](https://github.com/jeroenhendricksen/node-red-contrib-openhab3) - Integration of openHAB item states and commands.
- [power-saver](https://power-saver.smoky.no/) - Automatically save money on variable electricity prices.
- [smartnora](https://github.com/andrei-tatar/node-red-contrib-smartnora) - Google smart home Action integration via Smart NORA.
- [sonos-plus](https://github.com/hklages/node-red-contrib-sonos-plus) - Controls Sonos player in your local network.
- [tado-client](https://github.com/mattdavis90/node-red-contrib-tado-client) - Connect to the Tado Web API.
- [tahoma](https://github.com/nikkow/node-red-contrib-tahoma) - Controls a Somfy Tahoma box (Roller shutters, etc.). 
- [tasmota](https://github.com/DaveMDS/node-red-contrib-tasmota) - Tasmota devices integration for building automation.
- [tuya-smart](https://github.com/hgross/node-red-contrib-tuya-smart) - Interface with smart plugs, bulbs, etc. from tuya.
- [zigbee](https://github.com/hobbyquaker/node-red-contrib-zigbee) - Controls Zigbee Devices via a CC253x Module.
- [zigbee2mqtt](https://github.com/andreypopov/node-red-contrib-zigbee2mqtt) - Zigbee2mqtt connectivity.
- [zwave-js](https://github.com/zwave-js/node-red-contrib-zwave-js) - Integrates Z-Wave node based on Z-Wave JS.

### Social

- [chatbot](https://github.com/guidone/node-red-contrib-chatbot) - Full featured chat bot for Telegram, Facebook Messenger, Viber, Twilio and Slack.
- [discord-advanced](https://github.com/Markoudstaal/node-red-contrib-discord-advanced) - Interact with Discord, via Discord.js.
- [dweetio](https://github.com/node-red/node-red-nodes/tree/master/social/dweetio) - Uses [dweetio](https://dweet.io/) to send/receive messages.
- [email](https://github.com/node-red/node-red-nodes/tree/master/social/email) - Sends and receives simple emails from services like gmail or smtp or imap servers.
- [feedparser](https://github.com/node-red/node-red-nodes/tree/master/social/feedparser) - Reads messages from an atom or rss feed.
- [irc](https://github.com/node-red/node-red-nodes/tree/master/social/irc) - Connect to an IRC server to send and receive messages.
- [notify](https://github.com/node-red/node-red-nodes/tree/master/social/notify) - Uses [Growl](https://growl.info/) to provide a desktop popup. Only useful on the local Apple machine.
- [prowl](https://github.com/node-red/node-red-nodes/tree/master/social/prowl) - Uses [Prowl](https://www.prowlapp.com/) to push to an Apple device that has the Prowl app installed.
- [pushbullet](https://github.com/node-red/node-red-nodes/tree/master/social/pushbullet) - Uses [PushBullet](https://www.pushbullet.com/) to push an Android device that has the app installed.
- [pusher](https://github.com/node-red/node-red-nodes/tree/master/social/pusher) - Publish-Subscribe to a [Pusher](https://pusher.com/) channel/event.
- [pushover](https://github.com/node-red/node-red-nodes/tree/master/social/pushover) - Sends alerts via [Pushover](https://pushover.net/).
- [PushStaq](https://github.com/pantchox/node-red-contrib-pushstaq) - Send real time alerts using Push Notifications from your Node-Red flows to any device with [PushStaq](https://www.pushstaq.com).
- [slack](https://github.com/yayadrian/node-red-slack) - Interact with the Slack API.
- [sms77](https://github.com/sms77io/nodered-contrib-sms77) - Uses [sms77](https://www.sms77.io/) service for SMS, text-to-speech calls and number lookups.
- [telegrambot](https://github.com/windkh/node-red-contrib-telegrambot) - Contains a receiver and a sender node which act as a Telegram Bot.
- [twilio](https://github.com/node-red/node-red-nodes/tree/master/social/twilio) - Uses [Twilio](https://www.twilio.com/) service to send/receive text messages.
- [whin](https://github.com/inUtil-info/node-red-contrib-whin) - Send and receive whatsapps from within a nodered flow.
- [xmpp](https://github.com/node-red/node-red-nodes/tree/master/social/xmpp) - Connect to an XMPP server to send and receive messages.
- [open-wa (whatsapp)](https://github.com/open-wa/node-red-contrib-wa-automate) - Efficiently connect to remote instances of your open-wa whatsapp automate servers.

### System

- [aedes](https://github.com/martin-doyle/node-red-contrib-aedes) - MQTT Broker based on Aedes.
- [dockerode](https://github.com/naimo84/node-red-contrib-dockerode) - Connect to Docker daemon.
- [os](https://github.com/Argonne-National-Laboratory/node-red-contrib-os) - Obtain system information.

### Time

- [blindcontroller](https://github.com/alisdairjsmyth/node-red-contrib-blindcontroller) - Automate the control of household roller blinds based on the current position of the sun.
- [bigtimer](https://github.com/scargill/node-red-contrib-bigtimer) - Timing node with support for dusk/sunset dawn/sunrise and variations also day/week/month (and special days) control. The node offers outputs suitable for MQTT, speech and databases.
- [suncalc](https://github.com/node-red/node-red-nodes/tree/master/time/suncalc) - Uses the suncalc module to generate an output at sunrise and sunset based on a specified location. 
- [simpletime](https://github.com/Paul-Reed/node-red-contrib-simpletime) - Adds time and date payloads with various formatting options, which can be retreived and used later in the flow.
- [sun-position](https://github.com/rdmtc/node-red-contrib-sun-position) - Timer based flow control with dusk, dawn (and variations) and much more. Additional you can get sun and moon position or to control a flow by sun or moon position.
- [timeswitch](https://github.com/node-red/node-red-nodes/tree/master/time/timeswitch) - Lets the user set simple repeating timers for example for simple heating control, etc.

### Utility

- [actionflows](https://github.com/Steveorevo/node-red-contrib-actionflows) - Brings easy to use loops and OOP (object oriented programming) features.
- [alarm](https://github.com/Anamico/node-red-contrib-alarm) - Build your own home alarm system with any number of panels, zones, sensors, triggers and automations.
- [bool-gate](https://flows.nodered.org/node/node-red-contrib-bool-gate) - Boolean logic gates.
- [daemon](https://github.com/node-red/node-red-nodes/tree/master/utility/daemon) - Starts up (calls) a long running system program and pipes STDIN, STDOUT and STDERR to and from that process. 
- [exif](https://github.com/node-red/node-red-nodes/tree/master/utility/exif) - Extracts GPS and other EXIF information from a passed in jpeg image.
- [german-holidays](https://github.com/rdmtc/node-red-contrib-german-holidays) - Getting german holidays or information if today/tomorrow is a holiday.
- [ical-events](https://github.com/naimo84/node-red-contrib-ical-events) - Get events from an ical-URL, a caldav-server or from iCloud via [kalender-events](https://github.com/naimo84/kalender-events).
- [interval-length](https://github.com/bartbutenaers/node-red-contrib-interval-length) - Measure the (time) interval length between successive messages.
- [moment](https://github.com/totallyinformation/node-red-contrib-moment) - Produces a nicely formatted Date/Time string using the Moment.js library. 
- [owntracks](https://github.com/hardillb/node-red-contrib-owntracks) - Converts Owntrack Messages into standard geo message and deals with encrypted locations.
- [persist](https://github.com/DeanCording/node-red-contrib-persist) - Persist data over Node-RED restarts and deploys.
- [self-healing](https://github.com/jpdias/node-red-contrib-self-healing) - Making Node-RED more resilient by adding self-healing capabilities.
- [state-machine](https://github.com/DeanCording/node-red-contrib-state-machine) - Wraps around the JavaScript State Machine to implement a finite state machine.
- [string](https://github.com/steveorevo/node-red-contrib-string) - Provides native and extended chainable JavaScript string parsing and manipulation methods.
- [twc-weather](https://github.com/johnwalicki/node-red-contrib-twc-weather) - The Weather Company and Weather Underground Personal Weather Station APIs.
- [users](https://github.com/SenseTecnic/node-red-contrib-users) - Quickly build a very simple user access control for HTTP-based flows.
- [watson](https://github.com/watson-developer-cloud/node-red-node-watson) - Interact with the IBM Watson services in IBM Cloud.

### UI

- [browser-utils](https://github.com/ibm-early-programs/node-red-contrib-browser-utils) - Add browser functionality such as file upload, camera & microphone.
- [node-red-dashboard](https://github.com/node-red/node-red-dashboard) - Create a live data dashboard.
    - [https://flows.nodered.org/collection](https://flows.nodered.org/collection/590bc13ff3a5f005c7d2189bbb563976) - Dashboard extra nodes.
- [flow-manager](https://flows.nodered.org/node/node-red-contrib-flow-manager) - Separates flow json to multiple files.
- [iglass](https://www.npmjs.com/package/iglass-nodes) - Interaction with [iGlass Automation](https://iglass.international) blocks.
- [image-output](https://github.com/rikukissa/node-red-contrib-image-output) - Simple image output node. Useful for previewing images (of face detecting, object recognition etc.) inside the flow editor.
- [uibuilder](https://github.com/TotallyInformation/node-red-contrib-uibuilder) - Create dynamic web interfaces using any (or no) front end libraries for convenience.
- [web-worldmap](https://github.com/dceejay/RedMap) - Provide a world map web page for plotting "things" on.

## Community

- [HomeAssistant Forum](https://community.home-assistant.io/c/third-party/node-red/31)
- [Node-RED Forum](https://discourse.nodered.org/)
- [Node-RED Blog](https://nodered.org/blog/)
- [Node-RED User Group Japan](https://nodered.jp/)
- [Reddit](https://www.reddit.com/r/nodered/)
- [Redmatic Forum](https://homematic-forum.de/forum/viewforum.php?f=77)
- [Slack](https://nodered.org/about/community/slack)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/node-red)
- [Steves Node-RED Guide](https://stevesnoderedguide.com/)
- [Twitter](https://twitter.com/NodeRED)
- [YouTube](https://www.youtube.com/channel/UCQaB8NXBEPod7Ab8PPCLLAA)

## Contributing

Contributions welcome! Read the [contribution guidelines](https://github.com/naimo84/awesome-nodered/blob/master/contributing.md) first.
