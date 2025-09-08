# Bab 1: Basic Thinking

### Bagian 6: Base-Rate Neglect

Tahun 1982, seorang mahasiswa kedokteran bernama Steve tiba di emergency room dengan gejala yang concerning: demam tinggi, sakit kepala berat, kaku leher, dan ruam merah di sekujur tubuh.

Dokter jaga melihat kombinasi gejala ini dan langsung think: **meningitis bacterial**—infeksi serius yang butuh treatment segera atau bisa fatal.

Tapi ketika lumbar puncture dilakukan, hasilnya mengejutkan: **viral meningitis**—kondisi yang jauh lebih ringan dan self-limiting.

Mengapa dokter berpengalaman bisa salah diagnosis?

Karena dia focus pada gejala-gejala yang dramatic dan mengabaikan satu fakta fundamental: **viral meningitis 10x lebih common daripada bacterial meningitis.**

Dokter tersebut jadi korban **base-rate neglect**—kecenderungan mengabaikan informasi frekuensi dasar (base rate) dan terlalu focus pada informasi spesifik yang lebih salient.

---

## The Math That Our Brain Ignores

Base rate adalah **prior probability**—kemungkinan sesuatu terjadi berdasarkan data historis atau populasi umum, sebelum kita consider informasi spesifik lainnya.

Dalam kasus meningitis:
- **Base rate viral meningitis**: ~90% dari semua kasus
- **Base rate bacterial meningitis**: ~10% dari semua kasus

Meskipun gejala Steve seemed classic untuk bacterial meningitis, **prior probability tetap overwhelmingly favor viral meningitis.**

Tapi otak kita tidak wired untuk bayesian thinking. Kita lebih impressed oleh vivid symptoms ketimbang boring statistics.

---

## The Taxi Cab Problem: Classic Dunning-Kruger

Kahneman dan Tversky mendemonstrasikan base-rate neglect dengan famous "taxi cab problem":

*Sebuah taksi terlibat kecelakaan hit-and-run di malam hari. Di kota ini ada dua perusahaan taksi:*
- *Green Cab Co: 85% dari semua taksi*
- *Blue Cab Co: 15% dari semua taksi*

*Seorang saksi identify taksi tersebut sebagai Blue Cab. Court test menunjukkan saksi ini 80% akurat dalam mengidentifikasi warna taksi di kondisi malam hari.*

*Berapa probabilitas bahwa taksi yang terlibat kecelakaan benar-benar Blue Cab?*

**Jawaban intuitive kebanyakan orang: 80%** (sama dengan akurasi saksi)

**Jawaban mathematically correct: 41%**

Mengapa? Karena kebanyakan orang mengabaikan base rate (85% taksi adalah Green) dan hanya focus pada testimony accuracy (80%).

**Correct reasoning:**
- Ada 100 taksi: 85 Green, 15 Blue
- Jika Blue Cab yang kecelakaan: saksi identify correctly 80% (12 cases), salah 20% (3 cases)
- Jika Green Cab yang kecelakaan: saksi identify correctly 80% (68 cases), salah 20% (17 cases)
- Total cases di mana saksi bilang "Blue": 12 + 17 = 29
- Cases di mana actual Blue dan saksi bilang Blue: 12
- **Probability = 12/29 = 41%**

**Base rate matters more than most people realize.**

---

## Why Our Brain Neglects Base Rates

### 1. Representative Heuristic
Otak kita judge probability berdasarkan seberapa "representative" something appears. Vivid symptoms lebih representative daripada abstract statistics.

### 2. Causal Reasoning Bias
Kita focus pada causal chains (symptoms → diagnosis) dan ignore statistical priors (disease frequency in population).

### 3. Narrative Fallacy
Stories dan specific cases lebih memorable dan compelling ketimbang base rate data. We think in narratives, not numbers.

### 4. Availability Heuristic Combo
Recent atau memorable cases make rare events seem more common, distorting our internal base rate estimates.

---

## Base-Rate Neglect dalam Medical Diagnosis

Medical field adalah goldmine untuk base-rate neglect disasters:

### The Mammogram Problem
- **Base rate**: Breast cancer affects ~1% women aged 50
- **Test accuracy**: Mammogram 80% sensitive, 90% specific
- **Question**: Jika mammogram positive, berapa probability cancer?

**Common answer**: 80%
**Correct answer**: ~7%

**Why?** Di population 1000 women:
- 10 actually have cancer: 8 test positive, 2 test negative
- 990 don't have cancer: 99 false positives, 891 true negatives
- **Total positive tests**: 8 + 99 = 107
- **Actual cancer among positives**: 8/107 = 7%

**Most positive mammograms are false alarms** karena cancer base rate sangat rendah.

### Drug Testing False Positives
- **Base rate drug use** di certain population: 5%
- **Test accuracy**: 95% (both sensitivity dan specificity)

Jika seseorang test positive, probability dia actual drug user hanya ~50%, bukan 95%. **Half of positive results are false positives.**

### Rare Disease Diagnosis
Doctors sering over-diagnose rare diseases karena focus pada symptoms dan neglect base rates. **Zebra diagnoses** (rare conditions) get more attention than **horse diagnoses** (common conditions), meskipun horses much more likely.

---

## Base-Rate Neglect dalam Security dan Law Enforcement

### Airport Security Theater
Post-9/11 security measures designed untuk detect terrorists, tapi base rate terrorism attempts sangat rendah (~1 dalam 10 million). **Most security alerts are false positives**, creating massive waste dan inconvenience untuk prevent extremely rare events.

### Predictive Policing Bias
Algoritma predict "high-crime areas" berdasarkan past arrests, tapi ini ignore base rates dan create feedback loops. More police presence → more arrests → higher "predicted crime" → even more police presence.

### DNA Bukti Misinterpretation
Juries sering misinterpret DNA match probabilities karena ignore base rates. **1 dalam 100,000 match** sounds conclusive, tapi if you test million people, you'll get 10 matches by chance alone.

---

## Business dan Finance: Base-Rate Neglect Costs Money

### Startup Success Delusion
Entrepreneurs focus pada their specific advantages dan ignore base rates: **90% startups fail**. Passion dan specific planning dapat't override fundamental statistics.

### Stock Picking Hubris
Active fund managers think they can beat market berdasarkan analysis dan skill, ignoring base rate: **85% of active funds underperform index funds** over 10-year periods.

### Hiring Biases
HR focus pada impressive resumes atau interview performance, ignoring base rates untuk job success dari different backgrounds atau universities. **Past performance base rates are better predictors than individual impressions.**

### Insurance Mispricing
Insurance companies sometimes misprice risks karena focus pada recent events (availability heuristic) ketimbang long-term base rates, leading to under-reserving dan financial disasters.

---

## Tech Industry: Base-Rate Neglect di Scale

### A/B Testing Misinterpretation
Teams focus pada statistical significance tanpa considering base rates untuk conversion improvements. **Most A/B tests fail to move metrics**, regardless of initial promising signals.

### Bug Prioritization
Engineers focus pada dramatic crashes dan ignore common, boring bugs yang affect more users. **High-visibility bugs get attention disproportionate to their actual impact.**

### Feature Success Rates
Product teams overestimate success probability untuk new features, ignoring base rates: **majority of new features have little to no impact** on key metrics.

### Technical Talent Assessment
Focus pada impressive projects atau prestigious company backgrounds, ignoring base rates untuk actual job performance across different backgrounds.

---

## The Prosecutor's Fallacy: Legal System's Base-Rate Problem

### Classic Contoh
DNA evidence shows "1 dalam 1 million match probability." Prosecutor argues: "There's only 1 dalam 1 million chance defendant is innocent."

**Fallacy**: Ignore base rate likelihood that any random person could be the perpetrator. In city dengan 1 million people, **you'd expect 1 random match even if defendant is innocent.**

### Eyewitness Identification
Focus pada witness confidence ("I'm 90% sure") while ignoring base rates untuk eyewitness accuracy (**eyewitness misidentification causes 75% of wrongful convictions**).

### Statistical Bukti Misinterpretation
Juries focus pada impressive-sounding statistics tanpa understanding base rates, leading to systematic biases dalam conviction rates.

---

## Era Digital: Base-Rate Neglect Goes Viral

### Social Media Outrage
Viral stories about rare events (kidnapping, vaccine reactions, police misconduct) create perception these events are common, ignoring actual base rates. **Availability cascade amplifies base-rate neglect.**

### Fake News Detection
People focus pada source credibility atau emotional content, ignoring base rates: **most viral stories contain inaccuracies atau misleading information**.

### Algorithm Bias Amplification
ML algorithms trained on biased data perpetuate base-rate neglect patterns, creating systematic discrimination yang scale globally.

---

## 7 Strategies untuk Fighting Base-Rate Neglect

### 1. Always Ask: "What's the Base Rate?"
Sebelum make any probability judgment, cari tahu historical frequency. **Prior probability should anchor your reasoning.**

### 2. Use Natural Frequencies
Instead of percentages, think dalam natural numbers:
- "1% false positive rate" → "10 false alarms per 1000 tests"
- Easier untuk brain process dan less prone to errors

### 3. Consider the Reference Class
Define population atau category yang relevant. Base rate untuk "startups" berbeda dengan base rate untuk "SaaS startups dengan experienced founders."

### 4. Update Incrementally (Bayesian Thinking)
Start dengan base rate, then update berdasarkan new information. **Don't ignore priors, integrate them.**

### 5. Seek Diverse Data Sources
One vivid case study ≠ representative base rate. Collect systematic data across broader populations atau time periods.

### 6. Use Checklists dan Decision Frameworks
Formalize decision processes untuk include base rate considerations, preventing emotional atau intuitive shortcuts.

### 7. Practice Frequency Thinking
Train yourself untuk think dalam frequencies ketimbang probabilities. "How often does this actually happen?" vs "What's the chance this happens?"

---

## Studi Kasus: Base-Rate Neglect dalam COVID-19

### Early Overreaction untuk Rare Complications
Media focus pada rare severe cases dalam young, healthy individuals while ignoring base rates (severe COVID is predominantly elderly dengan comorbidities). Led to misproportionate fear dalam low-risk populations.

### Vaccine Side Effects Misperception
Focus pada rare adverse events (blood clots, myocarditis) while ignoring base rates untuk these conditions in general population dan much higher rates dari COVID itself.

### Testing Strategi Errors
Mass testing dalam low-prevalence populations generated many false positives, tapi public health officials focused pada test accuracy rather than base rate implications.

### School Closure Decisions
Focus pada possibility of school transmission while ignoring base rates untuk pediatric severe disease dan educational/social costs dari closure.

**Pelajaran**: Dramatic cases capture attention, but base rates determine optimal policy.

---

## Why This Matters: Base-Rate Neglect as Cognitive Pollution

Base-rate neglect isn't just individual cognitive bias—it's **systematic misallocation of attention, resources, dan policy focus.**

We over-invest dalam preventing rare but vivid risks while under-investing dalam addressing common but boring problems. We create policies berdasarkan dramatic exceptions rather than statistical norms.

**Hasil: Suboptimal decisions at individual, organizational, dan societal levels.**

Understanding base rates adalah foundation untuk **rational risk assessment** dan **evidence-based decision making.**

---

## The Paradox of Expertise

Interesting paradox: **domain expertise can increase base-rate neglect.**

Medical specialists see more rare diseases, distorting their internal base rate estimates. Investment professionals see more market anomalies, making them overestimate active management opportunities.

**Expertise provides better pattern recognition but worse probability calibration.**

**Solution**: Combine domain expertise dengan systematic base rate analysis.

---

## Latihan Praktis: Base-Rate Calibration

**This week, practice base-rate thinking:**

1. **Next medical concern**: Research actual prevalence rates before assuming worst-case scenarios.

2. **Business decisions**: For any new initiative, find base rates for similar projects' success rates.

3. **News consumption**: When reading about dramatic events, look up how common these events actually are.

4. **Personal fears**: List your biggest worries. Research base rates. Are you worried about the right things?

5. **Probability estimates**: Make 10 predictions tentang future events. Look up historical base rates. How does this change your confidence?

**Remember**: Your specific situation might be special, tapi it's probably not as special as you think. **Start with base rates, then adjust for your specific circumstances—not the other way around.**