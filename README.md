# Daniel Adamson
**Senior Software Engineer & System Architect**  
Mesa, AZ | https://www.linkedin.com/in/daniel-adamson-805091287/ 

---

## 🛠️ Specialized Technical Tracks
To review my nearly three decades of professional history, technical competencies, and architectural philosophy, select the portfolio track relevant to your engineering needs:

### 🔬 [Bioinformatics & Scientific Pipeline Profile](BIOINFORMATICS.md)
*Computational biology foundations, Nextflow pipeline exposure, edge computing, hardware instrumentation (ESP32/HuskyLens), and data parsing.*

### 🖥️ [Enterprise Systems & Database Architecture Profile](ENTERPRISE_SYSTEMS.md)
*Senior .Net Software Engineer, advanced SQL Server internals, transactional deadlock elimination, and high-volume transaction compliance.*

---

## 🚀 High-Level Core Capabilities

* **Languages & Architecture:** C#, .NET Core, C/C++, JavaScript, TypeScript, SQL, Assembly, Python, Matlab.
* **Database Internals:** Microsoft SQL Server (Query Optimization, Triggers, Stored Procedures, Indexing Strategy), Oracle, MongoDB, Redis.
* **System Rescue Strategy:** Specializing in tactical system rescue—diagnosing deep concurrency faults, resolving persistent production deadlocks, and stabilizing mission-critical data paths.

## Engineering Stories

A résumé can tell you where I've worked and which technologies I've used. These stories offer a little more insight into how I approach engineering: recognizing problems, questioning assumptions, finding practical solutions, and occasionally building something simply because I think there's a better way.

### 1. Rethinking Online Advertising: The Interactive Banner

**Wall Street On Demand | Prototype**

In the early days of the commercial web, banner advertising was becoming increasingly common. I anticipated that advertising would become an important part of the web's business model, but I also thought conventional banner ads were annoying: passive, intrusive, and offering very little reason for anyone to interact with them.

I experimented with a different approach: make the advertisement entertaining.

I created a playable video poker game that fit within standard banner-ad dimensions. It included company branding, a destination link, sound effects, and a user-controlled mute button.

The idea was to turn an advertisement into something visitors might actually choose to interact with, rather than something they simply learned to ignore.

It was a prototype rather than a deployed advertising product, but it reflected an idea I still believe in: good technology should engage people and improve their experience, not just compete for their attention.

### 2. Solving the WorldScope Scaling Problem

**Wall Street On Demand | Production Database Architecture**

In 2001, I built the WorldScope database, containing company balance sheets and quote information for thousands of companies across multiple stock exchanges. The data was integrated into financial reports for Charles Schwab. I also built a separate database for the launch of Schwab Japan.

SQL Server 6.5 presented a significant limitation: the entire WorldScope dataset could not practically reside on a single server.

Rather than treat that limitation as a dead end, I devised an ID-based data-distribution architecture that divided the data across multiple SQL Server instances.

I researched the distribution of WorldScope IDs, examined the associated data volumes, and designed the divisions manually to balance the actual storage requirements—not simply the number of records.

The result was a multi-server architecture that allowed the system to handle a dataset that exceeded the practical capacity of a single server.

This was an independently conceived approach now recognized as database sharding. I didn't know the term at the time; I simply needed to solve the problem in front of me.

### 3. Tat-too: Telemetry Analysis Tool

**Ball Aerospace | Six-Month Contract**

My primary project at Ball Aerospace was Tat-too (Telemetry Analysis Tool, Version 2), a web-based tool for exploring and visualizing telemetry data.

The goal was flexibility: the tool could retrieve data from different databases and tables and generate charts and graphs without requiring a custom visualization for every dataset. Features included moving averages and other analytical capabilities.

At the time, implementing this kind of flexible, interactive visualization in a browser was considerably more challenging than it is today. The available JavaScript charting tools were much more limited.

I also contributed to a smaller piece of testing software associated with the James Webb Space Telescope (JWST).

The Ball engagement was a six-month contract. The work needed to be completed, documented, and handed off within that period. That meant building something useful while also making sure the next people responsible for it could understand and maintain it.

### 4. Creating a Language for Automated Document Generation

**Moore-Wallace / RR Donnelly | Production Software**

A significant part of the business involved generating documents containing information drawn from live data sources. I developed a solution that made this process more flexible and standardized.

I designed a proprietary XML markup language, which allowed database fields and tables to be incorporated into PDF documents. I also built the PDF generation engine using Apache FOP and created technical documentation to support consistent development and maintenance.

The work was more than a document-generation utility. It helped establish a repeatable way to transform structured business data into finished documents.

The project also took place in an ISO 9001 quality-management environment, where documentation and standardized processes were important parts of the engineering work.

### 5. Rethinking Hand Washing

**Independent Engineering Project | In Progress**

The COVID pandemic brought renewed attention to hand hygiene, but it also highlighted something I'd observed in other environments: people don't always wash their hands correctly, even when they know they should.

Having worked in food service and clean-room environments, I understood the importance of proper hand washing. I also recognized that many existing approaches didn't adequately account for human behavior and the realities of everyday use.

I began designing a hand-washing machine around a different principle: make correct hand washing easy and natural, without getting in people's way or slowing them down.

The challenge isn't simply to automate a sequence of actions. It's to create something that accommodates how people actually behave while helping them do something important correctly.

The machine is nearing completion. This project brings together mechanical design, electronics, automation, and my broader engineering philosophy: technology should work around people, not expect people to work around technology.

### 6. Clipboard Electronics: Technology from the Ground Up

**Technical Education, Experimentation & Practical Engineering | YouTube**

*Clipboard Electronics* is my YouTube channel, where I explore technology through hands-on projects, practical demonstrations, and detailed technical explanations.

The subjects span a broad range of disciplines, including digital electronics, microcontrollers, embedded systems, programming, radio technology, RF analysis, and practical project development.

Some videos dive deeply into the underlying technology. For example, I demonstrate how microcontroller timers work at the hardware level, progressing from clock signals and binary logic through prescalers, registers, and direct hardware configuration in C++. Others focus on practical applications, such as programming Baofeng radios, using a TinySA spectrum analyzer to investigate radio transmissions, organizing complex projects, or helping beginners choose components when learning Arduino.

What ties these subjects together is my interest in understanding how technology works, from its fundamental building blocks to its practical applications.

I enjoy sharing that knowledge. Explaining a complicated subject clearly requires more than knowing which buttons to press or which library to use; it requires understanding the underlying principles well enough to make them understandable to someone else.

The channel is also an extension of my approach to mentoring and engineering: experiment, investigate, understand, and share what you've learned.

<details>
  <summary><strong>📺 View all 22 Clipboard Electronics tutorials</strong></summary>

  <ol>
    <li><a href="https://youtu.be/W0PRDd4JXcg?si=kURHOdkawSU2mGff">Clipboard Electronics: ATTiny Timers Hardware Deep Dive</a></li>
    <li><a href="https://youtu.be/Zp9Vt3NSAtw?si=prLrrC6kkiOiQ0zP">Clipboard Electronics: Retrocomputer (6502/Z80) Clock Hardware</a></li>
    <li><a href="https://youtu.be/FVDanliUgPU?si=lSCd5dBWt1gIGhux">Clipboard Electronics: ATTiny Programming Tutorial</a></li>
    <li><a href="https://youtu.be/ftwlYMzEjeA?si=3d5kXS_dpfTTE1GZ">Clipboard Electronics: Baofeng Programming with CHIRP (UV-5R and BF-F8HP)</a></li>
    <li><a href="https://youtu.be/Rl5jaN8dRDk?si=tiXt7jF7IWLTU0MM">Clipboard Electronics: Make IC Labels Readable</a></li>
    <li><a href="https://youtu.be/XXtXHj8_XNc?si=etV3paJLccY-cJEp">Clipboard Electronics: Arduino LED Control and PWM Basics</a></li>
    <li><a href="https://youtu.be/mg-hmzTL0d0?si=cGOQlpwAi52vZLu7">Clipboard Electronics: Arduino Basic Supplies List</a></li>
    <li><a href="https://youtu.be/grLyHi-wfoo?si=p0yVPZoxLfLnfDCk">Clipboard Electronics: Arduino Projects Basics</a></li>
    <li><a href="https://youtu.be/ScGuF6fwPgg?si=F-tWhLlkHov7zyVr">Clipboard Electronics: Arduino High Temperature Kiln Alarm Prototype</a></li>
    <li><a href="https://youtu.be/ZwvjVlGbkSI?si=vToH2e9ywz8rd8M0">Clipboard Electronics: JYETech DSO150 Pocket Oscilloscope Tips</a></li>
    <li><a href="https://youtu.be/zjhpEm7OONc?si=4iqiZf3m6Wua1qXB">Clipboard Electronics: SparkFun JYETech Oscilloscope Kit Build</a></li>
    <li><a href="https://youtu.be/1avjTKbksww?si=8JNzybkp8XA9ZIcA">Arduino LSM303 Demo</a></li>
    <li><a href="https://youtu.be/pf4qosqpv3A?si=6crSGfCv_NBcUc1v">Clipboard Electronics: RadioShack Arduino Starter Kit Review</a></li>
    <li><a href="https://youtu.be/3VZgaJBrZD8?si=JjVIb825nfCX0ML5">Clipboard Electronics: Arduino State Machines &amp; BlinkWithoutDelay</a></li>
    <li><a href="https://youtu.be/h_GXhJeCDD0?si=mTyCu4LyObhsvHRD">Radio Shack Tri-color LED Strips How-to</a></li>
    <li><a href="https://youtu.be/LmVm9zcSXic?si=bTiil9uiachviLZ3">Clipboard Electronics: Arduino Micro Setup &amp; First Program</a></li>
    <li><a href="https://youtu.be/9NC2IGVWUew?si=15HJj1ASGQVNkgSf">All About LEDs for RC Night Flying</a></li>
    <li><a href="https://youtu.be/_QplIxvqtUo?si=QSVvTjaib-nuh5FA">Clipboard Electronics: Make a Better DIY TV Antenna Than Commercial Ones</a></li>
    <li><a href="https://youtu.be/_HGx4vAeLTs?si=IobX2kI6nnsjr_UW">Clipboard Electronics: Petoi Bittle Review (for Developers!)</a></li>
    <li><a href="https://youtu.be/tQ2Rx9XR_EQ?si=EY8_Ee30pE_prrG_">Clipboard Electronics: Hysteresis</a></li>
    <li><a href="https://youtube.com/shorts/k11hTlnqZyA?si=uSprMRbeM5Mv3hDv">Clipboard Electronics: TinySA Police Chase Tracking</a></li>
    <li><a href="https://youtu.be/fW_Xutk9BxU">Clipboard Electronics: Petoi Bittle-X Time-lapse Build</a></li>
  </ol>
</details>


---

### A Common Thread

These projects span different industries and technologies, but they share a common approach.

I look for the problem behind the problem. I question whether the existing approach is actually the best one. I distinguish between what is impossible, what is impractical, and what is merely difficult. Then I work toward a solution that makes sense in the real world.

**I build technology around people, not people around technology.**
