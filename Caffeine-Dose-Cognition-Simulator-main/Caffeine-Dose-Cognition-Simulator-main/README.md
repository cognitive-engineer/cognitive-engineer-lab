# ☕ Caffeine Dose vs. Cognitive Performance — AI Simulation

This project uses a machine learning model to simulate how different doses of caffeine affect short-term cognitive performance. Inspired by peer-reviewed neuroscience literature, the simulation captures:

- The **inverted-U effect** of caffeine on cognition  
- The impact of **tolerance buildup over time**  
- The effects of **cycled vs. daily use**
- The predicted **boost in cognitive score** relative to baseline

---

## Features Simulated

- **Dose (mg):** 0–600+
- **Habitual Use:** Binary (yes/no) and dynamic tolerance adaptation
- **Baseline Arousal:** Modeled as a continuous factor (0.3–0.9)
- **Sleep Hours:** Sleep-deprivation vs. recovery effect
- **Reaction Time and Working Memory** also generated synthetically

---

## Key Findings

- **200 mg caffeine** appears to provide the optimal cognitive boost  
- Performance **drops after 300 mg** due to overstimulation  
- **Cycled use slows** tolerance but doesn’t eliminate it  
- High doses still outperform baseline in short term — but decay rapidly with habitual use

---

## Files

- `caffeine_simulation.ipynb`: Full simulation code (Colab-ready)
- `synthetic_caffeine_cognition_dataset.csv`: Generated dataset
- `dose_response_plot.png`: Dose vs. cognition visual
- `slide_deck.txt`: Text content for Instagram or presentation slides

---

## Based On:

- Nehlig (2010) — *Is Caffeine a Cognitive Enhancer?*  
- Lieberman (2002) — *Effects of Caffeine, Sleep Loss, and Stress*  
- Haskell (2005) — *Cognitive and Mood Improvements of Caffeine*

---

## Next Steps

- Add personalized tolerance tracking
- Incorporate L-theanine as a co-modifier
- Simulate withdrawal and recovery phases
- Port to a Streamlit web app

---

## References

1. Nehlig, A. (2010). *Is caffeine a cognitive enhancer?* Journal of Alzheimer's Disease, 20(s1), S85–S94.  
   [https://doi.org/10.3233/JAD-2010-091315](https://doi.org/10.3233/JAD-2010-091315)

2. Lieberman, H. R., Tharion, W. J., Shukitt-Hale, B., Speckman, K. L., & Tulley, R. (2002).  
   *Effects of caffeine, sleep loss, and stress on cognitive performance and mood during U.S. Navy SEAL training.* Psychopharmacology, 164(3), 250–261.  
   [https://doi.org/10.1007/s00213-002-1217-9](https://doi.org/10.1007/s00213-002-1217-9)

3. Haskell, C. F., Kennedy, D. O., Wesnes, K. A., & Scholey, A. B. (2005).  
   *Cognitive and mood improvements of caffeine in habitual consumers and habitual non-consumers of caffeine.* Psychopharmacology, 179(4), 813–825.  
   [https://doi.org/10.1007/s00213-004-2104-3](https://doi.org/10.1007/s00213-004-2104-3)

4. Temple, J. L., Bernard, C., Lipshultz, S. E., Czachor, J. D., Westphal, J. A., & Mestre, M. A. (2017).  
   *The safety of ingested caffeine: A comprehensive review.* Frontiers in Psychiatry, 8, 80.  
   [https://doi.org/10.3389/fpsyt.2017.00080](https://doi.org/10.3389/fpsyt.2017.00080)

---

## Author
Daivarsi Malik  
[Instagram: @cognitive.engineer](https://instagram.com/cognitive.engineer)  
PhD-track Biomedical Engineer | Applied AI | Cognitive Neuroscience Modeling  

---

