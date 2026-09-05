<h1 align="center">Hirdyanshu</h1>

<p align="center">
  CSE graduate who likes the layer where software meets the operating system.<br>
  Currently writing macOS utilities in Swift.
</p>

<p align="center">
  <a href="https://leetcode.com/u/Hirdyanshu2004/"><img src="https://img.shields.io/badge/LeetCode-Hirdyanshu2004-FFA116?style=flat&logo=leetcode&logoColor=white" alt="LeetCode"></a>
  <a href="https://www.codechef.com/users/noobhirdyanshu"><img src="https://img.shields.io/badge/CodeChef-noobhirdyanshu-5B4638?style=flat&logo=codechef&logoColor=white" alt="CodeChef"></a>
</p>

---

## 🍝 Macaroni

**Per-app volume control for macOS** — because macOS has no API for setting one
app's volume, and the good commercial option costs $47.

<a href="https://github.com/HirdyanshuSinghChanaria/Macaroni">
  <img src="https://raw.githubusercontent.com/HirdyanshuSinghChanaria/Macaroni/main/docs/demo.gif" width="600" alt="Macaroni demo">
</a>

It works by creating a **Core Audio process tap** on the target app, muting its
original output, and re-rendering its audio through a private aggregate device
with your gain applied. Also does clipboard history, live network speed in the
menu bar, scroll inversion, and a disk cleaner that shows you exactly what it
found before deleting anything.

`Swift` `SwiftUI` `CoreAudio` · MIT · [**Source →**](https://github.com/HirdyanshuSinghChanaria/Macaroni)

---

## 📶 Auto WiFi Auth

**A daemon that logs you back into captive portals so downloads don't die
overnight.** Anyone who has lived in a hostel or used university WiFi knows the
problem: the portal session expires, and everything silently stops.

It runs hidden in the background and only shows a window when it meets a network
it doesn't recognize. The interesting part is the universal solver — instead of
hardcoding one login page, it parses the portal's HTML to find the username,
password and hidden token fields, then re-fetches a **fresh token** before each
submission, which is what defeats the session-timeout behaviour that breaks
naive scripts. Picks the right OS network tooling underneath (`netsh` on
Windows, `networksetup` on macOS).

`Python` `CustomTkinter` `BeautifulSoup` · [**Source →**](https://github.com/HirdyanshuSinghChanaria/auto_wifi_auth)

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=HirdyanshuSinghChanaria&show_icons=true&theme=tokyonight&hide_border=true&count_private=true">
  <img src="https://github-readme-stats.vercel.app/api?username=HirdyanshuSinghChanaria&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" height="165">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=HirdyanshuSinghChanaria&layout=compact&theme=tokyonight&hide_border=true">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HirdyanshuSinghChanaria&layout=compact&hide_border=true" alt="Top languages" height="165">
</picture>

</div>

---

<p align="center">
  <a href="https://github.com/HirdyanshuSinghChanaria?tab=repositories">Repositories</a> ·
  <a href="https://www.linkedin.com/in/hirdyanshu-chanaria-27132524b/">LinkedIn</a>
</p>
