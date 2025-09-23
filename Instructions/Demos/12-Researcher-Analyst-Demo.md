---
demo:
  title: 리서치 도구 및 분석 도구 데모
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 리서치 도구 및 분석 도구 데모

이 데모에서는 Copilot 앱에 기본 제공되는 두 명의 전문가 에이전트인 **리서치 도구** 및 **분석 도구**를 사용하는 방법을 강조 표시합니다.  

- **리서치 도구**는 웹 데이터를 회사의 파일 및 기술 자료와 결합하여 여러 단계의 연구 작업을 처리할 수 있도록 도움을 줍니다.  
- **분석 도구**는 숙련된 데이터 과학자처럼 사고하며, 코드를 모르더라도 고급 데이터 분석과 Python 실행을 수행할 수 있습니다.  

## 데모 설정

이러한 데모를 완료하려면, 모든 필수 파일과 리소스를 포함한 [리서치 도구 및 분석 도구 데모 - 콘텐츠 팩](https://microsoft.sharepoint.com/:u:/r/teams/MTTCentral/Immersion%20Experience%20Source%20Control/MS-4021%20Copilot%20Immersion%20Experience/Demos/Agent%20Demo%20Sample%20Docs/Researcher%20and%20Analyst%20Demo%20-%20Content%20Pack.zip?csf=1&web=1&e=384sFW)을 다운로드해야 합니다.  

> **팁:** 데모를 진행하기 전에 데모 환경에 SharePoint 사이트를 만들어 쉽게 액세스할 수 있도록 모든 파일을 저장합니다. 또는 파일을 로컬에 저장한 다음, **/** 를 사용하여 프롬프트에서 직접 참조할 수도 있습니다.  

이러한 에이전트에 액세스하려면 다음을 수행합니다.  

- [m365.cloud.microsoft](https://m365.cloud.microsoft)에서 **Copilot 앱**을 엽니다.  
- 탐색 창에서 **리서치 도구** 또는 **분석 도구**를 선택하세요.  

> **참고:** 신뢰할 수 있는 인사이트를 얻기 위해 리서치 도구 및 분석 도구를 내부 파일(SharePoint/OneDrive)과 연결해야 합니다.

---

## 핵심 요지

- **리서치 도구**는 고액의 컨설턴트처럼 작동합니다. 내부 파일, 경쟁사 인텔리전스, 웹 소스를 결합하여 체계적이고 잘 인용된 결과물을 만들어낼 수 있습니다.  
- **분석 도구**는 마치 데이터 과학자를 곁에 둔 것과도 같은 효과가 있습니다. 모델을 빌드하고, Python 코드를 실행하며, 추세를 즉시 시각화합니다.  
- 두 에이전트 모두 추론을 투명하게 설명하여 결과의 유효성을 검사할 수 있도록 합니다.  
- 이 에이전트를 함께 사용하면 마케팅 계획, 고객 세분화, 재무 전망과 같은 전략적 업무를 가속화하여 더 빠르고 자신 있게 업무를 진행할 수 있습니다.  

---

## 데모 단계

### 리서치 도구: 마케팅 계획 빌드

> **중요:** 리서치 도구가 첫 번째 프롬프트를 완료할 수 있도록 충분한 시간을 제공하기 위해, 1~4단계는 반드시 학습 시작 시점(슬라이드 5에 표시된 대로)에 완료해야 합니다.

1. 탐색 창에서 **리서치 도구**를 엽니다.  

    ![M365 Copilot 메뉴에서 선택된 리서치 도구를 보여 주는 스크린샷](../Prompts/Media/researcher.png)  

1. 다음 프롬프트를 입력합니다.

    ```text
    Create a marketing plan for our newest SprintCycle EV charger launch. 
    Emphasize its AI-powered adaptive charging, modular design, and biometric access control. 
    Make sure to include recommendations on the right digital channels and content strategy. 
    Include insights from competitors and our past GTM campaigns.
    ```

1. `/`를 사용하여 참조 파일을 첨부합니다(SharePoint/OneDrive를 가리킴).  

   - **/SprintCycle Charger Product Launch.docx**  
   - *(선택 사항)* **/Contoso - PedalPerks GTM Plan.docx**  

1. **제출**을 선택합니다.  

리서치 도구에서는 다음과 같은 작업을 수행합니다.  

- 내부 파일과 웹에서 받은 인사이트를 결합합니다.  
- 채널 및 콘텐츠 전략에 대한 권장 사항을 활용하여 마케팅 계획을 수립합니다.  
- 출처를 인용하여 해당 작업의 유효성을 검사할 수 있도록 합니다.  

> **참고:** 리서치 도구는 추론 경로("생각의 연결고리")를 보여 주고, 필요한 경우 다른 에이전트를 호출할 수 있습니다.  

### 분석 도구: 고객 구분 및 재무 모델링

**참고:** 이 데모는 콘텐츠의 Executive 버전에 대해 수행되지 않고 대신 Copilot 스튜디오** 데모로 **이동합니다.

1. 탐색 창에서 **분석 도구**를 엽니다.

    ![M365 Copilot 메뉴에서 선택된 분석 도구를 보여 주는 스크린샷](../Prompts/Media/analyst.png)  

1. 다음 프롬프트를 입력합니다.

    ```text
    Find the right customer segment and demographic to sell our new EV charger, 
    include a graph to show how this will maximize our market opportunity.
    ```

1. **+** 기호를 사용하여 파일을 첨부합니다.  

   - **BoulderEV ebike Internal Market Forecast.xlsx**  

    ![분석 도구에서의 파일 첨부를 보여 주는 스크린샷](../Prompts/Media/Analyst-Attach-Files.png)  

1. **제출**을 클릭합니다.  

분석 도구에서는 다음과 같은 작업을 수행합니다.  

- 데이터 세트를 분석합니다.  
- 중요한 고객 세그먼트를 식별합니다.  
- 권장 사항을 백업하는 시각화를 제공합니다.  

### 추가 분석 도구 시나리오

다양성을 위해 이러한 추가 프롬프트를 실행할 수 있습니다. 각 시나리오는 동일한 패턴을 따릅니다. **프롬프트 → 파일 첨부 → 제출 → 결과 검토**

- **재무 예측**  

    ```text
    Build a 5-year financial projection from this data along with a graph to view revenue growth over time.
    ```  

    파일: **BoulderEV ebike Internal Market Forecast.xlsx**  

- **영업 실적**  

    ```text
    Analyze sales volume across locations to identify our highest and lowest performing stores, 
    along with a visualization of the best-selling products.
    ```  

    파일: **BoulderEV ebike Internal Market Forecast.xlsx**  

- **캠페인 성과**  

    ```text
    Analyze and visualize how the marketing campaign performed across each target segment 
    and help me decide where to re-target our next campaign.
    ```  

    파일: **BoulderEV ebike Internal Market Forecast.xlsx**  

## 주요 요점

- **리서치 도구**: 고품질 리서치를 통해 전략과 계획을 가속화합니다.  
- **분석 도구**: 고급 분석 및 시각화를 통해 데이터 기반 인사이트를 제공합니다.  

리서치 도구와 분석 도구를 함께 사용하면 **질문에서 인사이트까지**의 경로를 단축하여 몇 주가 걸리는 노력을 몇 분 만에 끝낼 수 있습니다.  

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
