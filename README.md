# 박기현 | AI Engineer

**결과를 믿기 전에 데이터와 평가부터 검증하는 AI 엔지니어 지망생입니다.**
데이터 정제부터 모델 학습·통계 검증·API 배포, LLM 에이전트·RAG 서비스 개발까지 직접 구현했습니다.

- 🧪 **검증 중심** — 평가 기준과 가설을 실행 전에 고정하고, 부트스트랩·Wilcoxon·Holm 보정·RAGAS로 결과를 확인합니다
- 🛠 **끝까지 구현** — 수집 → 정제 → 학습 → FastAPI·Docker → Cloud Run 배포까지 직접 했습니다
- 🤖 **LLM·에이전트** — 논문 RAG 챗봇의 팀장으로 LangGraph 오케스트레이션과 평가 체계를 구현했고, 에이전트의 조건 되묻기 기능을 개발했습니다

---

## 🚀 Projects

| 프로젝트 | 내용 | 핵심 기술 |
|---|---|---|
| [**Orbit — AI 에이전트 업무 자동화**](https://github.com/20260528-skn-family-ai-33/SKN33-Final-5Team) (팀 5명, 진행 중) | 자연어 업무 설명을 워크플로우로 바꿔 실행하는 플랫폼. **LLM의 사용자 요청 검증·되묻기 판정과 도구 확장 연결을 담당**했고 회귀 테스트를 작성. 이어서 **업무 설계·도구 연결 정확도를 높이기 위한 sLLM(Qwen) 파인튜닝 작업** | Deep Agents · LangGraph · Ollama(Qwen3) · Docker · LoRA(예정) |
| [**Paper Scholar — 논문 RAG 챗봇**](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN33-4th-2Team) (3·4차 팀 프로젝트, 5명, **팀장**) | arXiv·PDF 논문 검색·요약·번역·근거 기반 Q&A. **3차**: [RAG 챗봇](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN33-3rd-2Team)의 **LangGraph 오케스트레이션·Supervisor 적응형 라우팅을 구현**하고 LangSmith·RAGAS·DeepEval 기반 400건 평가 체계 구축. **4차**: 같은 엔진을 Django·React 웹 서비스로 확장하며 Supervisor 웹 연동, 요약 우선 파이프라인 전환, 평가 코퍼스 200건 구축, Docker 배포 오류 수정 | LangGraph · LangChain · RAG · LangSmith · RAGAS · Django · React · Docker |
| [**EGFR Evidence Lab**](https://github.com/egfr-evidence-lab/egfr-evidence-lab) (개인) | 공개 데이터 26,600건을 감사·정제하고 모델 예측을 어디까지 믿을 수 있는지 검증. LLM 에이전트의 도구 사용 평가, 추론 API의 클라우드 배포까지 진행 | scikit-learn · Chemprop · FastAPI · Docker · Cloud Run · OpenAI API |
| [**LabelBudget**](https://github.com/LabelBudget/LabelBudget-Main) (개인) | GNN(D-MPNN)과 자기지도 사전학습 2종을 PyTorch로 직접 구현해 공식 구현과 출력이 비트 단위로 일치함을 검증. 라벨 수별 효과를 시드 10개로 통계 비교하고 웹 앱으로 공개 | PyTorch · LightGBM · Streamlit · pytest |
| [**OULAD 중도이탈 조기경보**](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN33-2nd-7Team) (팀 4명) | 학습 로그로 다음 주 이탈 위험 학생을 예측하는 서비스(이탈률 1.2% 불균형 데이터). **VLE 학습 로그 전처리·EDA, GRU·TCN 딥러닝 비교 실험, 모델 서비스 연동 담당**. 최종 CatBoost는 PR-AUC 0.159·ROC-AUC 0.844 | pandas · CatBoost · XGBoost · PyTorch · Streamlit |

> 이 밖에 1차 팀 프로젝트로 [서울시 버스 노선 시각화](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN33-1st-6Team)(ERD 설계·SQL·Streamlit 구조 설계)를 진행했습니다.
>
> 두 개인 프로젝트는 신약 개발 데이터를 다루지만, 핵심은 도메인과 무관한 **데이터 감사·평가 설계·재현 가능한 실험·서비스 배포** 역량입니다.

---

## 📚 Learning Log — [HYonthePark-retrospect](https://github.com/HYonthePark-retrospect)

AI 부트캠프에서 2026년 6월부터 학습한 내용을 단계별 저장소로 정리했습니다.

| 영역 | 주요 실습 |
|---|---|
| Python · DB · 데이터 분석 | Python 기초·OOP, SQL(DDL/DML/JOIN), NumPy·pandas·시각화·EDA |
| Machine Learning | 회귀·분류, 앙상블(RF·XGBoost·LightGBM), 차원 축소, 군집, 교차검증·하이퍼파라미터 튜닝, 추천 시스템 |
| Deep Learning · NLP | 역전파·옵티마이저, CNN, RNN·LSTM, Seq2Seq, Attention·Transformer, BERT |
| LLM | 프롬프트 엔지니어링, LangChain, RAG·Advanced RAG(하이브리드 검색·리랭킹·Graph RAG), LangGraph, MCP 서버 구현, sLLM LoRA 파인튜닝 |
| Multimodal | ViT, CLIP·BLIP, 멀티모달·영상 RAG, GAN·Diffusion |
| Web | HTML·CSS·JavaScript, Django |

---

## 🧰 Tech Stack

**Language** &nbsp; Python · SQL · TypeScript(팀 프로젝트)
**ML / DL** &nbsp; scikit-learn · LightGBM · XGBoost · CatBoost · PyTorch · Hugging Face
**LLM / Agent** &nbsp; LangChain · LangGraph · RAG · RAGAS · MCP · OpenAI API · Ollama · LoRA
**Serving / Web** &nbsp; FastAPI · Django · Streamlit · Docker · Google Cloud Run
**Tools** &nbsp; Git/GitHub · pytest · Jupyter · ChatGPT · Claude · Gemini

---

## 📫 Contact

- Email: rlgusqkr102@gmail.com
