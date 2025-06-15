# Bacopa vs Adderall – Cognitive Performance Simulation

This project simulates how memory performance changes over one year under three cognitive enhancement strategies:

- 💊 **Adderall** (taken 1x, 2x, or 5x per week)
- 🌿 **Bacopa Monnieri** (taken daily)
- ⚪ **No intervention** (baseline mental fluctuation)

The simulation helps visualize how short-term spikes (Adderall) compare to long-term gains (Bacopa) using AI-style cognitive modeling.

---

## 🧠 What's Being Modeled

- **Memory Score (0–100):** A synthetic metric representing working memory, attention span, and learning capacity
- **Time:** Simulated daily for 365 days (1 year)
- **Noise:** Gaussian randomness added to reflect day-to-day mental variability

---

## 🔬 Methodology

We used Python to simulate three conditions:

| Agent           | Simulation Logic                                  |
|----------------|---------------------------------------------------|
| Bacopa (daily) | Linear rise in memory score → plateau after 90 days |
| Adderall       | Spikes on dose days only → decays with tolerance |
| Baseline       | No intervention → fluctuates with noise only     |

All memory curves are built using rule-based logic (symbolic AI), not machine learning.

---

## 📊 Output

- Three visual comparisons (IG-ready square format):
  - Adderall 5x/week vs Bacopa
  - Adderall 2x/week vs Bacopa
  - Adderall 1x/week vs Bacopa
- Clean plots with baseline, consistent formatting, and high-legibility for social or scientific content

---

## 🤖 Why It’s AI-Based

This project applies **symbolic AI techniques** — using hand-coded rules to simulate cognitive state changes over time. This is commonly used in cognitive architectures like ACT-R and SOAR. While it doesn't use neural networks, it reflects the same AI foundations that power decision-making models in neuroscience.

---


## 📚 Sources

- Stough, C. et al. (2001). *Psychopharmacology*, 156(4), 481–484.
- Calabrese, C. et al. (2008). *J. of Alternative and Complementary Medicine*, 14(6), 707–713.
- Ilieva, I. et al. (2013). *Journal of Cognitive Neuroscience*, 27(6), 1069–1089.
- Weyandt, L. L. et al. (2018). *Experimental and Clinical Psychopharmacology*, 26(5), 384–394.

---

## 📲 Follow & Explore

- Instagram: [@cognitive.engineer](https://www.instagram.com/cognitive.engineer)
- Project Hub: [cognitiveengineer.carrd.co](https://cognitiveengineer.carrd.co)

Pull requests and forks welcome.
