---
theme: seriph
background: https://source.unsplash.com/featured/?gaming,education
class: text-center
highlighter: shiki
lineNumbers: true
info: |
  ## DGBL: Design & Implementation
  Stage 2 keynote for the Serious Games course.
drawings:
  persist: false
transition: slide-left
title: DGBL - From Problem to Serious Game
---

# DGBL: From Problem to Serious Game
## Stage 2: Design, Implement, or Iterate

A methodological guide for creating digital game-based learning experiences.

---
layout: section
---

# Current State of the Art
Recapping progress and setting our next goals.

---

# Stage 1 Milestone Cleared

<div class="grid grid-cols-2 gap-10 items-center mt-10">
  <div class="text-center">
    <div class="text-8xl font-bold text-lime-400">Baseline</div>
    <div class="text-xl mt-2 text-gray-400">Successfully Established</div>
  </div>
  <div class="text-left text-lg">
    <ul>
      <li class="mb-4"><strong>Research problem defined:</strong> All groups have successfully identified their core DGBL question.</li>
      <li class="mb-4"><strong>Mandatory requirement met:</strong> You are now cleared to move into the active phase.</li>
      <li class="mb-4"><strong>The focus now:</strong> The quality of your process (whether designing a prototype or deepening research) will define your final outcome.</li>
    </ul>
  </div>
</div>

---

# The Fork in the Road (Stage 2)

<div class="mt-8 p-5 bg-gray-800 rounded border-l-4 border-lime-400 text-left">
  For Stage 2, your group must choose one of two distinct paths:
</div>

<div class="grid grid-cols-2 gap-10 mt-8 text-left">
  <div>
    <h3 class="text-lime-400 font-bold mb-2">Path A: The Builder</h3>
    <p>Move forward with <strong>Design & Implementation</strong>. You will map your research to a playable prototype.</p>
  </div>
  <div>
    <h3 class="text-blue-400 font-bold mb-2">Path B: The Researcher</h3>
    <p>Not ready to build? <strong>Iterate on Stage 1</strong>. Deepen your context, read more papers, and test hypotheses without committing to a prototype.</p>
  </div>
</div>

---
layout: section
---

# Path A: Design Methodology
The bridge between research and gameplay.

---

# The LM-GM Framework
### Learning Mechanics - Game Mechanics (Lim et al.)

<div class="grid grid-cols-2 gap-10 mt-10 text-left">
  <div>
    <h4 class="text-lime-400 text-xl font-bold">Learning Mechanics (LM)</h4>
    <p class="mb-4">What the player must learn (e.g., Identify, Classify, Prioritize).</p>
    
    <h4 class="text-blue-400 text-xl font-bold">Game Mechanics (GM)</h4>
    <p>What the player actually does in the game (e.g., Collect, Dodge, Combine).</p>
  </div>
  <div class="border-2 border-dashed border-gray-500 p-6 rounded flex items-center bg-gray-900/50">
    <p class="italic text-gray-300 text-lg">"The pedagogical goal (LM) must strictly map to a play action (GM) that makes the learning invisible yet highly effective."</p>
  </div>
</div>

---

# Quick Design Checklist
Before coding anything, your team must answer these 3 questions:

<div class="mt-10 space-y-8 text-left text-lg">
  <p><strong>1. What is the core loop?</strong> <br> <span class="text-gray-400">If the player spends 80% of their time jumping, the learning must happen during the jump.</span></p>
  <p><strong>2. Is there a direct connection?</strong> <br> <span class="text-gray-400">Does this specific game mechanic help answer our Stage 1 research question?</span></p>
  <p><strong>3. Is there "noise"?</strong> <br> <span class="text-gray-400">If a game element neither entertains nor teaches, cut it out immediately.</span></p>
</div>

---

# Tips & Implementation Tools

<div class="grid grid-cols-2 gap-10 mt-10 text-left">
  <div>
    <h3 class="text-lime-400 mb-3 font-bold">Narrative Focus (No-Code)</h3>
    <p><strong>Twine:</strong> Ideal for research involving decision-making, ethics, or clinical case studies. Exports directly to HTML.</p>
  </div>
  <div>
    <h3 class="text-blue-400 mb-3 font-bold">Action Focus (Low-Code)</h3>
    <p><strong>GDevelop:</strong> Ideal for spatial logic, resource collection, or 2D reflexes. Visual programming without typing code.</p>
  </div>
</div>

<div class="mt-10 p-5 bg-gray-800 rounded border border-gray-600">
  <strong>Golden Rule:</strong> Control your scope. A 3-minute functional prototype that measures your variables is infinitely better than an unfinished epic.
</div>

---
layout: section
---

# Path B: The Researcher
Deepening the context.

---

# Iterating on Stage 1 (Path B)
### For those who choose not to build a prototype.

<div class="mt-8 text-left text-lg space-y-6">
  <p><i class="fas fa-book text-lime-400 mr-2"></i> <strong>Expanded Literature Review:</strong> Gather and analyze significantly more academic papers related to your problem.</p>
  <p><i class="fas fa-flask text-lime-400 mr-2"></i> <strong>Hypothesis Testing:</strong> Design theoretical frameworks or surveys to test your hypotheses without the need for a digital build.</p>
  <p><i class="fas fa-bullseye text-lime-400 mr-2"></i> <strong>Refining the Context:</strong> Redefine the target audience and variables with much higher academic rigor.</p>
  <p class="text-gray-400 text-base italic mt-4">*Note: While highly valuable, choosing not to implement a prototype caps the final grading ceiling slightly compared to a full game deployment.*</p>
</div>

---

# Stage 3: The Academic Report
### The "Journal Submission" Process

<div class="mt-8 text-left text-lg space-y-4">
  <p><strong>📝 Journal Format:</strong> Your final research report will be styled as an academic paper submission.</p>
  <p><strong>🤝 Peer Review:</strong> You will act as peer reviewers for the reports (and games) of other groups.</p>
  <p><strong>🧑‍🏫 Teacher's Role:</strong> I will act as the Editor-in-Chief, validating your reviews.</p>
</div>

<div class="mt-10 p-5 border border-dashed border-lime-400 rounded">
  <strong>The Roadmap:</strong> 
  <br> • Stage 1 Iteration Only ➔ Solid foundation (up to 4.0).
  <br> • Functional Prototype (Path A) ➔ Higher ceiling (up to 4.5).
  <br> • Outstanding Paper + Peer Review ➔ Academic Excellence (4.5 - 5.0).
</div>

---
layout: center
---

# Additional Resources & References

For groups looking to explore accessibility and inclusion:
<br><br>
**The TEGA Toolkit:** A validated framework for inclusive game design, focusing on cognitive accessibility, representation, and flexibility. 
<br>*(Documentation available on the virtual campus).*

---
