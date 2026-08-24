![Redbox logo](../brand/Redbox_banner.png)

<img src="https://github.com/ThatRedBox/.github/blob/main/documentation/ThatRedBox.png?raw=true" align="right" width="40%"/>

**"What's that red box?"** you ask? The **Red[box]** is the brain embedded into your creations that brings them to life! When your ideas require interactivity that's not just a screen, and maybe not even grounded in one single thing or location. Risen from the mind of a crazy inventor experienced in building interactive museum exhibits, the _Red[Box]_ ecosystem gives you access to the necessary complexity in a simple yet robust package.

#### Features
- **A reliable, robust computer system** ready to build into your creations. [Raspberry Pi](https://raspberrypi.com) equipped with [Edgeberry](https://github.com/Edgeberry) provide a solid foundation for building your craziest ideas upon.
- **Visual programming and real-time insight** with [Node-RED](https://nodered.org), an industry-trusted open-source platform with strong community support, requiring no special tools or licenses.
- **Compatibile with a wide range of sensors and actuators** from several popular ecosystems (e.g., Grove, [Crowtail](https://www.elecrow.com/steam-education/crowtail.html), ... ) through the [Hardware Cartridge](https://github.com/ThatRedBox/Redbox-Explorer-Hardware-Cartridge) allowing for limitless interactivity possibilities.
- **You are in control**. You own every bit of hardware, software and on-prem/cloud infrastructure. No black boxes, everything open source.

<br clear="right"/>

## Getting Started
A Red[box] gets its compute from a [Raspberry Pi™](https://www.raspberrypi.com/),that's equipped with the [Edgeberry™](https://www.elecrow.com/catalogsearch/result/?q=edgeberry) device suite for robustness, and the [Explorer Hardware Cartridge](https://github.com/ThatRedBox/Redbox-Explorer-Hardware-Cartridge) which allows it to interact with a wide range of sensors and actuators.

With a single **Red[box]**, you can open up a new dimension into your creations by embedding a digital experience. Select [sensors and actuators](https://www.elecrow.com/catalogsearch/result/?q=+crowtail) that match your vision for interactivity, and directly connect them to the I/O ports of the box.

If no software was installed yet, download and execute the installer from the commandline on the device.

```bash
wget -O install.sh https://github.com/ThatRedBox/Redbox-setup-nodered/releases/latest/download/install.sh
chmod +x ./install.sh
sudo ./install.sh
```
In the browser, open up the `web editor` at `http://[ip address]?view=editor` to start wiring up your logic into the Node-RED flow editor.

### Server
When your creation goes beyond one single embodyment, beyond one location, you can use multiple Red[box] devices in each part, with a server for wiring the logic between them and let them talk to each other.

```
Todo
```

### Demo
New to Redbox? Catch the vibe with this [demo project](https://github.com/ThatRedBox/Redbox-demo)!


<hr/>
*Trademark rules and guidelines apply to the **Red[box]** brand