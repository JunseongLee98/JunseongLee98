# Hi, I'm Junseong Lee 👋

<p align="center">
  <img src="https://github.com/junseonglee98.png" alt="Junseong Lee" width="150" style="border-radius: 50%;" />
</p>

**Software Engineer | Informatics Student @ University of Washington**

I'm a software engineer with experience in manufacturing systems, mobile development, and data frameworks. Currently pursuing my BS in Informatics at UW while working as a Teaching Assistant for Product Management.

[![Email](https://img.shields.io/badge/Email-wnstjd98%40uw.edu-blue)](mailto:wnstjd98@uw.edu)
[![GitHub](https://img.shields.io/badge/GitHub-junseonglee98-181717?logo=github)](https://github.com/junseonglee98)
[![Phone](https://img.shields.io/badge/Phone-206--535--0596-green)](tel:206-535-0596)

---

## 🚀 About Me

I'm a Seoul-born software engineer with a unique journey spanning manufacturing systems engineering, military service as an interpreter, and education. My experience includes developing SQL procedures for automotive manufacturing systems used by Ford, Hyundai, Kia, and Tesla, building mobile viewers for factory data analysis, and currently mentoring 65 students in Product Management at UW.

I bring a meticulous approach to problem-solving, emphasizing root cause analysis and assumption validation—skills I've honed both in engineering systems and teaching others.

---

## 💼 Professional Highlights

### Software Engineering at EZMS
- **Manufacturing Systems Development**: Built SQL procedures for Manufacturing Engineering Systems deployed across international automobile plants (Ford, Hyundai, Kia, Tesla)
- **Recall Prevention**: Established back-trace mechanisms for product recall scenarios
- **Mobile Innovation**: Developed mobile viewer for real-time manufacturing status and data analysis
- **Data Framework**: Designed new framework improving timeline stamping accuracy and serial number parsing
- **Cross-border Tools**: Created Data Viewer tools enabling business owners to monitor Vietnamese factory operations

### Military Service
- **Technical Translation**: Translated 127 documents on Radio Communication Hardware as Interpreter Sergeant at USAG Humphreys
- **Community Impact**: Tutored Math, Chemistry, and Coding for veterans with hearing disabilities, developing specialized communication methods

### Education & Mentorship
- **Teaching Assistant**: Managing 65-student Product Management program at UW (INFO 380)
- **Boot Camp Leadership**: Led team of 12 instructors for AP/IB exam preparation at Sehan Academy

---

## 🛠️ Technical Skills

**Languages**  
![C#](https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![Elixir](https://img.shields.io/badge/Elixir-4B275F?logo=elixir&logoColor=white)

**Technologies & Tools**  
`.NET` • `Microsoft SQL Server` • `VSCode` • `AWS` • `Phoenix` • `Phoenix LiveView` • `GenServer`

**Specializations**
- Manufacturing Engineering Systems
- Data Analysis & Visualization
- Mobile Application Development
- Back-end Architecture
- Real-time Systems

---

## 🎯 Featured Projects

---

### 🎓 [Cadence](https://github.com/JunseongLee98/Capstone_Bridgers) — Capstone Graduation Project *(Jan 2026)*

**Role**: Lead Developer · Backend Engineer · AI Engineer

**Name of Project**: Cadence — AI-Powered Calendar & Task Manager

**Goals**: Build an intelligent calendar application that reduces the cognitive overhead of task planning by using AI to automatically distribute tasks across a user's existing schedule.

**Problem & Opportunity**: Students and professionals struggle to break down large tasks and fit them into their real-world calendars. Most to-do apps require manual scheduling, leading to unrealistic plans or procrastination. Cadence addresses this gap by automating the scheduling step entirely.

**My Role**: As Lead Developer, I architected the overall system and drove both backend and AI integration. I designed the task ingestion pipeline, built the AI layer that reads task descriptions and maps them to open calendar slots, and coordinated the development workflow across the team.

**Process & Solution**: I led the design of the TypeScript-based backend, integrating an LLM to parse free-form task descriptions and produce structured scheduling recommendations. The AI layer analyzes calendar availability and distributes tasks according to priority, duration estimates, and user preferences. I also implemented the manual task entry flow as a fallback and for user overrides.

**Outcome & Next Steps**: Cadence successfully demonstrates AI-assisted scheduling end-to-end. Next steps include improving the AI's handling of recurring tasks, adding deadline-awareness, and conducting user testing with UW students.

**Takeaways**: This project deepened my understanding of prompt engineering for structured output and the challenges of mapping fuzzy user intent onto concrete calendar data. Leading a capstone team also sharpened my skills in scoping work and keeping a project on track under academic deadlines.

**URL**: [github.com/JunseongLee98/Capstone_Bridgers](https://github.com/JunseongLee98/Capstone_Bridgers)

---

### 📱 [Task-Momma](https://github.com/ntran180/Task-App) — Graduation Project *(Mar 2026)*

**Role**: Lead Developer · Backend Engineer

**Name of Project**: Task-Momma — Habit-Building Task App

**Goals**: Help users reclaim small pockets of idle time throughout the day by replacing doom-scrolling with intentional, bite-sized tasks — and make it social and competitive.

**Problem & Opportunity**: People waste dozens of small minutes each day on passive phone use but feel they "don't have time" for their goals. Task-Momma reframes this: instead of needing a free hour, users only need five minutes. The social competition layer adds accountability and motivation.

**My Role**: As Lead Developer and Backend Engineer, I owned the server-side architecture and Firebase data modeling. I designed the database schema for users, tasks, and session tracking, built the backend logic for task assignment and time-slot matching, and integrated the competitive leaderboard system.

**Process & Solution**: I architected the backend on Firebase, structuring real-time listeners so the app immediately reflects completed micro-sessions and updates friend leaderboards without polling. I worked closely with the frontend team to define the API contract between Swift UI components and Firebase, and implemented the core algorithm that selects an appropriate task based on the available time window.

**Outcome & Next Steps**: The app is functional with core features—micro-task selection, session logging, and friend competition. Next steps include push notifications to prompt users during typical scroll sessions and an onboarding flow to help users populate their initial task list.

**Takeaways**: Building on Swift and Firebase taught me the importance of designing for eventual consistency in real-time mobile apps. Leading the backend also reinforced how critical clear API contracts are when frontend and backend teams work in parallel.

**URL**: [github.com/ntran180/Task-App](https://github.com/ntran180/Task-App)

---

### 🏫 [CampusXchange](https://github.com/JunseongLee98/campus_xchange) — Personal Project *(Apr 2025)*

**Role**: Sole Developer

**Name of Project**: CampusXchange — Campus Auction Marketplace

**Goals**: Create a real-time auction platform exclusively for students on the same campus, making it easy to buy and sell used goods within a trusted community.

**Problem & Opportunity**: General platforms like Facebook Marketplace or eBay lack campus-specific trust and convenience. Students often want to offload textbooks, furniture, or electronics quickly to people nearby. CampusXchange solves this with a campus-scoped, real-time bidding experience.

**My Role**: I designed and built the entire application solo — from database schema and auction state management to the real-time UI layer.

**Process & Solution**: I chose Elixir and Phoenix LiveView to handle real-time auction updates without writing complex JavaScript. Each auction is managed as an independent process using Elixir's GenServer, which handles bid validation, countdown timers, and state transitions concurrently and reliably. Phoenix LiveView pushes UI updates to all connected bidders instantly when a new bid arrives.

**Outcome & Next Steps**: The platform supports concurrent auctions with live bid updates and automatic auction closing. Next steps include adding user authentication, a reputation/rating system, and campus email verification to enforce community membership.

**Takeaways**: This project gave me hands-on experience with the actor model and OTP concurrency in Elixir. Managing auction state as isolated processes was a paradigm shift from traditional web development and showed me how powerful process-oriented architecture is for event-driven systems.

**URL**: [github.com/JunseongLee98/campus_xchange](https://github.com/JunseongLee98/campus_xchange)


---

### 📈 [Auto Investing Bot](https://github.com/JunseongLee98/TradeBot) — Personal Project *(Mar 2022)*

**Role**: Sole Developer

**Name of Project**: Auto Investing Bot — Automated Trading System

**Goals**: Build an automated trading bot that executes investment strategies around the clock without requiring manual intervention, deployed on cloud infrastructure for reliability.

**Problem & Opportunity**: Manual trading requires constant monitoring and is prone to emotional decision-making. Automated bots can follow rules consistently and act on signals faster than any human. This project was an opportunity to apply Python programming to a real financial domain and explore cloud deployment.

**My Role**: I designed, built, and deployed the entire system independently — including the trading strategy logic, AWS infrastructure setup, and ongoing monitoring.

**Process & Solution**: I implemented the bot in Python, scripting trading strategies and portfolio management rules that run on a schedule. The bot was deployed on an AWS EC2 instance to ensure it runs continuously. I configured the instance for reliability and set up logging to track trades and performance over time.

**Outcome & Next Steps**: The bot successfully executed automated trades per its configured strategy. Next steps would include implementing backtesting against historical data, adding more sophisticated strategy signals, and building a simple dashboard to visualize portfolio performance.

**Takeaways**: This project was my first experience with cloud deployment and taught me practical AWS skills (EC2 setup, SSH, process management). It also gave me a deeper appreciation for the importance of rigorous testing before deploying anything that handles real money.

**URL**: [github.com/JunseongLee98/TradeBot](https://github.com/JunseongLee98/TradeBot)

---

## 📚 Currently

- 🎓 Completing BS in Informatics at University of Washington (Expected: Jun 2026)
- 👨‍🏫 Teaching Assistant for INFO 380 - Product Management
- 🔨 Building real-time applications with Elixir and Phoenix
- 📖 Exploring advanced computational theory and learning algorithms

**Relevant Coursework**: Computer Architecture • Comparison of Learning Algorithms • Computational Theory • Client-side Web Development

---

## 🎵 Beyond Code

When I'm not coding or teaching, you'll find me:
- 🎮 Gaming and exploring virtual worlds
- 🍳 Experimenting with new recipes
- 🎻 Playing cello and guitar
- 🎬 Watching films (favorites: *The Mask*, *The Matrix*, *Simpsons The Movie*)
- 📚 Reading mystery novels and neuroscience (*The Snowman* by Jo Nesbø, *The Man Who Mistook His Wife for a Hat* by Oliver Sacks)
- 🎵 Listening to Cory Wong - "You Got to Be You"

---

## 📫 Let's Connect

I'm always open to discussing software engineering, product management, or potential collaborations.

- **Email**: [dlwnstjd98@gmail.com](mailto:dlwnstjd98@gmail.com)
- **Phone**: 206-535-0596
- **Location**: Seattle, WA | Seoul, South Korea

---

<div align="center">
  <i>💡 "Meticulous problem-solving starts with identifying root causes and validating assumptions."</i>
</div>
