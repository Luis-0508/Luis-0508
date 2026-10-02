<p align="center">
  <img src="assets/network-map.svg" width="880" alt="Hi, I'm Luis. A network map of my projects, all linked to NERVE, which runs in the background.">
</p>

I'm a systems administrator in Germany. At work it's Linux, Windows, Active Directory and keeping
things running. After hours I build software I'd want to use myself: careful, offline-first where
possible, and documented well enough that I'll still understand it in a year.

## New on the network

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Luis-0508/plantarium">
        <img src="https://raw.githubusercontent.com/Luis-0508/plantarium/main/docs/screenshots/plant-view-areca-palm.webp" alt="Plantarium showing a procedurally generated Areca palm in its pot">
      </a>
      <h3><a href="https://github.com/Luis-0508/plantarium">Plantarium</a></h3>
      An interactive 3D herbarium for houseplants, from leaf to root. Each plant and its root
      system is generated procedurally from a few botanical parameters, at real-world scale.
      <br><br>
      <sub>React 19, TypeScript, three.js with React Three Fiber</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Luis-0508/Cykla">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Luis-0508/Cykla/master/docs/images/hero-dark.png">
          <img src="https://raw.githubusercontent.com/Luis-0508/Cykla/master/docs/images/hero-light.png" alt="Three Cykla screens: the today overview, the calendar and the estimate explanation">
        </picture>
      </a>
      <h3><a href="https://github.com/Luis-0508/Cykla">Cykla</a></h3>
      A free, offline-first period and cycle tracker for iOS and Android. What you record and what
      the app estimates stay separate, and every estimate explains itself. No account, no cloud.
      <br><br>
      <sub>Expo, React Native, TypeScript, local SQLite</sub>
    </td>
  </tr>
</table>

## Running in the background

```text
$ systemctl status nerve
● nerve.service - Self-hosted network management platform
     Loaded: loaded (private repository; enabled)
     Active: active (running) in the background
      Tasks: device discovery, infrastructure inventory, network visualization
     Status: "Building it slowly and properly. Public when it's ready."
```

**NERVE** is the project I keep coming back to. It's a self-hosted platform that discovers what's
on your network and maps how devices, VMs, containers and services connect, so the network itself
becomes the way you navigate. It runs on Go, PostgreSQL and Docker Compose. It isn't public yet,
but it's why the map above has something in the middle.

## Also on the network

| Host | What it does |
| --- | --- |
| [**sysadmin-scripts**](https://github.com/Luis-0508/sysadmin-scripts) | Windows support scripts for Active Directory, Outlook, Teams, OneDrive and Appx cleanup. Each one previews first and only changes the machine when you pass `/apply`. |
| [**pizza-order-tool**](https://github.com/Luis-0508/pizza-order-tool) | Collects a group's pizza order in English, German, Italian or Greek. [Try it](https://luis-0508.github.io/pizza-order-tool/). |
| [**discord-rich-presence**](https://github.com/Luis-0508/discord-rich-presence) | A custom Discord Rich Presence with your own text, images and buttons. |

## Homelab

The homelab is where things break before they reach anything that matters: Proxmox, Docker
Compose, WireGuard, reverse proxies, monitoring and backups. Most of what ends up in NERVE started
as a question about my own network.

**Toolbox:** Linux, Windows Server, Active Directory, Proxmox, Docker, PowerShell, Bash, Go,
TypeScript and React. Next on the list: Ansible and infrastructure as code.

## Say hello

Found a bug or have an idea for one of the projects? Open an issue in that repository. I'm always
happy to talk about Linux, self-hosting and small tools that save a sysadmin ten minutes a day.
