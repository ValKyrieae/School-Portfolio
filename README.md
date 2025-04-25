# Kyrie L – School + Portfolio Projects

Hey there! This repo holds everything from my personal portfolio site to the projects I’ve done in Python, Java, HTML/CSS, and more. It’s where I keep the work I’ve built from scratch (no templates here), and where I can track my growth while learning new tools and trying new things.

---

## 📁 Project Highlights

### 🌐 Portfolio Website  
Fully custom-coded site that shows off who I am and what I do — built with just HTML, CSS, and a little JavaScript. Includes a popup interaction, 3D image cube, and links to everything else.  
[View Live](https://valkyrieae.github.io/School-Portfolio) | [View Source](./)

---

### 👶 Python Baby Name Generator  
Group project from my Python logic class — lets you randomly generate baby names and (soon) compare popularity on a chart. Uses real Social Security name data, tuples, loops, and input validation.  
[View Code](./baby_name_gen) | Full README in progress

---

### 🔼 Classical Image Cube (HTML/CSS)  
An animated cube of classical sketches from my Java + web design class. Uses CSS 3D transforms, filters, and custom styling for a soft art-style vibe.  
[View Demo](#) | [Sample CSS](#)

---

### 🧑‍💻 Cisco Switch Interface Lab (Packet Tracer)  
Assignment from my networking class where I configured switches, trunk links, and VLANs using Cisco Packet Tracer. It helped reinforce how devices connect and communicate — and how to troubleshoot when they don’t.  
[View Lab File](./Lab2SelfMade.pka.pkt) | [Read More Below](#-cisco-packet-tracer-lab--switch-interface-configuration)

---

## 🛠️ Tech I’ve Used

- HTML + CSS (hand-coded, no frameworks)
- Python (Tuples, Random, Input Validation)
- Java (for logic and structure)
- GitHub Pages (for hosting)
- Google Fonts + UI details
- JavaScript (popup and interaction)
- Cisco Packet Tracer (network simulation)
- Networking concepts: VLANs, trunking, IP config

---

## 💡 Why This Exists

I didn’t want a portfolio that looked like everyone else’s — I wanted one that actually showed what I’ve done and how I’m growing. This repo is part reference, part sandbox, and totally mine. I’ve learned a lot through these builds (especially the hard way), and I wanted a space to keep track of that.

---

## 📌 What’s Coming Next

- More projects as I finish out my cybersecurity degree
- Better responsive styling (mobile-friendly)
- Charts + visuals for the baby name generator
- Python practice: log parsers, scripts, and maybe a weather project 👀

---

## 🔌 Cisco Packet Tracer Lab – Switch Interface Configuration

This was an assignment for my networking class where we used Cisco Packet Tracer to manually configure switch interfaces. The goal was to get more hands-on experience with how switches work, how to assign IPs, and how VLANs and trunking actually function in a real network.

### 🖥️ What I set up
- 3 Cisco 2960 switches (Switch0, Switch1, Switch2)
- 4 endpoint devices (3 PCs and 1 laptop)
- Each device had a static IP (192.168.1.1 to 192.168.1.4)
- The switches were connected in layers, with trunk links between them

### ⚙️ What I configured
- Set interface speeds and duplex modes manually
- Disabled auto-negotiation to practice manual config
- Assigned all PCs and laptop to VLAN 1
- Configured trunk ports between the switches (no negotiation protocol)
- Used ping and switch CLI to verify everything was working

### 🧠 What I learned
- How access ports and trunk ports are different and when to use them
- How misconfigured VLANs can break connectivity (and how to fix it)
- That trunking doesn’t just magically happen — you actually have to tell the switch what you want
- How to troubleshoot connection issues using port LEDs and `show` commands

### 🖼️ Screenshot

![Lab Screenshot](./4f659262-1fd8-4e7e-9d2
