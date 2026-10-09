<!-- ───────── HEADER (animated wave) ───────── -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=7D1E23&height=220&section=header&text=NetSec%20Sandbox&fontSize=55&fontColor=F7C59F&animation=fadeIn&fontAlignY=38&desc=Firewall%20%C2%B7%20Virtual%20Machines%20%C2%B7%20Cyber%20SOC&descSize=18&descColor=EB6464&descAlignY=58" alt="header" />
</p>

<!-- ───────── TYPING ANIMATION ───────── -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1200&color=EB6464&center=true&vCenter=true&width=620&lines=Learn+how+a+firewall+really+works+%F0%9F%94%A5;Manage+virtual+machines+in+your+browser+%F0%9F%96%A5%EF%B8%8F;Watch+a+SOC+dashboard+come+alive+%F0%9F%9B%A1%EF%B8%8F;100%25+HTML+%C2%B7+zero+install+%C2%B7+zero+dependencies" alt="Typing animation" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-7D1E23?style=for-the-badge&logo=html5&logoColor=F7C59F" />
  <img src="https://img.shields.io/badge/CSS3-7D1E23?style=for-the-badge&logo=css3&logoColor=F7C59F" />
  <img src="https://img.shields.io/badge/JavaScript-7D1E23?style=for-the-badge&logo=javascript&logoColor=F7C59F" />
  <img src="https://img.shields.io/badge/Made%20for-Beginners-EB6464?style=for-the-badge&labelColor=7D1E23&logoColor=F7C59F" />
</p>

---

## ✨ What is this?

> *"Three small pages to **see** how network security and infrastructure work, instead of just reading about it."*

**NetSec Sandbox** is a collection of **three standalone HTML pages**. Each one is a **simplified, beginner-friendly** take on a real-world tool.

Everything runs **in your browser**. No server, no install, no build step, and **nothing is sent over the Internet**. Just open a file and play. 🎮

---

## 🗂️ The three pages

### 🔥 Firewall Rule Simulator
*File: `firewall.html`*

A **firewall control center** where you build rules and then test them against fake traffic, just like on a real firewall.

- ➕ **Create rules** with a name, source, destination, port, protocol (`TCP` / `UDP` / `ICMP` / `ANY`), interface (`LAN` / `WAN` / `DMZ` / `VPN`) and action (**Allow** or **Deny**)
- 🧪 **Test Traffic**: simulate a packet and see which rule catches it
- 📏 **First-match logic**: rules are checked in order, like on real firewalls
- ⚠️ **Smart alerts**: flags **risky rules** and **shadowed rules** (a rule that can never trigger because an earlier one already covers it)
- 📊 Live counters: total rules, allowed/denied, critical alerts, plus a **TTL log**
- 💾 **Auto-saved** in your browser, with **export** and **demo rules** generator

*Simplified on purpose, but the logic follows how real firewalls evaluate traffic.*

---

### 🖥️ VM Infrastructure Control Panel
*File: `VMs.html`*

A **virtualization dashboard** inspired by hypervisor/datacenter consoles, with a simulated production cluster.

- 📈 **Live metrics**: CPU, RAM and disk for every VM, updating in real time
- 〰️ **Sparklines & trend arrows** to see what's going up or down
- 🚦 **Status changes** (healthy, warning, critical) that react to the load
- 🔎 **Search, filter chips and sorting** (by CPU, RAM, disk, name or status severity)
- 📋 **Summary strip** for a quick cluster overview
- ⏸️ **Pause / refresh** the simulation whenever you want

---

### 🛡️ CyberShield SOC
*File: `cybershield.html`*

A **Security Operations Center** dashboard. This one is **purely decorative**, made for the cyber-security aesthetic. 😎

- 📡 **Threat Radar** and network nodes
- 📜 **Live Security Log** scrolling in real time
- 🏗️ **Protected Infrastructure** and **System Health** panels
- 🧾 **Threat Ledger**

*All data is randomly generated. It's here to look cool, not to monitor anything real.*

---

## 🚀 How to use it

**Option 1: Live demo** (GitHub Pages)

| Page | Link |
|------|------|
| 🔥 Firewall | `https://gabpgl.github.io/Networking-Sandbox/firewall.html` |
| 🖥️ VMs | `https://gabpgl.github.io/Networking-Sandbox/VMs.html` |
| 🛡️ CyberShield | `https://gabpgl.github.io/Networking-Sandbox/cybershield.html` |

**Option 2: Run it locally**

```bash
git clone https://github.com/gabpgl/Networking-Sandbox.git
cd Networking-Sandbox
# then just double-click any .html file 🎉
```

> 💡 The pages load their fonts from Google Fonts. Offline they still work, they'll just use your system fonts.

---

## 🎓 Who is it for?

- 🌱 **Beginners** discovering networking and cybersecurity
- 🧑‍🏫 **Students and teachers** who want a visual demo
- 🎨 Anyone who likes **good-looking dashboards**

---

## ⚠️ Disclaimer

This is an **educational project**. The simulators are **simplified** and the data is **fake**. Do **not** use them to configure or monitor a real network.

---

<!-- ───────── FOOTER (animated wave) ───────── -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=7D1E23&height=120&section=footer&text=Thanks%20for%20stopping%20by!&fontSize=22&fontColor=F7C59F&animation=twinkling&fontAlignY=68" alt="footer" />
</p>
