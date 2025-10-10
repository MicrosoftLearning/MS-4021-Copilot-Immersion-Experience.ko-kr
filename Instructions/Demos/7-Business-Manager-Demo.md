---
demo:
  title: 비즈니스 관리자 데모
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 비즈니스 관리자 데모

**시나리오**:

판매 실적과 고객 피드백을 분석하여 제품 문제를 해결한 다음 팀과 협업하여 개선 계획을 세웁니다.

## 데모 설정

샘플 문서는 MS-4021 GitHub 리포지토리 [여기](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)에서 찾을 수 있습니다.

이 데모에 필요한 특정 파일은 다음과 같습니다.

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

> **참고:** 다운로드 후 해당 파일이 OneDrive에 동기화될 때까지 최대 10분 정도 걸릴 수 있습니다. 데모 중에 지연을 방지하려면 해당 파일을 다운로드하여 OneDrive에서 미리 사용할 수 있는지 확인합니다. 파일을 사용할 수 없는 경우 문서를 열고 데모에서 사용할 공유 파일 링크를 복사합니다.

## 데모 단계

### Excel의 Copilot

1. 브라우저 또는 데스크톱 응용 프로그램에서 Excel을 실행하고 **EV_Charger_Sales_Analysis_v1.xlsx** 파일을 엽니다.

1. Excel 파일의 **"Sales by Product" 탭으로 이동**합니다.

1. Excel 리본에서 **Copilot**을 선택한 다음, **앱 기술**을 선택하여 Copilot 창을 엽니다.

1. Copilot을 사용하여 월 매출 계산:  

   먼저 가장 많은 매출을 창출하는 비즈니스 범주를 파악해 보겠습니다. 이 시트에는 3년간의 판매 데이터가 포함되어 있으며, 제품별 월 매출이 수천 개의 행으로 표시됩니다. 일상적인 작업이지만 데이터의 양이 많아 다루기 어려울 수 있습니다. Copilot에게 제품별 월 매출을 신속하게 계산하도록 요청할 수 있습니다.

   다음 프롬프트를 사용합니다.

   ```text
   Calculate monthly revenue by product and add a column with total revenue - refer to the Prices worksheet.
   ```

    - Copilot은 이 작업을 수행하는 방법과 탭 간에 참조할 데이터를 알고 있습니다.
    - Copilot은 이러한 수치를 실행하는 방법에 대한 계획을 만들고, 그 계획을 실행하면서 작업을 보여주고, 도달한 솔루션에 대해 질문하거나 반복하라는 메시지를 표시합니다.
    - **+열 삽입**을 선택한 다음 **Sales by Product** 탭으로 다시 이동합니다.

1. Copilot을 사용하여 매출을 분석합니다. Copilot 창에 다음 프롬프트를 입력하면 됩니다.

    ```text
    What is the total revenue for each category so far in 2024?
    ```

    - Copilot이 수치를 계산하여 통합 문서에 추가할 수 있는 막대형 차트를 만듭니다.
    - **+새 시트에 추가**를 클릭한 다음 **Sales by Product** 탭으로 다시 이동합니다.

1. 이제 Copilot을 사용하여 매출이 낮은 제품을 강조 표시합니다. 이 프롬프트를 입력하면 됩니다.

    ```text
    Highlight rows where the value in column H is less than $100K.
    ```

    - Copilot이 조건부 서식을 적용하여 기준에 맞지 않는 제품을 식별하도록 도와 줍니다.

1. **"Reviews" 탭으로 이동**하여 고객 피드백을 분석합니다.

1. 다음 프롬프트를 입력하여 Copilot에게 주요 문제를 요약하도록 요청합니다.

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - Copilot이 피드백을 분석하여 고객이 지적하는 상위 3가지 문제를 표시할 것입니다. 충전 속도가 새로 나타난 문제인 것으로 보입니다.

1. 다음으로는 이 프롬프트를 입력하여 충전 속도를 언급하는 리뷰를 강조 표시합니다.

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - Copilot이 데이터 세트의 모든 관련 리뷰를 강조 표시합니다.

### Copilot Chat

이제 느린 충전 속도를 주요 문제로 확인했으니 **Copilot Chat**을 사용하여 문제를 자세히 살펴보고 잠재적인 해결책을 찾아보겠습니다.

1. 브라우저를 열고 [M365copilot.com](https://m365copilot.com/)으로 이동합니다.  

1. **웹 모드**가 선택되어 있는지 확인합니다.  

    ![웹 모드 탭을 보여 주는 스크린샷.](../Prompts/Media/web-mode.png)

1. 이 문제를 조사하기 위해 다음 프롬프트를 입력합니다.
  
    ```text
    Research common issues with EV charger speeds and identify potential causes or solutions. Summarize findings in a format suitable for a business presentation. Highlight any relevant industry benchmarks or competitor data.
    ```

   - 필요한 경우 Copilot의 요약을 검토하고 추가 컨텍스트 또는 최근 추세를 요청합니다.  

1. 선택적으로 출력을 수정합니다.
   - EV 충전기 효율성 해결을 위한 최근 추세나 기술에 대해 Copilot에 문의합니다.

    ```text
    What are the latest innovations or technologies addressing slow EV charger speeds in 2024?
    ```

   - 경쟁 업체 인사이트 요청:

    ```text
    Assuming competitors in the EV charging market are improving speed by 20% annually, suggest how we could position our CC-2001 and CC-2000 models to stay competitive.
    ```

1. Copilot에게 EV 충전기 프로젝트 책임자에게 물어볼 5가지 전략적 질문을 제안해 달라고 요청합니다.

    ```text
    Based on this information, suggest 5 strategic questions to ask the product team during our meeting tomorrow. Focus on identifying root causes, assessing risks, and brainstorming potential improvements.
    ```

### Outlook의 Copilot

이 데모에서는 Outlook의 Copilot을 사용하여 EV 충전기 제품군을 담당하는 프로젝트 책임자와 회의를 설정하고 잠재적인 솔루션에 대해 논의합니다.

1. 브라우저를 열고 [outlook.office.com](https://outlook.office.com.com/)으로 이동합니다.

1. Outlook 리본에서 Copilot 아이콘을 선택하여 Copilot 창을 엽니다.

1. 프롬프트 창에 다음을 입력합니다.

    ```text
    I need to schedule a meeting with [/Pick a colleague] tomorrow afternoon to discuss the EV charger issue reports. Can you suggest a time that works? If they are unavailable, please suggest an alternative time.
    ```

1. Copilot은 모임 시간과 날짜를 제안해야 합니다. 프롬프트에 전송하거나 편집할 수 있는 일정 항목이 표시되면 **편집**을 선택합니다.

1. 일정 정리로 전환하여 Copilot이 제안한 시간이 프로젝트 관리자에게 적합한지 확인합니다. 둘 다 시간이 비어있어야 합니다.

1. 이벤트 탭으로 다시 전환한 다음 이벤트 본문에서 **Copilot으로 초안 작성**을 선택합니다.

1. 프롬프트 창에 다음을 입력합니다.

    ```text
    Create an agenda for a meeting to discuss slow charging speeds with our CC-2001 and CC-2000 models. Include time for an introduction to the issue, a review of any available data or customer feedback, and a brainstorming session for potential solutions.  
    ```

1. **유지**를 선택하기 전에 Copilot에게 안건 초안의 길이를 늘리거나 줄이거나 어조를 변경하도록 요청할 수 있습니다.

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
