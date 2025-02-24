---
task:
  title: 몰입 환경 - 재무
---

## 몰입 환경 - 재무  

Microsoft 365 Copilot을 사용하여 주요 재무 인사이트를 수집, 분석 및 문서화하여 재무 의사 결정을 개선합니다.

다음 세 가지 작업을 수행합니다.  

- **Copilot Chat**을 사용하여 재무 데이터를 수집합니다.  
- **Copilot Chat**을 사용하여 재무 영향 및 추세를 평가합니다.  
- **Word의 Copilot**을 사용하여 재무 분석 문서 초안을 작성합니다.  

> **참고:** 시작하는 데 도움이 되는 샘플 프롬프트가 제공됩니다. 필요에 맞게 자유롭게 개인화하여 창의력을 발휘하고 탐색해 보세요! Copilot이 원하는 결과를 제공하지 않는 경우 프롬프트를 수정하고 다시 시도합니다. 과정을 즐기고 재미있게 실험해 보세요!  

### 작업 1: 재무 데이터 수집  

**Microsoft 365 Copilot Chat**을 사용하여 선택한 회사 또는 업계의 시장 동향, 매출 인사이트, 비용 구조 등 관련 재무 데이터를 수집합니다. 이 정보는 재무 분석을 위한 견고한 기반을 구축하여 비즈니스 성과를 평가할 정확한 데이터 요소를 확보하는 데 도움이 됩니다.

**단계:**

- 새 브라우저 탭을 열고 [M365copilot.com](https://m365copilot.com/)으로 이동합니다.
- **Copilot Chat**에서 **"웹 모드"** 탭이 선택되어 있는지 확인합니다.

    ![작업 모드 탭을 보여 주는 스크린샷.](../Prompts/Media/web-mode.png)

**샘플 프롬프트**:

```text
Summarize key financial indicators for [company/industry] over the last year, including revenue growth, cost trends, and market conditions.
```

> **참고:** [회사/산업]을 분석하려는 특정 엔터티로 대체합니다. **/** 문자(슬래시)를 사용하여 해당하는 경우 내부 회사 데이터를 참조합니다.

### 작업 2: 재무 영향 및 추세 평가  

**Microsoft 365 Copilot Chat**을 사용하여 수집한 재무 데이터를 평가하고 추세, 위험 및 기회를 파악합니다. 비용 변동, 매출 증가 패턴 및 기타 주요 지표를 분석하여 의사 결정에 영향을 줄 수 있는 의미 있는 인사이트를 추출합니다.

**샘플 프롬프트**:

```text
Based on recent financial performance, identify key trends, risks, and opportunities for [company/industry]. Provide insights on cost fluctuations and revenue projections.
```

> **팁 1:** 심층 분석이 필요한 경우 Copilot에 여러 기간 또는 회사의 추세를 비교하도록 요청합니다.

> **팁 2:**  
>
> - 다음 작업을 위해 저장할 Word 문서로 응답을 내보내도록 Copilot에 요청합니다. OneDrive에 문서를 저장하고 공유 URL을 복사합니다.
> - 링크를 복사하려면 저장된 Word 문서를 열고 아래와 같이 **공유** > **링크 복사**를 선택합니다.  
> ![링크 공유](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### 작업 3: 재무 분석 문서 초안 작성  

**Word의 Copilot**을 사용하여 주요 결과, 추세 및 전략적 권장 사항을 요약하는 구조화된 재무 분석 문서를 작성합니다. 문서가 명확한 내용을 제시하여 이해 관계자가 재무 전망 및 의미를 신속하게 이해할 수 있도록 합니다.

**단계:**

- 브라우저([word.new](https://word.new))에서 Microsoft Word를 시작하거나 데스크톱 응용 프로그램을 사용합니다.
- **"작성하고 싶은 내용을 설명하세요"** 라고 표시된 곳에 프롬프트를 입력합니다.

    ![Word의 Copilot을 보여 주는 스크린샷.](../Prompts/Media/draft-with-copilot.png)

**샘플 프롬프트**:

```text
Draft a financial analysis report on [company/industry], summarizing key revenue trends, cost analysis, profitability insights, and future financial projections. Use the insights from the linked document to structure the report logically.

[Paste link to shared Word document from Task 2 here]
```

> **팁:** **유지**를 선택하기 전에 Copilot에게 주제를 확장하거나 어조를 조정하여 문서를 더 명확하게 다듬어 달라고 요청합니다.
