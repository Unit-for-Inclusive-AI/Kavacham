# KAVACHAM : **Knowledge-Aware Agent-based Verbal Advocacy using Counter-speech against Homophobia And Transphobia in Malayalam**

---

## Overview 
Watch the demo video : 
[<img width="1056" height="493" alt="Image" src="https://github.com/user-attachments/assets/4d1de11f-d9e5-4595-a63d-b12f50a24899" />](https://www.youtube.com/watch?v=iRNaxlmx1ow)


KAVACHAM is a **two-stage, multi-agent framework** designed to detect and counter online **homophobic and transphobic speech** in **Malayalam** and its **Latin-script variant (Manglish)**.  

The system integrates:  

- **Kavacham-D (Detection):** Multi-agent, debate-based detection of harmful speech.  
- **Kavacham-G (Generation):** Counter-speech generation using rhetorical strategies (*education, empathy, humor, logic, and human rights*).  

By combining **explainable detection** with **culturally sensitive counter-speech**, KAVACHAM fosters **safer and more inclusive online spaces**, particularly for under-resourced languages.  

---

## System Architecture  

### 1. User Input  
Accepts social media comments in **Malayalam** or **Manglish**.  

### 2. Kavacham-D (Detection)  
- Agents with perspectives: **Minimalist**, **Stereotype-aware**, **Norm-critical**, **Impact-balanced**, **Human Rights**.  
- Uses **debate + judge model** for the final decision.  

### 3. Kavacham-G (Counter-Speech)  
- Agents with rhetorical strategies: **Educational**, **Humor**, **Empathy**, **Logic**, **Rights-based**.  
- Judge selects the **most effective counter-speech**.  
- Generates **culturally sensitive, respectful, and persuasive responses**.  

---

## Dataset Required

- Transformed_PREDICT_Dataset_with_Rationales.csv
- 5100GPTDatasetHITL.csv
---

## Paper Link

- [P. Prasannan, P. K. Kumaresan, S. Rajiakodi, C. N. Subalalitha,
and B. R. Chakravarthi, “Counter-speech generation for homophobic
and transphobic social media content in malayalam,” Social Network
Analysis and Mining, vol. 15, no. 1, p. 87, 2025. [Online]. Available:
https://doi.org/10.1007/s13278-025-01507-x 35](https://link.springer.com/article/10.1007/s13278-025-01507-x)

## Installation  

```bash
# Clone the repository
git clone https://github.com/yourusername/kavacham.git
cd kavacham
---


