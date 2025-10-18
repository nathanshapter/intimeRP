# 🕒 InTimeRP — Public Development Roadmap
_Last updated: {{10/18/2025}}_

Welcome to the official roadmap for **InTimeRP**, the time-based roleplay experience set in a controlled city economy where every second counts.  
This roadmap tracks our progress across all **four main development phases**, from Alpha to full global rollout.

---

## 🧩 Phase 1 — Alpha Launch (Core Systems)

> Goal: make the world playable and fun, even with low population.

### ✅ Major Systems (must be near-perfect)
- [ ] **Core Time Mechanic** — ticking timer, death at 0, medic revival (5 min)
- [ ] **Prison System** — jail, mining for time, breakout alerts
- [ ] **Police & Government Roles** — mayor election, police hierarchy, guard duty
- [ ] **Apartment & Real Estate System** — player-owned housing + rent timers

### 🧱 Basic Implementations
- [ ] **Economy & Jobs** — basic earnings + spending
- [ ] **Server Infrastructure** — stable VPS, FastDL, proxy, DDoS protection
- [ ] **Events** — mayor-triggered only
- [ ] **Monetization** — Supporter / Supporter+ tiers
- [ ] **Transaction Logging** — track time trades for 2–4 weeks

### 💰 Core Mechanics
- Players die when out of time (unless revived by medic within 5 min)
- Medics revive using their own time (cost 5–10 min)
- Time bank taxes: any stored time > 24 h taxed 5 %/day → City dirty time
- Mayor prints limited time (monitored)
- Dirty time → laundered via USB (1 h = 10 min process)

### 🚧 In Progress
- [ ] Prison breakout alert radius + disguise cooldowns
- [ ] Police promotion system based on guard hours
- [ ] Apartment ownership tracking
- [ ] Transaction history web dashboard

---

## 🧾 Phase 2 — Systems Expansion

> Goal: introduce deeper social, criminal, and economic loops.

### 🏛️ New Mechanics
- [ ] **Taxes on banked time** — optional compliance; refusal triggers warrant
- [ ] **NPC Quest Framework** — 30 + quest givers with timed respawns
- [ ] **Expanded Crime System** — new contraband, laundering tiers, bribes
- [ ] **Courier-Dependent Drug Role** — dealers rely on couriers for profit
- [ ] **Player Reputation / Heat System**

### ⚙️ Refinements
- [ ] Better laundering scaling (larger USB = longer time)
- [ ] Repeat offender tracking → longer prison sentences
- [ ] Mayor printing logs → public accountability
- [ ] Enhanced player database → court integration prep

---

## 🧠 Phase 3 — Progression & Factions

> Goal: give long-term purpose and power structures to loyal players.

### 🧍 Player Progression
- [ ] Experience, reputation, skill trees
- [ ] Lifetime statistics and legacy carryover ("will" system)

### 🏢 Factions
- [ ] Create/join factions after 6 months of continuous subscription  
- [ ] Internal ranks + joint time vault
- [ ] Political factions may influence city policy

### 🛫 Cross-Server Expansion
- [ ] Inter-city travel between regional servers  
- [ ] Local laws & culture differences per region

---

## 🌆 Phase 4 — Custom Map & Global Rollout

> Goal: polish, identity, and global connection.

### 🏙️ Map + World
- [ ] Custom map replacing rp_bangclaw base  
- [ ] Unique neighborhoods per class/tier  
- [ ] Lore-based NPCs and posters

### 💡 Systems
- [ ] Surveillance system (optional comeback)  
- [ ] Full court & lawyer system  
- [ ] City-wide broadcast events

### 💸 Crowdfunding
- [ ] Kickstarter or equivalent for custom map + marketing  
- [ ] Founders’ physical rewards and statues (no visible tags in-game)

---

## 🧰 Infrastructure & Tools

| Component | Status | Notes |
|------------|---------|-------|
| VPS (GTHost Montreal) | ✅ Online | Hosts server & backend |
| Proxy / DDoS protection | ✅ Configured | Using VPS reverse-proxy |
| FastDL server | ⚙️ Planned | Will host custom assets |
| GitHub repo + Actions | ⚙️ Next Step | For live roadmap |
| Discord integration | ✅ | Mayor vetting, faction roles |
| Patreon tiers | ✅ | Supporter / Supporter + / Founder |
| Website hosting | ✅ | nobswitch.dev |

---

## 🐞 Known Issues
- [ ] Alt-account detection tuning
- [ ] Prison mining abuse mitigation
- [ ] Mayor printing abuse loopholes
- [ ] Police overtime tracking bug

---

## 🗺️ Next Steps
1. Finish apartment ownership system  
2. Add transaction log viewer  
3. Connect GitHub → VPS auto-deploy for roadmap  
4. Begin NPC system prototyping  

---

## 🖼️ (Future Images)
To embed screenshots or diagrams later:
```markdown
![Example Prison Flow](images/prison_flow.png)
![Phase Timeline](images/timeline.png)
