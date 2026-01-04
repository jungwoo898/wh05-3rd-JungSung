# 🎙️ Feple(피플): AI 기반 상담 분석 및 코칭 플랫폼

> **Feple은 콜센터의 품질 관리(QC) 및 상담사 코칭 프로세스를 100% 자동화하고, 데이터 기반의 객관적인 평가와 맞춤형 코칭을 제공하여 상담 품질과 관리 효율을 혁신하는 AI 솔루션입니다.**

- 기존의 주관적이고 샘플링에 의존했던 수동 평가 방식의 한계를 극복하고, 모든 상담 내용을 AI가 분석하여 일관성 있고 공정한 평가를 제공합니다.
- Feple은 단순한 분석 도구를 넘어, **AI 전환(AX)을 통해 콜센터 운영의 패러다임을 바꾸는 통합 플랫폼**입니다.

---

## 👥 **팀 소개**

| [**오현서**](https://github.com/OhHyunSeo) | [**김기훈**](https://github.com/kimgihoon-99) | [**노준석**](https://github.com/RJ-Stony) | [**오정우**](https://github.com/jungwoo898) |
|:--:|:--:|:--:|:--:|
| [<img width="128" height="128" alt="오현서" src="https://github.com/user-attachments/assets/81ca3f11-b78f-4871-93d3-a6754b139bd6" />](https://github.com/OhHyunSeo) | [<img width="128" height="128" alt="김기훈" src="https://github.com/user-attachments/assets/fce55b66-abc1-4858-9f92-ac95b2fd28f8" />](https://github.com/kimgihoon-99) | [<img width="128" height="128" alt="노준석" src="https://github.com/user-attachments/assets/58095b6c-ec16-48de-b3c2-bdf808a6fa6f" />](https://github.com/RJ-Stony) | [<img width="128" height="128" alt="오정우" src="https://github.com/user-attachments/assets/640305e8-b8d6-479c-a8ff-cde0f01933a5" />](https://github.com/jungwoo898) |
| 서버 환경 구축<br> 백엔드 API 연동<br> 웹 퍼블리싱 | 알고리즘 설계<br> 데이터 수집<br> 백엔드 API 연동 | 시스템 아키텍처 설계<br> 프론트엔드 총괄<br> Call 모델 개발 | 프로젝트 기획<br> 사용자 경험(UX) 상담 후 처리 모델 개발<br> |

---

## ✨ **실제 서비스 & 주요 기능**

> **🔗 [feple-ad.vercel.app](https://feple-ad.vercel.app)**

| 구분 | For Consultants (상담사) | For QC Managers (QC 관리자) |
| :--- | :--- | :--- |
| **성과 대시보드** | 개인의 성과 지표, 성장 추이, 강점/약점을 시각적으로 확인하고 동료와 비교하며 자기주도적 성장을 도모합니다. | 팀/부서별 전체 상담사의 성과를 실시간으로 모니터링하고, 우수 상담사와 코칭이 필요한 상담사를 즉시 파악합니다. |
| **AI 코칭 리포트** | 모든 상담콜에 대해 AI가 생성한 강점, 개선점, 구체적인 코칭 팁이 담긴 리포트를 즉시 제공받습니다. | 모든 평가 과정이 자동화되어, QC 관리자는 분석이 아닌 코칭과 품질 개선 전략 수립 등 고부가가치 업무에 집중할 수 있습니다. |
| **상세 분석** | 상담 스크립트 전체와 함께 감정 변화, 주요 지표(정중함, 공감 등) 점수를 상세히 검토하며 스스로 문제점을 진단합니다. | 특정 상담 세션을 드릴다운하여 문제의 근본 원인을 파악하고, 데이터에 기반한 객관적이고 공정한 피드백을 제공합니다. |
| **간편한 사용** | 상담 녹음 파일을 업로드하기만 하면, 전사부터 분석, 평가, 코칭까지 모든 과정이 자동으로 처리됩니다. | 수동으로 통화 내용을 듣고 평가하는 시간을 **95% 이상 단축**하고, 일관된 기준으로 팀 전체의 품질을 관리합니다. |

---

## 🌊 **데이터 흐름도 (Data Flow)**

> Feple의 데이터 처리 파이프라인은 상담 녹음 파일이 업로드되는 순간부터 최종 분석 리포트가 대시보드에 표시되기까지, 아래와 같이 체계적이고 자동화된 단계로 진행됩니다.

![Feple Data Flow](docs/Feple%20Data%20Flow.png)

---

## 🛠️ **기술 스택 (Tech Stack)**

| Category      | Technologies |
|---------------|--------------|
| **Frontend**  | ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=ffffff) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=ffffff) ![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=ffffff) ![Recharts](https://img.shields.io/badge/-Recharts-8884d8?style=flat-square) |
| **AI/ML**     | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=ffffff) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=ffffff) ![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=ffffff) ![faster-whisper](https://img.shields.io/badge/-huggingface-FFD21E?style=flat-square&logo=huggingface&logoColor=ffffff) |
| **Backend**   | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=ffffff) ![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat-square&logo=prisma) |
| **Infra/DevOps**| ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=ffffff) ![Replicate](https://img.shields.io/badge/-Replicate-000000?style=flat-square) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=ffffff) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=ffffff) |

---

## 🏛️ **기술 아키텍처 및 성능**

> Feple은 최신 서버리스 기술과 고성능 AI 모델을 결합하여, 확장성과 효율성, 그리고 기술적 깊이를 모두 갖춘 시스템을 구현했습니다.

### **인프라 아키텍처: 100% Serverless & MSA**

- 모든 인프라는 Vercel, Replicate, Supabase를 기반으로 한 **완전 서버리스(Fully Serverless)** 환경에 구축되었습니다.
- 각 컴포넌트는 독립적인 마이크로서비스로 동작하여, 트래픽 증가 시 자동 확장되고, 장애 발생 시 다른 서비스에 미치는 영향을 최소화합니다.

*   **Vercel (프론트엔드 & 엣지 컴퓨팅):** Next.js로 구축된 프론트엔드를 글로벌 엣지 네트워크에 배포하여 전 세계 어디서든 빠른 접속 속도를 보장하며, 서버리스 함수를 통해 백엔드 로직을 처리합니다.
*   **Replicate (서버리스 AI 추론):** `cog`로 컨테이너화된 Feple의 AI 모델을 배포하여, 복잡한 MLOps 없이 사용량에 따라 GPU 자원이 자동 할당/확장되는 비용 효율적인 AI 추론 환경을 구축했습니다.
*   **Supabase (통합 백엔드):** PostgreSQL DB, 파일 스토리지, 인증 등 백엔드의 모든 기능을 통합 제공하여 개발 및 운영의 복잡성을 크게 낮췄습니다.

### **성능 우수성**

> [`Feple 서비스 성능 평가 결과서`](docs/Feple%20서비스%20성능%20평가%20결과서.pdf)를 확인하여 알 수 있듯이, Feple은 모든 핵심 성능 지표(SLA)를 성공적으로 충족 및 초과 달성했습니다.

*   **준실시간 AI 분석:** 5분 길이의 상담 통화 파일을 **평균 49.7초** 만에 분석 완료합니다. (실제 통화 시간의 **16.7%** 수준)
*   **빠른 대시보드:** 대시보드 초기 로딩 **3초 이내**, 데이터 조회 **평균 5.2초**로 쾌적한 사용자 경험을 제공합니다.
*   **안정적인 API:** 50명의 사용자가 동시 접속하는 부하 테스트 환경에서도 95%의 요청을 **450ms** 이내에 처리하는 견고함을 입증했습니다.
*   **높은 처리 용량:** 완전 자동화된 파이프라인을 통해 **일일 10,000건 이상의 상담**을 처리할 수 있습니다.

---

## 🧠 **Hybrid AI & 한국어 특화된 AI 모델**

> Feple의 AI는 단순히 외부 API를 호출하는 것을 넘어, 속도와 정확도, 비용 효율성을 모두 고려한 **하이브리드(Hybrid) AI 아키텍처**로 설계되었습니다.
> 이는 [`모델 정의서`](docs/모델%20정의서/Feple%20CALL%20모델%20정의서.pdf)에 상세히 기술된 Feple의 핵심적인 설계 철학입니다.

### **왜 하이브리드 AI인가?**

*   **규칙 기반 접근의 역할:** '존댓말 어미'(-습니다, -세요)처럼 명확하고 반복적인 패턴은 규칙(Rule-based)으로 빠르게 처리하여 효율성을 극대화합니다. 이는 LLM의 불필요한 호출을 줄여 비용과 시간을 절약합니다.
*   **LLM 기반 접근의 역할:** '사과의 진정성'이나 '문제 해결 제안의 논리적 타당성'처럼 깊은 문맥 이해가 필요한 정성적 분석은 LLM을 통해 처리합니다.
*   **시너지:** 규칙 기반으로 1차 필터링을 거친 후, 정제된 후보군에 대해서만 LLM이 심층 분석을 수행하는 **'필터링 및 검증'** 역할을 통해, 전체 파이프라인의 속도, 정확도, 비용 효율성 간의 최적의 균형을 달성했습니다.

### **1. Feple_AI: 핵심 분석 엔진**

*   **STT (음성 인식):** `faster-whisper` (medium 모델)를 채택하여 빠르고 정확한 한국어 음성 인식을 수행합니다.
*   **화자 분리:** `pyannote/speaker-diarization-3.1` 모델을 통해 상담사와 고객의 발화를 95% 이상의 정확도로 분리합니다. (현재 시스템의 주된 병목점으로, 향후 성능 개선의 핵심 포인트)
*   **한국어 특화 NLP:** `Kiwipiepy` (형태소 분석), `KSS` (문장 분리) 라이브러리를 사용하여 존댓말, 완곡어법 등 한국어의 미묘한 뉘앙스까지 정확하게 분석합니다.
*   **18개의 다각적 분석 지표:** 아래와 같이 다각적인 지표를 추출하여 상담 품질을 입체적으로 분석합니다.
    *   **정중함 및 언어 품질:** 존댓말 사용률, 긍/부정어 비율, 완곡어 사용률
    *   **공감적 소통:** 공감/사과 표현의 진정성 (LLM으로 검증)
    *   **문제 해결 역량:** 구체적인 해결책 제시 수준
    *   **감정 안정성:** 상담 전후 고객 감정 변화 추이
    *   **대화 흐름 및 응대 태도:** 평균 응답 시간, 끼어들기, 침묵 비율

### **2. Feple_LLM_Algorithm: 자동 피드백/코칭 생성**

*   **객관적 점수화:** `Feple_AI`가 추출한 18개 지표를 바탕으로, 사전에 정의된 `cutoff` 기준에 따라 5대 핵심 역량(정중함 및 언어 품질, 공감적 소통, 문제 해결 역량 등)의 점수와 등급을 계산합니다.
*   **LLM 기반 정성 피드백:** 이 점수/등급과 전체 스크립트를 **OpenAI의 GPT** 모델에 전달하여, 단순 평가를 넘어 구체적인 **강점, 개선점, 실천 가능한 코칭 멘트**를 생성합니다.
*   **완전 자동화 파이프라인:** Supabase DB를 폴링(polling)하여 새로운 분석 데이터가 입수되는 즉시, 점수화부터 LLM 리포트 생성, 결과 저장까지의 모든 과정을 자동으로 수행합니다.

---

## 💻 **핵심 코드**

> Feple의 핵심 기능이 어떻게 코드로 구현되었는지 간략하게 알려드리겠습니다.

### **`Feple_AD` - 동적 차트 생성 (in `ScoreChart.tsx`)**
- *Recharts 라이브러리를 사용하여 AI 분석 결과를 바탕으로 동적인 레이더 차트를 생성하고, 상담사의 역량을 시각적으로 보여주는 핵심 컴포넌트입니다.*

<details>
<summary>코드 보기/숨기기</summary>

```typescript
// 실제 코드에서 발췌 및 단순화
import { Radar, RadarChart, PolarGrid, Legend, PolarAngleAxis, PolarRadiusAxis, ResponsiveContainer } from 'recharts';

const ScoreChart = ({ data }) => (
  <ResponsiveContainer width="100%" height={300}>
    <RadarChart cx="50%" cy="50%" outerRadius="80%" data={data}>
      <PolarGrid />
      <PolarAngleAxis dataKey="subject" />
      <PolarRadiusAxis angle={30} domain={[0, 100]} />
      <Radar name="상담사 점수" dataKey="score" stroke="#8884d8" fill="#8884d8" fillOpacity={0.6} />
      <Legend />
    </RadarChart>
  </ResponsiveContainer>
);
```

</details>

### **`Feple_AI` - AI 분석 파이프라인 (in `pipeline.py`)**
- *오디오 파일이 입력되었을 때, 화자 분리, STT, 지표 계산 등 전체 AI 분석 프로세스를 순차적으로 실행하고 결과를 종합하는 파이프라인의 중심부입니다.*

<details>
<summary>코드 보기/숨기기</summary>

```python
# 실제 코드에서 발췌 및 단순화
class AnalysisPipeline:
    def run(self, audio_path):
        # 1. 화자 분리 (병목 구간)
        speaker_turns = self.diarization_module.run(audio_path)

        # 2. 음성 인식 (STT)
        word_segments = self.stt_module.run(audio_path)

        # 3. STT 결과와 화자 정보 병합
        structured_transcript = self.merge_results(speaker_turns, word_segments)

        # 4. 18개 정량/정성 지표 계산
        metrics = self.metrics_calculator.run(structured_transcript)

        # 5. 최종 결과 JSON으로 패키징
        return self.package_results(metrics)
```

</details>

### **`Feple_LLM_Algorithm` - 자동화된 LLM 피드백 생성 (in `LLM_evaluation_with_supabase.py`)**
- *Supabase DB를 주기적으로 확인하여, 처리되지 않은 분석 결과가 있으면 자동으로 점수를 매기고 LLM을 호출하여 코칭 피드백을 생성한 뒤, 다시 DB에 저장하는 완전 자동화 로직의 핵심입니다.*

<details>
<summary>코드 보기/숨기기</summary>

```python
# 실제 코드에서 발췌 및 단순화
def main_loop():
    while True:
        # 1. Supabase에서 처리되지 않은 분석 결과 조회
        unprocessed_rows = get_unprocessed_analysis_results()

        for row in unprocessed_rows:
            # 2. 정량적 지표(metrics)로 5대 역량 점수 및 등급 계산
            scores = metrics_to_scores_and_grades(row.get("metrics"))

            # 3. 점수와 대화록을 기반으로 LLM 코칭 피드백 생성
            feedback = run_llm_evaluation_with_scores(scores, row.get("transcript"))

            # 4. 최종 결과를 counselor_evaluations 테이블에 저장
            save_analysis_feedback_to_supabase(row, scores, feedback)

        # 10초 대기 후 다시 시작
        time.sleep(10)
```

</details>

---

## 🚀 **시작하기**

### **사전 요구사항**

*   Node.js 18+
*   Python 3.10+
*   Supabase 프로젝트 생성 및 API 키 발급
*   OpenAI API 키 발급
*   Replicate 계정 및 API 토큰 발급

### **설치 및 실행**

1.  **저장소 클론 (서브모듈 포함):**
    ```bash
    git clone --recurse-submodules https://github.com/your-repo/Feple_v2.git
    cd Feple_v2
    ```
2.  **Feple_AD (프론트엔드) 설정:**
    ```bash
    cd Feple_AD
    npm install
    # .env.local 파일에 Supabase 및 기타 환경변수 설정
    npm run dev
    ```
3.  **Feple_AI (AI 모델) 배포:**
    ```bash
    cd ../Feple_AI
    # Replicate CLI 설치 및 로그인
    cog push r8.im/your-username/feple-ai
    ```
4.  **Feple_LLM_Algorithm (피드백 생성) 실행:**
    ```bash
    cd ../Feple_LLM_Algorithm
    pip install -r requirements.txt
    # .env 파일에 Supabase, OpenAI 환경변수 설정
    python LLM_evaluation_with_supabase.py
    ```

---

## 📂 **프로젝트 문서 안내**

> 프로젝트에 대한 더 깊이 있는 정보는 아래 `docs` 폴더의 문서를 참고해 주세요. (문서명을 클릭하면 해당 파일을 확인할 수 있습니다.)

| 문서명 | 주요 내용 및 기대효과 |
| :--- | :--- |
| [**Feple 프로젝트 계획서.pdf**](docs/Feple%20프로젝트%20계획서.pdf) | 프로젝트의 범위, 리소스 계획을 담고 있습니다. **프로젝트의 초기 청사진을 이해할 수 있습니다.** |
| [**Feple 요구사항정의서.xlsx**](docs/Feple%20요구사항정의서.xlsx) | 시스템의 기능적/비기능적 요구사항 명세서입니다. **Feple이 해결하고자 하는 구체적인 문제와 목표를 파악할 수 있습니다.** |
| [**Feple WBS.xlsx**](docs/Feple%20WBS.xlsx) | 프로젝트의 전체 작업을 상세하게 분할한 WBS입니다. **팀의 체계적인 프로젝트 관리 방식을 엿볼 수 있습니다.** |
| [**모델 정의서/Feple CALL 모델 정의서.pdf**](docs/모델%20정의서/Feple%20CALL%20모델%20정의서.pdf) | Feple AI 모델의 하이브리드 아키텍처, 기술 스택 선정 근거, 18개 세부 분석 지표의 상세 계산 방식 등 **모델의 핵심 설계 사상을 심도 있게 이해할 수 있습니다.** |
| [**모델 정의서/Feple LLM Alogorithm 모델 정의서.pdf**](docs/모델%20정의서/Feple%20LLM%20Alogorithm%20모델%20정의서.pdf) | 5대 지표 산출을 바탕으로 강점, 개선점, 코칭 멘트가 생성되는 과정과 **LLM 프롬프트 설계 방식을 상세히 확인할 수 있습니다.** |
| [**Feple 서비스 성능 평가 결과서.pdf**](docs/Feple%20서비스%20성능%20평가%20결과서.pdf) | AI 파이프라인 및 대시보드의 상세 성능(처리 속도, 응답 시간 등) 측정 결과와 분석, 병목 현상 및 개선 제안을 통해 **프로젝트의 기술적 완성도와 안정성을 객관적인 데이터로 확인할 수 있습니다.** |
| [**Feple 프로젝트 수행 결과 보고서.pdf**](docs/Feple%20프로젝트%20수행%20결과%20보고서.pdf) | 프로젝트 계획 대비 실제 수행 결과를 비교하고, 성과와 교훈을 정리한 최종 보고서입니다. **프로젝트의 성공적인 완수 과정을 살펴볼 수 있습니다.** |
| [**Feple 최종 발표 자료.pdf**](docs/Feple%20최종%20발표%20자료.pdf) | 프로젝트의 배경, 목표, 개발 과정, 시연, 기대 효과를 요약한 최종 발표 자료입니다. **프로젝트 전체를 빠르게 이해하는 데 가장 효과적입니다.** |

---

## 🖼️ **스크린샷**

| 구분 | 실제 화면 |
| :---: | :---: |
| 상담사 대시보드 | <img width="1919" height="878" alt="image" src="https://github.com/user-attachments/assets/8f9e6d78-1aac-4ef5-a2d0-95becef2f7f3" /> |
| 상담사 모니터링 | <img width="1919" height="879" alt="image" src="https://github.com/user-attachments/assets/05247edd-9657-45dd-90b9-c81aa0c87425" /> |
| QC 관리자 대시보드 | <img width="1919" height="878" alt="image" src="https://github.com/user-attachments/assets/ba6cd5d8-4663-433e-b5d7-99fb7d9cc750" /> |
| QC 관리자 모니터링 | <img width="1919" height="880" alt="image" src="https://github.com/user-attachments/assets/7a63d15a-c187-4532-9924-81b51e2ba368" /> |

---

## 📈 **향후 개선 계획**

> Feple은 현재의 완성도에 안주하지 않고, 지속적인 기술 개발을 통해 최고의 상담 분석 솔루션으로 발전하는 것을 목표로 합니다.

-   [ ] **성능 최적화:** 현재 AI 파이프라인의 가장 큰 병목인 **화자 분리 모델의 처리 속도 개선**을 최우선 과제로 삼아, 더 가벼운 대체 모델을 연구하거나 현재 모델의 파라미터를 미세 조정하여 전체 분석 시간을 단축할 계획입니다.
-   [ ] **자체 LLM 미세조정 (Fine-tuning):** 장기적으로는 외부 상용 API 의존도를 낮추고 비용 효율성을 높이기 위해, **Polyglot-Ko와 같은 경량화된 오픈소스 LLM을 상담 도메인 특화 데이터로 미세조정**하는 프로젝트를 추진할 것입니다.
-   [ ] **분석 지표 확장:** '적극적 경청 지표(맞장구 등)', '상향/교차 판매 시도 탐지' 등 비즈니스 성과와 직결되는 새로운 분석 지표를 개발하여 분석의 깊이를 더할 예정입니다.
-   [ ] **관리자용 분석 UI 고도화:** QC 관리자 및 센터장이 데이터를 다각도로 탐색하고 인사이트를 얻을 수 있는 **웹 기반의 시각화 대시보드**를 추가 개발할 계획입니다.
