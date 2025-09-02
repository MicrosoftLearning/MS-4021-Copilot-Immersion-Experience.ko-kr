---
demo:
  title: 마케팅 데모
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 마케팅 데모

**시나리오**:  

음료 회사의 마케팅 담당자가 되어 시장 추세를 분석하고 마케팅 분석을 작성하며 새로운 소셜 미디어 캠페인을 개발하는 목표가 있다고 가정해 보겠습니다.

## 데모 설정

샘플 문서는 MS-4021 GitHub 리포지토리 [여기](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)에서 찾을 수 있습니다.

이 데모에 필요한 특정 파일은 다음과 같습니다.

- [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Promotion_Plan_for_Chai_Tea_in_Latin_America.docx)

- [Mystic_Spice_Premium_Chai_Tea_product_description.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Mystic_Spice_Premium_Chai_Tea_product_description.docx)

- [Contoso_Chai_Tea_market_trends.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_market_trends.docx)

- [Contoso_Chai_Tea_social_marketing_trends.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_social_marketing_trends.xlsx)

> **참고:** 다운로드 후 해당 파일이 OneDrive에 동기화될 때까지 최대 10분 정도 걸릴 수 있습니다. 데모 중에 지연을 방지하려면 해당 파일을 다운로드하여 OneDrive에서 미리 사용할 수 있는지 확인합니다. 파일을 사용할 수 없는 경우 문서를 열고 데모에서 사용할 공유 파일 링크를 복사합니다.

## 데모

### Word의 Copilot

Word의 Copilot를 사용하여 자세한 시장 분석 보고서를 작성하고 라틴 아메리카 시장에 맞는 창의적인 마케팅 캠페인 아이디어를 브레인스토밍합니다.

1. 브라우저 또는 데스크톱 응용 프로그램에서 Word를 엽니다.

1. **작성하고 싶은 내용을 설명하세요** 프롬프트 상자에 다음을 입력합니다.

    ```text
    Create a Market Analysis report for Mystic Spice Premium Chai Tea using the attached files. Include the product description, market trend analysis, and a promotion plan for Latin America.

    [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx], [Mystic_Spice_Premium_Chai_Tea_product_description.docx], [Contoso_Chai_Tea_market_trends.docx]
    ```

    > **참고:** 대괄호는 문서가 참조되고 있음을 나타냅니다. 문서를 참조할 때 공유 링크를 직접 붙여넣거나 OneDrive에서 사용할 수 있는 경우 파일 이름을 참조할 수 있습니다.

1. Copilot이 소셜 미디어 캠페인 아이디어를 추가하는 새 섹션을 만들도록 합니다.

    다음 프롬프트를 입력합니다.

    ```text
    Draft a new section for social media campaigns to promote Mystic Spice Premium Chai Tea. Include a brief description of 2-3 campaign ideas, each with a unique focus. For each campaign, provide a tagline that reflects its theme and resonates with our target audience of young professionals and tea enthusiasts.
    ```

1. 이 새 문서를 **LATAM_Market_Analysis.docx**로 저장합니다.

### Copilot Chat

Copilot Chat을 사용하여 제안된 소셜 미디어 캠페인의 효과를 평가하고 라틴 아메리카 시장에서 문화적 관련성에 대한 전략을 구체화합니다.

1. 브라우저를 열고 [M365copilot.com](https://m365copilot.com/)으로 이동합니다.

1. 웹 모드가 선택되어 있는지 확인합니다.

    ![웹 모드 탭을 보여 주는 스크린샷.](../Prompts/Media/web-mode.png)

1. 프롬프트 창에 다음을 입력합니다.

    ```text
    Review the social media campaigns outlined in the Market Analysis Report for Mystic Spice Premium Chai Tea.docx. Evaluate which campaign might resonate best with the LATAM market based on cultural relevance, target audience preferences, and alignment with regional trends. Provide reasons for your choice and suggest any adjustments to improve its impact.
    ```

    > **참고:** 프롬프트를 아직 제출하지 마세요. 다음 단계로 이동하여 파일을 업로드합니다.

1. **콘텐츠 추가**를 선택하고 이전 데모에서 OneDrive에 저장한 **LATAM_Market_Analysis.docx**를 업로드합니다. 그런 다음 프롬프트를 제출합니다.

    ![콘텐츠 Copilot Chat을 추가합니다.](../Demos/Media/add-content-copilot-chat.png)

1. Copilot은 집중할 캠페인 중 하나를 추천하고 개선을 위한 제안을 제공해야 합니다. 다음 프롬프트에서는, Copilot이 이 새로운 아이디어에 대한 마케팅 캠페인 슬로건을 제안하도록 해보겠습니다.

    ```text
    Generate a catchy marketing slogan for the [Campaign name - e.g., 'Morning Motivation'] campaign that highlights its unique value proposition and resonates with the LATAM market. Ensure the slogan reflects a vibrant and culturally relevant tone that appeals to young professionals.
    ```

1. 필요에 따라 마지막 프롬프트의 경우 Copilot에게 캠페인에 대한 새 비디오를 생성하도록 요청할 수 있습니다.

    Copilot Chat의 오른쪽에서 **Visual Creator 에이전트**를 선택합니다.

    ![동영상 작성자 에이전트.](../Demos/Media/video-creator.png)

    그런 다음, 다음 프롬프트를 입력합니다.

    ```text
    Create a captivating social media video for Mystic Spice Chai Tea that highlights its unique flavor and vibrant appeal. The video should feature eye-catching visuals, with colors, and themes that resonate with young professionals and tea enthusiasts.
    ```

### Excel의 Copilot

1. [Contoso_Chai_Tea_market_trends_2023.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/Contoso_Chai_Tea_market_trends_2023.xlsx)를 다운로드했는지 확인하고 웹 또는 데스크톱 응용 프로그램에서 Excel로 문서를 엽니다.

1. 리본에서 **Copilot**을 선택하여 Copilot 창을 엽니다.

1. Excel에 다음 프롬프트를 입력합니다.

    ```text
    On average, how many sales do we get per social media campaign view?
    ```

1. 다음으로, Copilot에게 매출을 소셜 미디어 참여와 비교하도록 요청합니다.

    ```text
    Can you show a correlation between social media engagement and sales?
    ```

1. 그런 후에, 다음 프롬프트를 입력합니다.

    ```text
    How many social media campaign views did we have from September to December?
    ```

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
