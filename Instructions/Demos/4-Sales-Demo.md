---
demo:
  title: 샘플 데모
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 샘플 데모

**시나리오**:  

EV 충전 회사의 영업 담당자로서 내년도 전략 계획을 수립하고 있다고 가정해 보겠습니다.

## 데모 설정

샘플 문서는 MS-4021 GitHub 리포지토리 [여기](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)에서 찾을 수 있습니다.

이 데모에 필요한 특정 파일은 다음과 같습니다.

- [Charger_sales_report_2022-2024.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Charger_sales_report_2022-2024.xlsx)

> **참고:** 다운로드 후 해당 파일이 OneDrive에 동기화될 때까지 최대 10분 정도 걸릴 수 있습니다. 데모 중에 지연을 방지하려면 해당 파일을 다운로드하여 OneDrive에서 미리 사용할 수 있는지 확인합니다. 파일을 사용할 수 없는 경우 문서를 열고 데모에서 사용할 공유 파일 링크를 복사합니다.

## 데모

### Copilot Chat

1. 브라우저를 열고 [M365copilot.com](https://m365copilot.com/)으로 이동합니다.

1. 웹 모드가 선택되어 있는지 확인합니다.

    ![웹 모드 탭을 보여 주는 스크린샷.](../Prompts/Media/web-mode.png)

1. 먼저 Copilot에게 주요 메트릭을 조사하도록 요청해 보겠습니다. **Copilot Chat** 프롬프트 필드에서 다음을 입력합니다.

    ```text
    What is the ratio of EV cars to EV chargers by region in the US for the past 3 years? Please show it in a table organized by region.
    ```

    ![Copilot Chat EV 충전기 프롬프트를 보여 주는 스크린샷.](../Demos/Media/copilot-chat-ev-charger-prompt.png)

1. 이제 국가별 추세를 회사의 판매 실적과 비교해 보겠습니다. 제공된 데이터 세트를 업로드하고 Copilot에 데이터를 시각화하도록 요청합니다.

    프롬프트 필드에 다음을 입력합니다.

    ```text
    I need to know the quarterly trends for each of our sales regions. Create a quarterly revenue line graph for the past 2 years based on:
    ```

    > **참고:** 프롬프트를 아직 제출하지 마세요. 다음 단계로 이동하여 파일을 업로드합니다.

1. **콘텐츠 추가**를 선택하고 [**Charger_sales_report_2022-2024.xlsx**](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/Resourcefiles/Charger_sales_report_2022-2024.xlsx)을 업로드합니다. 그런 다음 프롬프트를 제출합니다.

    ![콘텐츠 Copilot Chat을 추가합니다.](../Demos/Media/add-content-copilot-chat.png)

1. 한 단계 더 나아가 Copilot에게 Word 문서로 내보낸 추천을 요청해 보겠습니다.

    프롬프트 필드에 다음을 입력합니다.

    ```text
    Based on the trend, suggest two ways I can increase EV charger sales in the Mountain and Midwest regions. Export the recommendations to a Word Document.
    ```

1. Copilot이 제공하는 새 Word 문서에 대한 하이퍼링크를 선택하여 열 수 있습니다.

1. 열면 **편집 사용**을 선택한 다음 "자동 저장"을 켭니다. 메시지가 표시되면 OneDrive 계정을 선택합니다.


### Word의 Copilot

이제 Copilot에게 이러한 전략을 확장하고 이를 구현하는 방법에 대한 제안서 초안을 작성하도록 요청할 것입니다.

1. 이전 데모에서 생성된 Word 문서가 브라우저 또는 데스크톱 응용 프로그램에서 열려 있지 않다면 지금 엽니다.

1. 문서 본문에서 아무 곳이나 선택하고 Copilot 아이콘을 선택합니다.

    다음 프롬프트를 입력합니다.

    ```text
    Draft a detailed proposal on how we could implement each of the strategies outlined in this document. Ensure the plan is actionable and includes resource requirements, timelines, and key stakeholders.
    ```

1. **유지**를 선택하거나 시간이 허락한다면 Copilot을 사용하여 문서를 조정하는 방법을 시연합니다.

1. 완료되면 문서를 **EV Sales Proposal.docx**로 저장하고 다음 단계에서 사용할 공유 URL을 복사합니다(자동 저장을 활성화하고 OneDrive 계정을 선택합니다).

    ![링크 공유](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

    > **강사 팁:** 이 단계를 사용하여 Copilot이 이전 결과물을 기반으로 아이디어를 응집력 있는 제안으로 구체화하는 방법을 시연합니다.

### PowerPoint의 Copilot

1. 브라우저([PowerPoint.new](https://PowerPoint.new))에서 Microsoft PowerPoint를 시작하거나 데스크톱 응용 프로그램을 사용합니다.

1. 새 빈 프레젠테이션을 엽니다.

1. Copilot 창에서 "파일에서 프레젠테이션 만들기" 프롬프트를 선택합니다.

1. "다음에서 프레젠테이션 만들기" 뒤에 있는 **EV Sales Proposal.docx** 링크를 붙여넣고 **보내기**를 선택합니다.

    전체 프롬프트는 다음과 같이 표시되어야 합니다.

    ```text
    Create a presentation from [Link to EV Sales Proposal.docx].
    ```

1. Copilot은 EV 영업 제안서를 기반으로 슬라이드를 생성하기 시작하여 발표자 메모, 이미지, 슬라이드 레이아웃 및 일반 민감도 레이블과 같은 기능과 함께 개요를 제공합니다.

    > **참고:** 문서의 복잡성과 슬라이드 수에 따라 슬라이드를 생성하는 데 최대 2분이 걸릴 수 있습니다.

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
