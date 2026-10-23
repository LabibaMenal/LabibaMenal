<div align="center">

# Hey, I'm Labiba 👋

### another software and systems dork(trust me I'm different from the millions worldwide) 🐱‍💻

*I try to make sense of this data while still figuring out college.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-labiba--menal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/labiba-menal/)
[![Codeforces](https://img.shields.io/badge/Codeforces-Pupil_1236-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/labibamenal2005)
[![LeetCode](https://img.shields.io/badge/LeetCode-labibamenal-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/labibamenal/)

</div>

---

## 🎓 About Me

- 🏛️ B.Tech in Mechanical Engineering @ **IIT (BHU) Varanasi** (2024 – 2028). Yes, I build software and not engines. The engines will be fine without me.
- 💻 Into **DSA, graph algorithms, concurrency, and full-stack development**
- 🧩 Competitive programmer: **Pupil (1236) on Codeforces**
  
### 🧠 The Dorky Details

- 🔭 **Currently working on:** grinding DSA, polishing my projects, and being a part of this AI/ML slop like a typical Gen-Z
- 👯 **Looking to collaborate on:** interesting projects, especially graphs, backends, or anything with a "wait, how does that actually work?" energy
- 🤔 **Looking for help with:** convincing my race conditions to stop racing
- 💬 **Ask me about:** graph algorithms, concurrency (and why mutexes are a love language), real-time apps, and how a mech engineer ended up here
- 📫 **How to reach me:** [LinkedIn](https://www.linkedin.com/in/labiba-menal/) is the fastest way. Bribes in the form of good problem statements are welcome.
- ⚡ **Fun fact:** I appeared numerous times at the National Spell Bee finals, so yes, I will quietly judge your commit message spelling 🐝

---

## 🚀 Projects

### 🚌 RajTransit: GTFS Network Resilience Analyzer
*"What happens to a city's buses if a road gets blocked?" Turns out: a lot.*

An interactive dashboard for Rajkot's bus network (**716 stops, 903 edges, 168 routes**), built as an academic research project under Prof. Lakshay Agrawal.

- Parsed raw GTFS data into a GeoJSON graph via **LOOM (C++)**
- **BFS** road-block simulation to find isolated stops via connected components
- **Dijkstra** with Haversine-weighted edges, answering queries in **under 1 ms**
- Flagged risky infrastructure: a corridor with **79 overlapping routes** and **39 zero-redundancy stops**
- Fully client-side on GitHub Pages, no backend needed

`JavaScript` `Leaflet.js` `C++` `Graph Algorithms`
[Code](https://github.com/LabibaMenal) <!-- TODO: replace with repo link --> · [Live Demo](https://github.com/LabibaMenal) <!-- TODO: replace with website link -->

### 🔨 LiveBid: Real-Time Auction Platform
*Sold! To the server that never forgets what time it is.*

A MERN + Socket.io bidding platform where every auction lives in its own room.

- **Crash-recoverable timers**: absolute end-time stored in MongoDB, so a server restart doesn't reset the clock
- **Server-authoritative validation** of price and status before every write
- Live "who's typing a bid" indicator
- Compound indexing on `status` + `endTime` for fast lookups
- Deployed on Vercel, Render and MongoDB Atlas

`MongoDB` `Express` `React` `Node.js` `Socket.io`
[Code](https://github.com/LabibaMenal) <!-- TODO --> · [Live Demo](https://github.com/LabibaMenal) <!-- TODO -->

### 🎟️ RushBooker: Flash-Sale Concurrent Ticket Broker
*1,000 threads. 50 seats. Zero double-bookings (when I remember the mutex).*

An IRCTC Tatkal-style booking engine in **C++17**.

- Custom **thread pool** + condition-variable **priority queue** (VIPs first)
- Ships both a synchronized and an *intentionally broken* path, so you can watch race conditions create duplicate tickets and crashes in real time
- Raw **Winsock2 TCP** layer, with a live demo (JS seat map + C++ server on Railway)

`C++17` `Multithreading` `Concurrency` `Winsock2` `JavaScript`
[Code](https://github.com/LabibaMenal) <!-- TODO --> · [Live Demo](https://github.com/LabibaMenal) <!-- TODO -->

---

## 🛠️ Tech Stack

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=databricks&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![AI/ML](https://img.shields.io/badge/AI%2FML-just_getting_started-8A2BE2?style=for-the-badge)

**Core strengths:** Data Structures & Algorithms · Graph Algorithms · AI/ML · Concurrency Control · REST APIs · OOP
**Currently leveling up:** AI / Machine Learning 🌱

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=LabibaMenal&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LabibaMenal&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=LabibaMenal&theme=tokyonight&hide_border=true" alt="GitHub streak" />

</div>

---

<div align="center">

*I love Pizzas, idk why i just said that* 🚢

</div>
