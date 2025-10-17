<!-- index.md -->

<style>
  .nav-buttons {
    margin-bottom: 1.5rem;
  }
  .nav-buttons a {
    display: inline-block;
    background-color: #15A9BA;
    color: white;
    padding: 0.5rem 1rem;
    margin-right: 0.5rem;
    text-decoration: none;
    border-radius: 4px;
    font-weight: bold;
  }
  .nav-buttons a:hover {
    background-color: #0f7f89;
  }
  
  /* color all level-1 headings red, level-2 blue, level-3 green */
  h1 { color: #15A9BA; }
  h2 { color: #15A9BA; }
  h3 { color: #1C538E; }
</style>

<div class="nav-buttons">
  <a href="#description">Description</a>
  <a href="#call-for-presentations">Call for Presentations</a>
  <a href="#key-dates">Key Dates</a>
  <a href="#organizers">Organizers</a>
  <a href="#agenda-materials">Agenda & Materials</a>
</div>

![Arch4Health Logo](arch4health-logo3.png){: width="700px" }

<h3 style="color: #E48158;font-style: italic;">
  A half-day workshop exploring the key computational challenges in health-related applications <br> 
  and the vital role of computer architecture in overcoming them to advance healthcare
</h3>

**18th (Saturday) October 2025, Seoul, Korea**  
**In conjunction with [the 58th IEEE/ACM International Symposium on Microarchitecture (MICRO 2025)](https://microarch.org/micro58/)**

## Workshop Description {#description}

**<span style="color: #E48158;">Opportunities</span>.** Recent biotechnological advances enable high-throughput, low-cost, and accurate biological data generation (e.g., using genome sequencing, multimodal medical imaging, continuous wearable sensing). This wealth of data enables unique opportunities for advancing healthcare. These opportunities include, but are not limited to, precision medicine, bedside personalized care, discovering early warning signs of communicable diseases, continuous physiological tracking, and enhanced diagnostic capabilities.

**<span style="color: #E48158;">Challenges</span>.** Despite these opportunities, efficiently analyzing large-scale biological data poses significant challenges for conventional computing systems. These systems often cannot keep up with the high-throughput rate at which data is generated, and they face additional constraints related to energy efficiency, scalability, privacy, and security. High-throughput processing is particularly crucial in clinical settings, where real-time data processing can significantly impact patient outcomes by improving both response times in time-critical scenarios as well as the decision-making processes for therapeutic schemes. Therefore, to facilitate the wide adoption of recent advances in healthcare, there is a need to optimize the computing systems to enable high-performance, energy-efficient, low-cost, private, and secure analysis of biological data.

**<span style="color: #E48158;">Architecture for Health</span>.** This workshop will focus on identifying key computational challenges in health-related applications and discussing how computer architects can contribute to advancing healthcare by addressing these challenges. First, we will provide invited talks and keynotes that summarize (i) a series of research in computing system designs for healthcare applications and (ii) new trends and bottlenecks in data-intensive healthcare applications. Second, we will invite researchers to submit their ongoing work on these topics.

**<span style="color: #E48158;">Fostering Diverse and Cross-Disciplinary Discussions</span>.** Since cross-disciplinary discussions are crucial for better identifying challenges in real-world health-related applications, we aim to foster open discussions and cooperation between researchers with diverse backgrounds (i.e., from both computer architecture and health sciences communities, industry, and academia).

**Time & Location:** October 18th, from 01:00 PM (KST) to 05:00 PM (KST) at Lotte Hotel Seoul (Room: Charlotte).

## Call for Presentations {#call-for-presentations}

This workshop consists of talks on the general topic of computing system designs for healthcare applications and new trends and bottlenecks in data-intensive healthcare applications. There are a limited number of slots for talks. If you are interested in delivering a talk on related topics, **please submit your talk's title and extended abstract via <a href="https://forms.gle/ozKpsox1LT2vt9aP7">this Google Form</a>**. You may either paste the abstract directly into the form or upload a two-page PDF prepared in any standard conference template. Each submission must include the talk title, all authors' names, and their affiliations.

We invite abstract submissions related to (but not limited to) the following topics:

- Computational Biology
  - Genomics
  - Metagenomics
  - Gene editing
  - Drug Design and Discovery
  - Proteomics
  - Other Areas in Precision Medicine
- Neuroscience
  - Brain-Machine Interfaces
  - Prosthetics
- Wearable Systems for Health
- Medical robotics
  - Surgery
  - Haptics
- Mental Health
- Medical Imaging
  - Brain scans
  - Radiology
  - Single-Cell Analysis
- Agent-Based Simulations
- Medical Privacy
- Bio-Sensors

## Key Dates {#key-dates}

- **Extended Abstract Submission Deadline:** 12 September 2025
- **Notification:** 21 September 2025
- **Workshop Date:** 18th (Saturday) October 2025

## Organizers {#organizers}

<style>
  .organizers { 
    display: flex; 
    flex-direction: column; 
    gap: 2rem; 
  }
  .organizer {
    display: flex;
    align-items: flex-start;       /* keep photo & bio top-aligned */
  }
  .organizer .photo-name {
    width: 120px;                  /* FIXED WIDTH so all bios start at same x */
    text-align: center;
    margin-right: 1.5rem;
  }
  .organizer .photo-name img {
    width: 120px;
    height: auto;
    border-radius: 8px;
    display: block;
    margin-bottom: 0.5rem;
  }
  .organizer .photo-name p {
    margin: 0;
    font-weight: bold;
  }
  .organizer .bio {
    flex: 1;
  }
  .organizer .bio p {
    margin: 0.25rem 0;             /* spacing between bio paragraphs */
  }
  .organizer .bio p:first-child {
    margin-top: 0;                 /* flush top margin */
  }
</style>

<div class="organizers">

  <div class="organizer">
    <div class="photo-name">
      <img src="{{ 'nika_pic.jpeg' | relative_url }}" alt="Nika Mansouri Ghiasi">
      <p><a href="https://sites.google.com/view/nikamansourighiasi/" style="color: inherit; text-decoration: none;">Nika Mansouri Ghiasi</a></p>
    </div>
    <div class="bio">
      <p>Email: <a href="mailto:nika.mansourighiasi@safari.ethz.ch">nika.mansourighiasi@safari.ethz.ch</a></p>
      <p>Nika Mansouri Ghiasi is a PhD student in the SAFARI Research Group at ETH Zurich, advised by Professor Onur Mutlu. Her research interests are in computer architecture and computational biology, focusing on 1) storage systems, large-scale bioinformatics applications, and their interactions, and 2) emerging technologies such as ultra-dense 3D integrated systems. She is interested in designing high-performance, energy-efficient, and low-cost systems that facilitate the widespread adoption of data-intensive applications needed in healthcare and precision medicine. For more information, please see her website: <a href="https://bit.ly/nikamgh">bit.ly/nikamgh</a>.</p>
    </div>
  </div>

  <div class="organizer">
    <div class="photo-name">
      <img src="{{ 'konstantina_pic.jpeg' | relative_url }}" alt="Dr. Konstantina Koliogeorgi">
      <p><a href="https://ihpcs.ethz.ch/people/person-detail.MzQ0MTU2.TGlzdC8zOTQxLDc2NTU1MzE0Mg==.html" style="color: inherit; text-decoration: none;">Dr. Konstantina Koliogeorgi</a></p>
    </div>
    <div class="bio">
      <p>Email: <a href="mailto:kkoliogeorgi@ethz.ch">kkoliogeorgi@ethz.ch</a></p>
      <p>Konstantina Koliogeorgi is a Postdoctoral Researcher at the SAFARI Research Group at ETH Zurich, led by Prof. Onur Mutlu. She received her Ph.D. degree in Electrical and Computer Engineering in 2023 at National Technical University of Athens (NTUA), advised by Prof. Dimitrios Soudris. Her research interests are in the field of computer systems and architecture, heterogeneous computing, and hardware acceleration. Her research has focused on hardware-software co-design, efficient high-level synthesis optimization, and design space exploration, targeting mainly genome analysis applications.</p>
    </div>
  </div>

  <div class="organizer">
    <div class="photo-name">
      <img src="{{ 'onur_pic.jpeg' | relative_url }}" alt="Prof. Onur Mutlu">
      <p><a href="https://people.inf.ethz.ch/omutlu/" style="color: inherit; text-decoration: none;">Professor Onur Mutlu</a></p>
    </div>
    <div class="bio">
      <p>Email: <a href="mailto:omutlu@gmail.com">omutlu@gmail.com</a></p>
      <p>Onur Mutlu is a Professor of Computer Science at ETH Zurich. He previously held the William D. and Nancy W. Strecker Early Career Professorship at Carnegie Mellon University. His research interests are in computer architecture, computing systems, hardware security, memory & storage systems, and bioinformatics, with a major focus on designing fundamentally energy-efficient, high-performance, and robust computing systems. He started the Computer Architecture Group at Microsoft Research (2006-2009), and held product, research, and visiting positions at Intel Corporation, Advanced Micro Devices, VMware, Google, and Stanford University. He received various honors for his research, including the 2025 IEEE Computer Society Harry H. Goode Memorial Award “for seminal contributions to computer architecture research and practice, especially in memory systems.” He is an ACM Fellow, IEEE Fellow, and an elected member of the Academy of Europe. He enjoys teaching, mentoring, and enabling & democratizing access to high-quality research and education. He has supervised 24 PhD graduates, many of whom received major dissertation awards, 15 postdoctoral trainees, and more than 60 Master’s and Bachelor’s students. His computer architecture and digital logic design course lectures and materials are freely available on YouTube, and his research group makes a wide variety of artifacts freely available online. For more information, please see his webpage at <a href="https://people.inf.ethz.ch/omutlu/">https://people.inf.ethz.ch/omutlu/</a>.</p>
    </div>
  </div>

</div>

## Agenda & Workshop Materials {#agenda-materials}

<style>
  /* agenda table: same look as before */
  table.agenda { width:100%; border-collapse: collapse; table-layout: fixed; }
  table.agenda th, table.agenda td { border: 2px solid #bbb; padding: 8px; text-align:left; }
  table.agenda thead { background:#15A9BB; color:#000; }  /* updated turquoise */

  /* ensure normal text color in body */
  table.agenda tbody { color:#000; }

  /* zebra striping, applied only to session tbodies */
  table.agenda tbody.session tr:nth-child(odd)  { background:#ffffff; }
  table.agenda tbody.session tr:nth-child(even) { background:#f2f8fa; }

  /* coffee break row keeps its own background and doesn't affect striping */
  table.agenda tbody.break tr td {
    background:#d8ebe7; font-weight:700; text-align:center;
  }
</style>

<table class="agenda">
  <colgroup>
    <col style="width:12%;">
    <col style="width:32%;">  <!-- wider speaker column -->
    <col style="width:18%;">
    <col style="width:38%;">
  </colgroup>

  <thead>
    <tr>
      <th>Time</th>
      <th>Speaker</th>
      <th>Domain</th>
      <th>Title</th>
    </tr>
  </thead>

  <!-- BEFORE BREAK (keeps the beauty + borders) -->
  <tbody class="session">
    <tr>
      <td>1:00–1:05</td>
      <td>Nika Mansouri Ghiasi<br>Dr. Konstantina Koliogeorgi<br>Prof. Onur Mutlu</td>
      <td>—</td>
      <td>Welcome</td>
    </tr>
    <tr>
      <td>1:05–1:25</td>
      <td>Prof. Hunjun Lee<br><i>(Hanyang University)</i></td>
      <td><b>Brain-Computer Interfaces</b></td>
      <td>Pathfinding Future BCI System with Full-Stack Design Space Exploration</td>
    </tr>
    <tr>
      <td>1:25–1:45</td>
      <td>Prof. Lizy John<br><i>(UT Austin)</i></td>
      <td><b>Wearables</b></td>
      <td>Energy-Efficient Neural Networks for Medical Wearables</td>
    </tr>
    <tr>
      <td>1:45–2:05</td>
      <td>Prof. Sang-Woo Jun<br><i>(UC Irvine)</i></td>
      <td><b>Genomics</b></td>
      <td>Addressing the Data Movement Overhead of Genomic Accelerators</td>
    </tr>
    <tr>
      <td>2:05–2:25</td>
      <td>Dr. Hasindu Gamaarachchi<br><i>(UNSW)</i></td>
      <td><b>Real-Time Genomics</b></td>
      <td>Algorithms &amp; Architectures for Long Read Sequence Analysis</td>
    </tr>
    <tr>
      <td>2:25–2:45</td>
      <td>Elton Shih<br><i>(Cornell University)</i></td>
      <td><b>Real-Time Genomics</b></td>
      <td>Towards an Edge Algorithm–Hardware Co-Design Framework for Adaptive Sampling</td>
    </tr>
    <tr>
      <td>2:45–3:05</td>
      <td>Seunghee Han<br><i>(KAIST)</i></td>
      <td><b>Genomics &amp; Proteomics</b></td>
      <td>From Genomics to Proteomics: Architectural Solutions for Memory-Intensive Health Applications</td>
    </tr>
  </tbody>

  <!-- BREAK (isolated so striping restarts cleanly) -->
  <tbody class="break">
    <tr><td colspan="4">3:05–3:30 — Coffee Break </td></tr>
  </tbody>

  <!-- AFTER BREAK (same borders + zebra, no washed-out rows) -->
  <tbody class="session">
    <tr>
      <td>3:30–3:50</td>
      <td>Nika Mansouri Ghiasi<br><i>(ETH Zurich)</i></td>
      <td><b>(Meta)Genomics</b></td>
      <td>Storage-Centric Systems for Genomics and Metagenomics</td>
    </tr>
    <tr>
      <td>3:50–4:10</td>
      <td>Dr. Konstantina Koliogeorgi<br><i>(ETH Zurich)</i></td>
      <td><b>Genomics</b></td>
      <td>MARS: Processing-In-Memory Acceleration of Raw Signal Genome Analysis Inside the Storage Subsystem</td>
    </tr>
    <tr>
      <td>4:10–4:30</td>
      <td>Dr. Noelia Oliete Escuin<br><i>(BSC)</i></td>
      <td><b>Genomics</b></td>
      <td>A Tightly-Coupled Hardware Accelerator for Fast Pattern Exact-Matching in Genome Analysis</td>
    </tr>
    <tr>
      <td>4:30–4:50</td>
      <td>Dr. Lukas Breitwieser<br><i>(CERN)</i></td>
      <td><b>Agent-Based Simulation</b></td>
      <td>Current State and Future Directions in Scalable Agent-Based Simulation with TeraAgent</td>
    </tr>
  </tbody>
</table>



<h3 style="color:#1C538E;">📽️ Livestream</h3>
<p>
  For those who can't attend in person, you can join us online via the 
  <strong>📽️ Livestream</strong>:
  <a href="https://www.youtube.com/live/lTc_gQzFNJI" target="_blank" style="color:#15A9BA; text-decoration:none;">
    https://www.youtube.com/live/lTc_gQzFNJI
  </a>
</p>

<div style="margin-top: 1rem; display: flex; justify-content: center;">
  <iframe width="720" height="405"
          src="https://www.youtube.com/embed/lTc_gQzFNJI"
          title="Arch4Health Livestream"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen
          style="border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.15);">
  </iframe>
</div>


