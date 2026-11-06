# Breathe Easy

Guided breathing practice for adults with asthma: step-by-step instructions, an animated breathing pacer and a timer, in one simple web page.

**Live app:** https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/

> **Not medical advice.** This app supports, but doesn't replace, prescribed treatment. Keep your reliever inhaler with you. If you ever feel unwell, pause and use your reliever as prescribed. If it doesn't help, get medical help right away. Don't change or reduce your medication because of breathing exercises without talking to your doctor first.

## What it does

- Four guided sessions (belly breathing, pursed-lip breathing, optional breathing control, and a warm-up / walk / cool-down routine) and an information card about inspiratory muscle training.
- A pacer circle with "Breathe In" and "Breathe Out" cues, a countdown, and optional sound and vibration cues for use while walking.
- An "I'm short of breath" button during the guided walk that stops the timer and shows reliever and emergency guidance straight away, with an optional breathing guide.
- Runs entirely in your browser. No account, no tracking, nothing stored or sent anywhere.

## How the exercises were chosen

The exercises come from a review of the research on breathing retraining in adults with asthma, and the instructions in the app follow that review's wording. [Edit this line to say how you prepared the review, for example: "The review was prepared with AI assistance."] The key findings below were checked against the abstracts of the original publications. Statements about how the exercises work that the research does not support were left out.

The research supports breathing exercises as an **add-on** to asthma medication. It does not show that they replace it, and it does not show that they cure asthma. "Evidence-informed" is a fairer description than "proven".

## What the research shows

| Exercise in the app | What the evidence says | Strength of evidence |
|---|---|---|
| **Exercise 1: Belly (diaphragmatic) breathing** | Part of the breathing-exercise programs in the Cochrane review [1]. A UK trial of physiotherapist-taught breathing training improved asthma-specific health status and other patient-centred measures, but not asthma pathophysiology [2]. | Moderate to very low, depending on the outcome |
| **Exercise 2: Pursed-lip breathing** | Lengthens the breath out and creates gentle back-pressure in the airways [5]. Most of the evidence comes from COPD, and asthma-specific trials are limited. | Limited for asthma |
| **Exercise 3: Breathing control (optional)** | In a randomised trial, adults using the Buteyko technique and adults taught breathing and relaxation by a physiotherapist improved by a similar amount. The Buteyko group also reduced their inhaled steroid dose more [3]. The app uses only gentle pauses, not full Buteyko breath-holds. | Low to moderate |
| **Exercise 4: Inspiratory muscle training (optional)** | A Cochrane review of 5 small trials (113 adults) found stronger breathing muscles, but no conclusive evidence of benefit for symptoms, lung function or medication use [4]. It needs a threshold device and professional guidance, so it is optional and the app has no timer for it. | Very low |
| **Warm-up / cool-down** | The American Thoracic Society recommends interval or combination warm-up before planned exercise for all patients with exercise-induced bronchoconstriction (strong recommendation, moderate-quality evidence) [6]. Breathing with the belly during the warm-up applies Exercise 1 and has not been tested on its own. | Moderate for the warm-up itself |

### The main review

The 2020 Cochrane review pooled 22 randomised trials with 2,880 adults who had mild to moderate asthma (14 of the 22 trials studied yoga) [1]:

- **Quality of life** improved at 3 months compared with no breathing exercises (Asthma Quality of Life Questionnaire, +0.42 points, 95% CI 0.17 to 0.68; moderate certainty).
- **Hyperventilation symptoms** were lower at 4 to 6 months (moderate certainty).
- **Lung function**: FEV1 as a percentage of predicted improved (+6.9%), but FEV1 in litres was inconclusive (very low certainty). Other trials and reviews found no reliable improvement in lung function [2][7].
- **Asthma symptoms** (Asthma Control Questionnaire) were inconclusive (low certainty).
- **Side effects** were not assessed.

The authors concluded that breathing exercises *may* have positive effects on quality of life, hyperventilation symptoms and lung function, and rated the certainty of the evidence from moderate to very low. The most consistent benefit is on quality of life, not on lung function.

## How the timings were chosen

The review gave ranges (about 2 to 3 seconds in, 4 to 6 seconds out). The app uses fixed values inside those ranges:

- Exercise 1: 3 seconds in, 5 seconds out.
- Exercise 2: 2 seconds in, 4 seconds out (5 breaths take 30 seconds).
- Exercise 3: 3 seconds in, 4 seconds out, 3 seconds pause (10 cycles).
- Guided walk: 5 minutes of warm-up and 3 minutes of cool-down at 3 seconds in and 5 seconds out. The walking stage has no breathing pace; it is just a timer.

None of these timings has been clinically validated.

## Limitations

- The trials studied adults with mild to moderate asthma treated as outpatients. They say little about severe asthma.
- This app has not been tested in a clinical study.
- Breathing exercises work best when taught and checked by a respiratory physiotherapist or doctor, who can adjust them to the individual.

## Sources

1. Santino TA, Chaves GSS, Freitas DA, Fregonezi GAF, Mendonca KMPP. *Breathing exercises for adults with asthma.* Cochrane Database of Systematic Reviews 2020, Issue 3, CD001277. https://doi.org/10.1002/14651858.CD001277.pub4 (PubMed: https://pubmed.ncbi.nlm.nih.gov/32212422/)
2. Thomas M, McKinley RK, Mellor S, et al. *Breathing exercises for asthma: a randomised controlled trial.* Thorax 2009;64(1):55-61. https://pubmed.ncbi.nlm.nih.gov/19052047/
3. Cowie RL, Conley DP, Underwood MF, Reader PG. *A randomised controlled trial of the Buteyko technique as an adjunct to conventional management of asthma.* Respiratory Medicine 2008;102(5):726-732. https://pubmed.ncbi.nlm.nih.gov/18249107/
4. Silva IS, Fregonezi GAF, Dias FAL, Ribeiro CTD, Guerra RO, Ferreira GMH. *Inspiratory muscle training for asthma.* Cochrane Database of Systematic Reviews 2013, Issue 9, CD003792. https://www.cochrane.org/evidence/CD003792_inspiratory-muscle-training-asthma
5. Nguyen JD, Duong H. *Pursed-lip breathing.* StatPearls. https://www.ncbi.nlm.nih.gov/books/NBK545289/
6. Parsons JP, Hallstrand TS, Mastronarde JG, et al. *An official American Thoracic Society clinical practice guideline: exercise-induced bronchoconstriction.* American Journal of Respiratory and Critical Care Medicine 2013;187(9):1016-1027. https://doi.org/10.1164/rccm.201303-0437ST
7. O'Connor E, Patnode CD, Burda BU, Buckley DI, Whitlock EP. *Breathing exercises and/or retraining techniques in the treatment of asthma: comparative effectiveness.* AHRQ Comparative Effectiveness Review 12-EHC092-EF, 2012. https://pubmed.ncbi.nlm.nih.gov/23101047/

## Editing the app

The whole app is the single file `index.html`. To change the text or colors, edit that file on GitHub (pencil icon) and commit; GitHub Pages republishes it within a minute or two.
