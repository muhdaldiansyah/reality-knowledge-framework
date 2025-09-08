# reality-knowledge-framework

Kerangka Pengetahuan Realitas adalah peta terstruktur lintas disiplin yang merangkum konsep-konsep paling berdampak untuk memahami cara kerja dunia, mempertajam pemikiran, dan membuat keputusan lebih baik. Saya mengembangkan kerangka ini atas dasar informasi yang kian melimpah tapi tidak terintegrasi. RKF memberi panduan untuk fokus pada hal-hal yang paling inti dan menghindari hal-hal yang kurang berarti, menghindari kesalahpahaman yang sering terjadi, dan mengubah pengetahuan menjadi keputusan nyata.

Kerangka ini terdiri atas 5 Bagian, 20 Bab, dan 200 Konsep Inti.

**Bagian I — Fondasi.** Bagian ini menata cara berpikir dasar: bagaimana membedakan klaim yang valid dari sekadar opini, menggunakan logika dan *argument mapping* untuk menyusun argumen yang bersih, lalu menambah “otot” matematis melalui intuisi fungsi, pertumbuhan, matriks/transformasi, dan dimensi. Di sini juga dibahas probabilitas, informasi, serta bagaimana mengkalibrasi keyakinan—agar intuisi angka selaras dengan dunia nyata.

**Bagian II — Kausalitas.** Intinya adalah membaca sebab–akibat dengan benar. Anda belajar kerangka DAG dan *d-separation*, asumsi-identifikasi seperti SUTVA, positivity, dan exchangeability, serta aturan praktis backdoor, front-door, dan instrumen. Bagian ini juga merinci eksperimen (randomisasi, power, *spillovers*, MDE, etika) dan studi observasional (DiD, RDD, propensity score, *negative controls*, sensitivitas) sehingga Anda tahu kapan kesimpulan kausal dapat dipertanggungjawabkan.

**Bagian III — Sistem.** Fokusnya pada perilaku sistem dunia nyata: stok–aliran, umpan balik, keterlambatan, batas pertumbuhan, dan *leverage points*, termasuk jebakan *Goodhart’s Law* saat metrik dijadikan target. Anda menelaah dinamika dan kompleksitas—nonlinearitas, *tipping points*, *power laws*, *heavy-tails*—serta jaringan dan permainan strategis (struktur komunitas, efek jaringan, kompatibilitas insentif, koordinasi). Terakhir, Anda belajar mengelola kendala dan mengoptimalkan keputusan melalui TOC, *Pareto frontier*, *slack & buffers*, dan antifragilitas.

**Bagian IV — Alat & Metode.** Ini bengkel kerjanya: praktik data yang rapi (lineage, *data contracts*, *reproducible workflow*), statistik yang jujur (perbedaan *confidence* vs *credible intervals*, bahaya *p-hacking*, paradoks Simpson), dan pemodelan yang disiplin (hindari *data leakage*, gunakan CV, regularisasi, dan *baseline* yang kuat). Anda juga membangun simulasi untuk mengeksplorasi skenario—Monte Carlo, agen, dinamika sistem, hingga simulasi kontra-faktual berbasis SCM—dan menutupnya dengan komunikasi temuan yang bertanggung jawab lewat *uncertainty visualization/language*, integritas visual, dan alur naratif yang jelas.

**Bagian V — Keputusan & Aksi.** Bagian akhir menerjemahkan pengetahuan menjadi pilihan nyata. Anda memadukan *prospect theory* dengan strategi eksplorasi–eksploitasi dan nilai informasi (EVPI/EVSI) untuk keputusan sekuensial yang tangguh, lalu memprioritaskan pekerjaan lewat RICE, *cost of delay*, dan *complexity budget*. Implementasi diikat dengan metrik pagar pembatas, *pre-mortem*, rencana *rollout/rollback*, dan kesiapan *scaling*, sementara aspek etika–keamanan membahas privasi, risiko *dual-use*, prinsip kehati-hatian, dan *value alignment* agar dampak tetap aman dan bernilai.


## Reality Knowledge Framework - 200 Konsep Inti

**Part I: Foundations (40 Concepts)**

**Chapter 1: How We Know (10)**
1. Standards of Truth
2. Confirmation Bias
3. Availability Heuristic
4. Anchoring Bias
5. Dunning-Kruger Effect
6. Base-Rate Neglect
7. Scientific Method Steps
8. Falsification Principle
9. Null Hypothesis
10. Intellectual Humility

**Chapter 2: Clear Thinking Tools (10)**
11. Deductive Logic
12. Inductive Logic
13. Abductive Reasoning
14. Ad Hominem Fallacy
15. Straw Man Fallacy
16. False Dichotomy
17. Principle of Charity & Steelmanning
18. First Principles Thinking
19. Correlation Fallacy
20. Argument Mapping

**Chapter 3: Mathematical Intuition (10)**
21. Function Concept
22. Linear Growth
23. Exponential Growth
24. Logarithmic Scale
25. Rate of Change
26. Accumulation
27. Vectors
28. Matrix & Transformation
29. Dimensionality
30. Model Limitations

**Chapter 4: Uncertainty & Information (10)**
31. Probability Axioms
32. Conditional Probability
33. Bayes' Theorem
34. Prior vs Posterior
35. Expected Value
36. Risk vs Uncertainty
37. Information Content
38. Entropy Concept
39. Signal vs Noise
40. Probability Calibration

**Part II: Causality (30 Concepts)**

**Chapter 5: Causal Thinking (10)**
41. Collider Bias
42. Causality Definition
43. Front-Door Criterion
44. Counterfactuals, SUTVA, Positivity & Exchangeability
45. Selection Bias
46. Confounding Variables
47. DAG Notation & d-separation
48. Causal Paths
49. Backdoor Paths
50. Instrumental Variables

**Chapter 6: Experiments (10)**
51. Randomization Purpose
52. Control Groups
53. Interference & Spillovers
54. Sample Size Calculation
55. Statistical Power
56. Type I Error
57. Type II Error
58. A/B Test Design
59. Minimum Detectable Effect
60. Ethical Considerations

**Chapter 7: Observational Studies (10)**
61. Natural Experiments
62. Difference-in-Differences
63. Parallel Trends
64. Regression Discontinuity
65. Bandwidth Selection
66. Propensity Score
67. Negative Controls
68. Covariate Balance
69. Sensitivity Analysis
70. Omitted Variable Bias

**Part III: Systems (40 Concepts)**

**Chapter 8: System Fundamentals (10)**
71. Stocks
72. Flows
73. Positive Feedback
74. Negative Feedback
75. Time Delays
76. Growth Limits
77. Tragedy of Commons
78. Success to Successful
79. Goodhart's Law
80. Leverage Points

**Chapter 9: Dynamics & Complexity (10)**
81. Linear Systems
82. Nonlinear Systems
83. Tipping Points
84. Hysteresis
85. Butterfly Effect
86. Power Laws
87. Emergence
88. Self-Organization
89. Phase Transitions
90. Heavy-Tail Events

**Chapter 10: Networks & Games (10)**
91. Network Nodes
92. Network Edges
93. Degree Distribution
94. Network Effects
95. Preferential Attachment
96. Community Structure
97. Nash Equilibrium
98. Prisoner's Dilemma
99. Incentive Compatibility
100. Coordination Games (Stag Hunt, Focal Points)

**Chapter 11: Constraints & Optimization (10)**
101. Bottleneck Identification
102. Theory of Constraints Steps
103. Pareto Frontier
104. Multi-Objective Trade-offs
105. Satisficing
106. Local vs Global Optima
107. Slack & Buffers
108. Convexity
109. Antifragility
110. Barbell Strategy

**Part IV: Tools & Methods (50 Concepts)**

**Chapter 12: Data Foundations (10)**
111. Sampling Design
112. Data Types
113. Missing Data Patterns
114. Outlier Detection
115. Data Cleaning Steps
116. Exploratory Plots
117. Summary Statistics
118. Reproducible Workflow
119. Data Lineage & Data Contracts
120. Version Control

**Chapter 13: Statistical Thinking (10)**
121. Normal Distribution
122. Central Limit Theorem
123. Standard Error
124. Confidence vs Credible Intervals
125. Prediction Intervals
126. P-value Meaning
127. P-Hacking & Garden of Forking Paths
128. Effect Size Types
129. Simpson's Paradox
130. Common Misinterpretations

**Chapter 14: Modeling Basics (10)**
131. Linear Regression
132. Logistic Regression
133. Feature Selection
134. Data Leakage
135. Bias-Variance Trade-off
136. Training-Test Split
137. Cross-Validation
138. Overfitting Signs
139. Regularization
140. Baseline Models

**Chapter 15: Simulation & Computation (10)**
141. Monte Carlo Principles
142. Random Seed Setting
143. Bootstrap Methods
144. Sensitivity Analysis
145. Tornado Diagrams
146. Agent-Based Models
147. System Dynamics Models
148. Discrete Event Simulation
149. Scenario Planning
150. Counterfactual Simulation (SCM)

**Chapter 16: Communication (10)**
151. Visual Encoding
152. Gestalt Principles
153. Color Selection
154. Uncertainty Visualization
155. Uncertainty Language (Verbal vs Numeric)
156. Progressive Disclosure
157. Narrative Arc
158. Executive Summary Structure
159. Interactive Elements
160. Lie Factor & Integrity

**Part V: Decisions & Action (40 Concepts)**

**Chapter 17: Decision Frameworks (10)**
161. Decision Nodes
162. Exploration vs Exploitation
163. Prospect Theory & Reference Dependence
164. Backward Induction
165. Expected Utility
166. Risk Aversion
167. Option Value
168. EVPI & EVSI
169. Sequential Decisions
170. Group Aggregation

**Chapter 18: Prioritization (10)**
171. Opportunity Cost
172. RICE Framework
173. Cost of Delay
174. Complexity Budget
175. Portfolio Balance
176. Resource Constraints
177. Dependency Mapping
178. Diminishing Returns
179. Capacity Planning
180. Queueing Theory

**Chapter 19: Implementation (10)**
181. Pilot Principles
182. Success Metrics
183. OKR Framework
184. Guardrail Metrics
185. Monitoring Design
186. Pre-Mortem Analysis
187. Rollback Planning
188. Scaling Challenges
189. Post-Mortem Process
190. Knowledge Transfer

**Chapter 20: Ethics & Safety (10)**
191. First-Order Effects
192. Second-Order Effects
193. Unintended Consequences
194. Fairness Definitions
195. Disparate Impact
196. Privacy Trade-offs
197. Dual-Use & Misuse Analysis
198. Long-term Thinking
199. Precautionary Principle
200. Value Alignment