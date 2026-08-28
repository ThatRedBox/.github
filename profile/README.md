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

In the browser, open up the `web editor` at `http://[ip address]?view=editor` to start wiring up your logic with the visual, low-code Node-RED flow editor. [Read more...](https://github.com/ThatRedBox/Redbox-setup-nodered)

### Multiple devices
Of course, in most integrated productions, the envisioned experience goes beyond one single installation, even beyond one location. Allow Red[box] devices to communicate with each other by setting up the **Red[box] server** and in the same way you embed your logic into the devices, wire your logic into their interactions.

Whether on a `local network` or in the `cloud`, download and run the installer for the server in the commandline:

```bash
wget -O install.sh https://github.com/ThatRedBox/Redbox-setup-server/releases/latest/download/install.sh
chmod +x ./install.sh
sudo ./install.sh
```

When the server is up and running, point each **Red[box]** to your server by configuring their `cloud connection`. [Read more...](https://github.com/ThatRedBox/Redbox-setup-server)

### Demo
New to Redbox? Catch the vibe with this [demo project](https://github.com/ThatRedBox/Redbox-demo)!

## Support

Together we're better. The Red[box] project is a currated implementation of several open source technologies backed by thriving communities that live on every social media platform. A Red[box] is not a black box, ask your questions online and they will get answered! - Totally lost? Start [here](https://www.reddit.com/r/raspberry_pi)

<hr/>

<a href="https://certification.oshwa.org/be000035.html" target="_blank" >
    <img src="https://github.com/ThatRedBox/.github/blob/main/brand/oshw-certification-mark.png?raw=true" align="left" width="20%"/>
</a>
<p>
    Red[box] is <b>Open Source Hardware</b> certified since August 2026.
</p>
<br clear="left"/>

<a href="https://opensource.org/" target="_blank" >
    <img src="https://i0.wp.com/opensource.org/wp-content/uploads/2023/01/OSI_Horizontal_Logo_0.png?w=1488&quality=80&ssl=1" align="left" width="20%"/>
</a>
<p>
    Red[box] is distributed under <b>Open Source Initiative</b> approved licenses.
</p>
<br clear="left"/>

<hr/>

*Rules and guidelines apply to the usage of the **Red[box]** brand