<!-- ============================================================
     GitHub Profile README — ShifatSahariar
     NOTE: GitHub sanitizes all style="" attributes. Layout below
     uses only what GitHub actually renders: tables, align=, <img>,
     <details>, and badges.
     Replace every [GAP → ...] before publishing.
     ============================================================ -->

<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1200&color=F7DD0C&center=true&vCenter=true&width=700&lines=AI+for+Software+Engineering+Researcher;Does+AI-generated+code+actually+work%3F;Mutation+Testing+%C2%B7+Behavioral+Embeddings;Compiler+%26+Runtime+Validation" alt="Typing SVG" />
</a>

### PhD Researcher · Università della Svizzera italiana 🇨🇭



`behavioral embeddings` · `grammar-based generation` · `coding-agent evaluation`

<br>

<a href="https://www.linkedin.com/in/shifatsahariar/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="28" /></a>
<a href="https://www.youtube.com/@ShifatSahariar"><img src="https://img.shields.io/badge/The_Test_Oracle-FF0000?style=for-the-badge&logo=youtube&logoColor=white" height="28" /></a>
<a href="mailto:shifat.sahariar@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" height="28" /></a>
<a href="[GAP → Google Drive public CV link]"><img src="https://img.shields.io/badge/📄_Download_CV-2E2E2E?style=for-the-badge" height="28" /></a>
<a href="[GAP → scholar profile]"><img src="https://img.shields.io/badge/Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" height="28" /></a>

</div>

---

## 🧭 The one-liner

> A test suite can pass while the code is wrong. Now that AI writes a growing share of our code,
> that silent failure has become the field's most expensive problem.
> My research learns representations of program **behavior** — supervised by mutation analysis —
> to catch exactly those failures, validated on the hardest targets: **compilers and language runtimes**.

<div align="center">

`Evaluation & Reliability of AI-Generated Code` &nbsp;•&nbsp; `Test Oracles` &nbsp;•&nbsp; `Empirical SE`

</div>

---

## 🔬 Research

<table>
<thead>
<tr>
<th align="left">Paper</th>
<th align="center">Venue</th>
<th align="center">Type</th>
<th align="center">Year</th>
<th align="center">Artifact</th>
</tr>
</thead>
<tbody>

<tr>
<td><b><a href="[GAP → link]">History-Driven Patch Ranking</a></b><br><sub>Ranking automated-repair patches using repository history</sub></td>
<td align="center"><img src="https://img.shields.io/badge/[GAP_→_venue]-6E7B8B?style=flat-square" /></td>
<td align="center"><img src="https://img.shields.io/badge/Full_Paper-4CAF50?style=flat-square" /></td>
<td align="center"><code>[GAP]</code></td>
<td align="center">—</td>
</tr>

<!-- <tr>
<td><b>FAULTLENS</b><br><sub>Mutation-supervised contrastive embeddings for fault-revealing test prioritization</sub></td>
<td align="center"><img src="https://img.shields.io/badge/ISSTA_/_FSE-C2185B?style=flat-square" /></td>
<td align="center"><img src="https://img.shields.io/badge/In_Preparation-9E9E9E?style=flat-square" /></td>
<td align="center"><code>2027</code></td>
<td align="center">🔒</td>
</tr> -->

<!-- <tr>
<td><b>OracleBench</b><br><sub>Behavior-grounded re-scoring of coding-agent patches</sub></td>
<td align="center"><img src="https://img.shields.io/badge/Benchmark_Track-0A74DA?style=flat-square" /></td>
<td align="center"><img src="https://img.shields.io/badge/In_Progress-FF9800?style=flat-square" /></td>
<td align="center"><code>2027</code></td>
<td align="center">🚧</td>
</tr> -->

</tbody>
</table>

<div align="center">
<sub><b>Legend</b> &nbsp;·&nbsp; 🔒 held until submission &nbsp;·&nbsp; 🚧 building in public &nbsp;·&nbsp; 📦 artifact released</sub>
</div>

<details>
<summary><b>📖 Research narrative — click to expand</b></summary>
<br>

Modern software fails silently: it passes its tests while behaving incorrectly. My thesis develops
**behavior-aware testing** — using mutation analysis as a *supervision signal* to learn embeddings of
program behavior, then using those embeddings to (1) detect faults tests miss, (2) prioritize
fault-revealing tests, and (3) judge the correctness of generated code.

Validation targets are deliberately the hardest correctness domain available: **compilers and language
runtimes**, where "wrong but passing" is both common and consequential.

**Research threads:** mutation testing · contrastive representation learning · grammar-based test
generation · differential & metamorphic testing · coding-agent benchmark validity

</details>

---

## 🛠️ Projects

<table>
<thead>
<tr>
<th align="left">Project</th>
<th align="left">What it does</th>
<th align="left">Stack</th>
<th align="center">Domain</th>
<th align="center">Repo</th>
</tr>
</thead>
<tbody>

<!-- <tr>
<td><b>OracleBench</b></td>
<td>Re-scores "solved" coding-agent patches with behavior-grounded oracles — exposing how much leaderboard performance is illusory</td>
<td><code>Python</code> <code>PyTorch</code> <code>Docker</code></td>
<td align="center"><img src="https://img.shields.io/badge/AI_Evaluation-0A74DA?style=flat-square" /></td>
<td align="center"><a href="[GAP → repo]">→</a></td>
</tr> -->

<!-- <tr>
<td><b>FAULTLENS</b></td>
<td>Learns behavioral embeddings from mutants to rank tests by fault-revealing power</td>
<td><code>Python</code> <code>PyTorch</code> <code>PIT</code></td>
<td align="center"><img src="https://img.shields.io/badge/Software_Testing-4CAF50?style=flat-square" /></td>
<td align="center">🔒</td>
</tr>

<tr>
<td><b>ClusGram</b></td>
<td>Grammar-based test generation with behavioral clustering for interpreter/compiler targets</td>
<td><code>Python</code> <code>ANTLR</code></td>
<td align="center"><img src="https://img.shields.io/badge/Compiler_Testing-A569BD?style=flat-square" /></td>
<td align="center">🔒</td>
</tr>

<tr>
<td><b>BehaviorGate</b></td>
<td>CI gate that flags AI-generated patches whose behavior diverges from intent — even when tests pass</td>
<td><code>Python</code> <code>GitHub Actions</code></td>
<td align="center"><img src="https://img.shields.io/badge/Developer_Tools-FF9800?style=flat-square" /></td>
<td align="center">🚧</td>
</tr> -->

</tbody>
</table>

---

## 🎓 Teaching

<table>
<thead>
<tr>
<th align="left">Course</th>
<th align="center">Level</th>
<th align="center">Term</th>
<th align="center">Evaluation</th>
</tr>
</thead>
<tbody>
<tr>
<td><b>Introduction to Programming</b> <sub>(Python)</sub></td>
<td align="center"><code>MSc</code></td>
<td align="center">Autumn 25/26</td>
<td align="center"><img src="https://img.shields.io/badge/9.3_/_10-4CAF50?style=flat-square" /></td>
</tr>
<tr>
<td><b>Machine Learning</b></td>
<td align="center"><code>BSc</code></td>
<td align="center">[GAP]</td>
<td align="center"><img src="https://img.shields.io/badge/[GAP]-9E9E9E?style=flat-square" /></td>
</tr>
<tr>
<td><b>Data Structures &amp; Algorithms</b></td>
<td align="center"><code>BSc · MSc</code></td>
<td align="center">Autumn 24/25</td>
<td align="center"><img src="https://img.shields.io/badge/[GAP]-9E9E9E?style=flat-square" /></td>
</tr>
<tr>
<td><b>Advanced Java Programming</b></td>
<td align="center"><code>MSc</code></td>
<td align="center">Spring 24/25</td>
<td align="center"><img src="https://img.shields.io/badge/[GAP]-9E9E9E?style=flat-square" /></td>
</tr>
</tbody>
</table>

<sub>Teaching Assistant · Università della Svizzera italiana · scores are official student course evaluations.</sub>

---

## 💼 Experience

```text
2024 — now   PhD Researcher            USI Lugano, Switzerland
             Evaluation & reliability of AI-generated code; behavior-aware testing.

2023 — 2024  Research Assistant        University of Passau, Germany
             Fault localization & automated program repair (Prof. C. Hammer).

2016 — 2017  Android Developer         BASIS Institute of Technology, Dhaka
             Shipped production apps for industrial clients.
```

<div align="center">
<a href="[GAP → Google Drive public CV link]"><img src="https://img.shields.io/badge/📄_Full_CV-Download_PDF-2E2E2E?style=for-the-badge" /></a>
</div>

---

## 🎙️ The Test Oracle

I explain, clearly and rigorously, **how we test software and whether AI-generated code actually works.**

<table>
<tr>
<td width="33%" align="center"><b>📺 Paper Explainers</b><br><sub>Csmith · EMI · SWE-bench validity</sub></td>
<td width="33%" align="center"><b>🤖 Do AI Agents Actually Work?</b><br><sub>Compounding error · Who grades the homework?</sub></td>
<td width="33%" align="center"><b>✍️ Blog</b><br><sub>Passing tests is a weak oracle</sub></td>
</tr>
</table>

<div align="center">
<a href="https://www.youtube.com/@ShifatSahariar"><img src="https://img.shields.io/badge/Watch-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
<a href="[GAP → blog]"><img src="https://img.shields.io/badge/Read-1A1A1A?style=for-the-badge&logo=hashnode&logoColor=white" /></a>
</div>

---

## 🧰 Toolbox

<div align="center">

**Languages** &nbsp; ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**ML / LLM** &nbsp; ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![LoRA](https://img.shields.io/badge/Fine--tuning_·_LoRA-7952B3?style=flat-square)

**Testing & Analysis** &nbsp; ![Mutation](https://img.shields.io/badge/Mutation_Testing-C2185B?style=flat-square) ![Fuzzing](https://img.shields.io/badge/Grammar--Based_Fuzzing-A569BD?style=flat-square) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Infra** &nbsp; ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/CI-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ShifatSahariar&show_icons=true&hide_border=true&theme=graywhite&hide=stars&custom_title=Building%20in%20public" height="150" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ShifatSahariar&hide_border=true&theme=graywhite" height="150" />

<br><br>

***Currently:*** *finishing a PhD on the reliability of AI-generated code — and looking toward
industry research roles in Switzerland & Europe from late 2027.*

<sub>Open to research chats about test oracles, benchmark validity, and coding-agent evaluation.</sub>

</div>
