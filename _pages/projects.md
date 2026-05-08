---
layout: single
permalink: /projects/
title: "Projects"
author_profile: true
classes: wide
---

<style>
.projects-subtitle {
  color: #aaa;
  margin-bottom: 2em;
  font-size: 0.95em;
}

.section-label {
  font-size: 0.7em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 2px;
  color: #aaa;
  border-bottom: 2px solid #eaeaea;
  display: inline-block;
  padding-bottom: 4px;
  margin-bottom: 1.2em;
}

.project-card {
  border: 1px solid rgba(255,255,255,0.1);
  border-radius: 8px;
  padding: 28px 32px;
  margin-bottom: 1.5em;
  background: rgba(255,255,255,0.03);
  transition: background 0.2s, border-color 0.2s;
}
.project-card:hover {
  background: rgba(255,255,255,0.06);
  border-color: rgba(255,255,255,0.2);
}

.project-card-header {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 6px;
  flex-wrap: wrap;
}
.project-logo {
  width: 40px;
  height: 40px;
  object-fit: contain;
  flex-shrink: 0;
}
.project-title {
  font-size: 1.2em;
  font-weight: 700;
  margin: 0;
}
.project-title a {
  color: inherit;
  text-decoration: none;
}
.project-title a:hover {
  color: #0092ca;
}
.live-badge {
  font-size: 0.65em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 1px;
  color: #fff;
  background: #0092ca;
  padding: 2px 9px;
  border-radius: 3px;
  vertical-align: middle;
}
.project-tagline {
  font-size: 0.88em;
  color: #aaa;
  font-style: italic;
  margin-bottom: 0.8em;
}
.project-desc {
  font-size: 0.9em;
  color: #ccc;
  line-height: 1.75;
  margin-bottom: 1em;
}

.signals-grid,
.families-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 8px;
  margin-bottom: 1em;
}
.families-grid .family-item:last-child {
  grid-column: span 3;
}
.signal-item,
.family-item {
  padding: 8px 12px;
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(255,255,255,0.08);
  border-left-width: 3px;
  border-radius: 5px;
  display: flex;
  flex-direction: column;
  gap: 3px;
}
.signal-header,
.family-header {
  display: flex;
  align-items: center;
  gap: 9px;
}
.signal-header > i,
.family-header > i {
  font-size: 14px;
  flex-shrink: 0;
}
.signal-name,
.family-name {
  font-size: 0.78em;
  font-weight: 600;
  color: #ddd;
}
.signal-desc,
.family-desc {
  font-size: 0.72em;
  color: #888;
  line-height: 1.4;
}

.tags {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
  margin-bottom: 1em;
}
.tag {
  font-size: 0.75em;
  font-weight: 600;
  padding: 3px 11px;
  border-radius: 20px;
  white-space: nowrap;
}
.tag-blue  { background: rgba(0,146,202,0.15); color: #5bc4f5; }
.tag-green { background: rgba(46,160,67,0.15);  color: #56d364; }
.tag-orange{ background: rgba(210,105,30,0.18); color: #f0a04b; }

.card-links {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}
.btn-link {
  font-size: 0.82em;
  font-weight: 600;
  color: #0092ca;
  text-decoration: none;
  padding: 6px 16px;
  border: 1.5px solid #0092ca;
  border-radius: 5px;
  transition: all 0.2s;
  display: inline-block;
}
.btn-link:hover {
  background: #0092ca;
  color: #fff;
}
.btn-link.primary {
  background: #0092ca;
  color: #fff;
}
.btn-link.primary:hover {
  background: #007aaa;
  border-color: #007aaa;
}

.combo-section {
  margin-bottom: 1em;
}
.combo-section-label {
  font-size: 0.75em;
  color: #777;
  margin-bottom: 10px;
  font-style: italic;
}
.combo-arrow {
  color: #888;
  font-size: 0.85em;
  align-self: center;
  padding: 0 2px;
}
.playing-card.wildcard {
  background: #e8e8e8;
  border: 1.5px dashed #999;
}

.card-combos {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}
.combo {
  display: flex;
  flex-direction: column;
  gap: 5px;
}
.combo-label {
  font-size: 0.68em;
  color: #888;
  text-align: center;
}
.cards {
  display: flex;
  gap: 3px;
}
.playing-card {
  background: #f0f0f0;
  border-radius: 4px;
  padding: 4px 7px;
  font-size: 0.8em;
  font-weight: 700;
  line-height: 1.2;
  min-width: 28px;
  text-align: center;
  color: #222;
  box-shadow: 0 1px 3px rgba(0,0,0,0.4);
}
.playing-card.red { color: #c0392b; }

@media (max-width: 600px) {
  .signals-grid { grid-template-columns: repeat(2, 1fr); }
  .project-card { padding: 20px; }
}
</style>

<p class="projects-subtitle">Personal projects across statistics, machine learning, AI, and software engineering.</p>

<div class="section-label">Featured</div>

<div class="project-card">
  <div class="project-card-header">
    <img src="/assets/images/projects/trialchemy.svg" alt="Trialchemy logo" class="project-logo">
    <h2 class="project-title"><a href="https://www.trialchemy.app" target="_blank">Trialchemy ↗</a></h2>
    <span class="live-badge">Live · Open Source</span>
  </div>
  <p class="project-tagline">The workbench for designing, simulating, and comparing clinical trials.</p>
  <p class="project-desc">
    Trialchemy brings 20 trial designs across 7 families into a single workbench, from Phase I dose finding to treatment selection. The cross-design view lets researchers compare methodologies under the same scientific objective, making it more than a calculator.
  </p>
  <div class="families-grid">
    <div class="family-item" style="border-left-color:#8b5cf6"><div class="family-header"><i class="fas fa-vial" style="color:#8b5cf6"></i><span class="family-name">Phase I Dose Finding</span></div><span class="family-desc">3+3 · BOIN · mTPI-2 · CRM · TITE-CRM</span></div>
    <div class="family-item" style="border-left-color:#f97316"><div class="family-header"><i class="fas fa-sliders-h" style="color:#f97316"></i><span class="family-name">Dose Optimization</span></div><span class="family-desc">BOIN-ET · Keyboard OBD · Project Optimus</span></div>
    <div class="family-item" style="border-left-color:#f43f5e"><div class="family-header"><i class="fas fa-bullseye" style="color:#f43f5e"></i><span class="family-name">Phase II Single Arm</span></div><span class="family-desc">Simon's · A'Hern</span></div>
    <div class="family-item" style="border-left-color:#06b6d4"><div class="family-header"><i class="fas fa-chart-line" style="color:#06b6d4"></i><span class="family-name">Phase II Dose Response</span></div><span class="family-desc">MCP-Mod · Emax</span></div>
    <div class="family-item" style="border-left-color:#3b82f6"><div class="family-header"><i class="fas fa-chart-bar" style="color:#3b82f6"></i><span class="family-name">Phase III Two-Arm</span></div><span class="family-desc">Binary · Continuous · Survival</span></div>
    <div class="family-item" style="border-left-color:#f59e0b"><div class="family-header"><i class="fas fa-balance-scale" style="color:#f59e0b"></i><span class="family-name">Non-Inferiority</span></div><span class="family-desc">Binary · Continuous · Survival</span></div>
    <div class="family-item" style="border-left-color:#10b981"><div class="family-header"><i class="fas fa-trophy" style="color:#10b981"></i><span class="family-name">Treatment Selection</span></div><span class="family-desc">Sargent-Goldberg · Multi-arm GS · Adaptive</span></div>
  </div>
  <div class="tags">
    <span class="tag tag-green">Next.js</span>
    <span class="tag tag-green">TypeScript</span>
    <span class="tag tag-green">FastAPI</span>
    <span class="tag tag-green">R</span>
    <span class="tag tag-green">Supabase</span>
    <span class="tag tag-blue">Clinical Trial Design</span>
    <span class="tag tag-blue">Trial Simulation</span>
    <span class="tag tag-orange">20 Designs</span>
  </div>
  <div class="card-links">
    <a href="https://www.trialchemy.app" target="_blank" class="btn-link primary">Visit Trialchemy ↗</a>
    <a href="https://github.com/jiaguo1000/trialchemy" target="_blank" class="btn-link">GitHub ↗</a>
  </div>
</div>

<div class="section-label">Side Projects</div>

<div class="project-card">
  <div class="project-card-header">
    <img src="/assets/images/projects/eggbomb.png" alt="EggBomb logo" class="project-logo">
    <h2 class="project-title"><a href="https://eggbomb.duckdns.org" target="_blank">EggBomb (掼蛋) ↗</a></h2>
    <span class="live-badge">Live · Multiplayer</span>
  </div>
  <p class="project-tagline">A multiplayer web implementation of the Chinese card game Guan Dan.</p>
  <p class="project-desc">
    掼蛋 is a 4-player team card game where partners race to shed cards before the opposing team, with valid combinations ranging from singles to multi-card bombs.
    Empty seats are filled by an AI bot powered by ISMCTS, an algorithm designed for games with imperfect information.
  </p>
  <div class="combo-section">
    <p class="combo-section-label">Example Combinations</p>
    <div class="card-combos">
      <div class="combo">
        <div class="cards">
          <span class="playing-card">A♠</span>
        </div>
        <div class="combo-label">Single</div>
      </div>
      <div class="combo">
        <div class="cards">
          <span class="playing-card">K♠</span>
          <span class="playing-card red">K♥</span>
        </div>
        <div class="combo-label">Pair</div>
      </div>
      <div class="combo">
        <div class="cards">
          <span class="playing-card">5♠</span>
          <span class="playing-card red">6♥</span>
          <span class="playing-card red">7♦</span>
          <span class="playing-card">8♣</span>
          <span class="playing-card">9♠</span>
        </div>
        <div class="combo-label">Straight</div>
      </div>
      <div class="combo">
        <div class="cards">
          <span class="playing-card">7♠</span>
          <span class="playing-card red">7♥</span>
          <span class="playing-card">7♣</span>
          <span class="playing-card red">3♦</span>
          <span class="playing-card">3♣</span>
        </div>
        <div class="combo-label">Full House</div>
      </div>
      <div class="combo">
        <div class="cards">
          <span class="playing-card">J♠</span>
          <span class="playing-card red">J♥</span>
          <span class="playing-card">J♣</span>
          <span class="playing-card red">J♦</span>
        </div>
        <div class="combo-label">Quad</div>
      </div>
      <div class="combo">
        <div class="cards">
          <span class="playing-card red">5♥</span>
          <span class="playing-card red">6♥</span>
          <span class="playing-card red">7♥</span>
          <span class="playing-card red">8♥</span>
          <span class="playing-card red">9♥</span>
        </div>
        <div class="combo-label">Straight Flush</div>
      </div>
      <div class="combo">
        <div class="cards">
          <span class="playing-card red" style="border: 2.5px solid #c8922a;">7♥</span>
          <span class="combo-arrow">→</span>
          <span class="playing-card wildcard">?♠</span>
          <span class="playing-card wildcard red">?♥</span>
          <span class="playing-card wildcard">?♣</span>
          <span class="playing-card wildcard red">?♦</span>
        </div>
        <div class="combo-label">Wildcard (current rank)</div>
      </div>
    </div>
  </div>
  <div class="tags">
    <span class="tag tag-green">React</span>
    <span class="tag tag-green">Node.js</span>
    <span class="tag tag-green">Socket.io</span>
    <span class="tag tag-green">TypeScript</span>
    <span class="tag tag-blue">ISMCTS</span>
    <span class="tag tag-blue">Real-Time Multiplayer</span>
  </div>
  <div class="card-links">
    <a href="https://eggbomb.duckdns.org" target="_blank" class="btn-link primary">Play Online ↗</a>
    <a href="https://github.com/jiaguo1000/eggbomb" target="_blank" class="btn-link">GitHub ↗</a>
  </div>
</div>
