# Functional_Expansion
Empathy Chatbot for Pet Loss Support — A lightweight on-device chatbot system using KoELECTRA for emotion recognition and KoGPT2 for empathy-based response generation, achieving 0.84 BERTScore and +18% consistency improvement through integrated model evaluation.

---

# Empathy Chatbot for Pet Loss Support  
### 감정 인식 기반 반려동물 상실 케어 챗봇 (KoELECTRA + KoGPT2)

---

## Project Overview  
이 프로젝트는 **반려견/반려묘 상실 경험자(펫로스 증후군)** 를 위한  
감정 인식 및 공감형 챗봇 시스템입니다.  
사용자의 텍스트를 분석하여 감정 상태를 분류하고,  
그에 맞는 위로·응원·회상형 응답을 제공합니다.  

- **Emotion Recognition** → `KoELECTRA`  
- **Empathetic Response Generation** → `KoGPT2`  
- **Evaluation Metrics** → `BERTScore`, `SummEval`, `NarrativeQA`

---

## Model Architecture
---

## Performance Summary

| Metric | Model | Score | Improvement |
|---------|--------|--------|-------------|
| **BERTScore** | KoGPT2 | **0.84** | Maintained high fluency & contextual coherence |
| **SummEval** | KoGPT2 | **0.82** | Improved expression diversity & naturalness |
| **Consistency Index** | KoELECTRA + KoGPT2 | **+18% ↑** | Enhanced empathy consistency across emotion stages |

> 💬 Combined pipeline (KoELECTRA + KoGPT2) improved response coherence and emotional tone consistency by 18%.

---

## Features
- Emotion classification into **5 stages (L1~L5)** and **9 tone types (E1~E9)**
- Context-aware empathy tone design
- On-device inference structure for lightweight deployment
- Visualization dashboard for model evaluation and empathy scoring
- Potential expansion into **mental health early detection** and **counseling linkage**

---

## Tech Stack
| Category | Tools |
|-----------|--------|
| Language | Python |
| Models | KoELECTRA · KoGPT2 |
| Libraries | HuggingFace Transformers, PyTorch, Pandas |
| Evaluation | BERTScore, SummEval, NarrativeQA |
| Visualization | Matplotlib, Plotly |
| Deployment | On-device Test Environment (Local GPU) |

---

## Future Work
- Fine-tuning with user feedback datasets  
- Integration with psychological counseling APIs  
- Extension to generalized grief-support chatbot framework  

---

## Author
**양소라 (Sora Yang)**  
Clinical Data Scientist & AI Developer  
> Focused on bridging clinical empathy with AI-driven emotional intelligence.  

📧 Contact: [your_email@example.com]  
🔗 Portfolio: [link_to_portfolio_or_notion]  

---

## 🪶 License
This project is licensed under the **MIT License**.  
See [LICENSE](LICENSE) for details.
