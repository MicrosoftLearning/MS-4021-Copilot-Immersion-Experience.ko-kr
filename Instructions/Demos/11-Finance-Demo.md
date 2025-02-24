---
demo:
  title: 재무 데모
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 재무 데모

**시나리오**:  

Contoso의 재무 분석가로서 EV 충전 업계에서 판매 실적 및 시장 위치를 평가하는 역할을 담당합니다. 목표는 판매 데이터를 분석하고, 인사이트를 생성하며, 팀에 대한 요약을 준비하는 것입니다.

## 데모 설정

샘플 문서는 MS-4021 GitHub 리포지토리 [여기](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)에서 찾을 수 있습니다.

이 데모에 필요한 특정 파일은 다음과 같습니다.

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

### Excel의 Copilot  

Excel의 Copilot을 사용하여 판매 데이터를 분석하고 주요 추세를 식별하며 재무 메트릭을 계산합니다.

1. Excel 시작 및 파일 열기  

1. Excel(브라우저 또는 데스크톱 응용 프로그램)에서 **Finance_Sales_Analysis.xlsx**를 엽니다.  

1. **"Sales by Product"** 탭으로 이동합니다.  

1. 다음 프롬프트를 입력하고 Copilot을 사용하여 테이블을 정렬합니다.  

    ```text
    Sort the table by date in descending order, from the most recent to the oldest entry.
    ```  

    - Copilot은 테이블을 정렬하고 데이터 집합을 업데이트합니다.  
    - 정렬 후 **"적용"** 을 선택합니다.  

1. '총 수익' 열 삽입  

    Copilot 창에서 다음 프롬프트를 사용합니다.  

    ```text
    Add a new column named 'Total Revenue'. Populate it by multiplying 'Units Sold' by 'Product Price' for each row.
    ```  

    - Copilot이 새 열을 만들고 수식을 적용합니다.  
    - **"열 삽입"** 을 선택합니다.  

1. 2024년 판매 요약 테이블 생성  

    Copilot 창에서 다음 프롬프트를 입력합니다.  

    ```text
    Create a summary table for total sales in 2024. The table should include Product ID, total units sold, and total revenue.
    ```  

    - Copilot은 요약 테이블을 생성합니다.  
    - **"새 데이터 시트에 추가"** 를 선택하여 테이블을 별도로 저장합니다.  
    - 테이블에 **2024년 데이터만** 포함되는지 확인합니다.  
    - **"Sales by Product"** 탭으로 돌아가거나 Copilot의 마지막 응답 아래에서 **"데이터로 돌아가기"** 를 선택합니다.  

1. 베스트셀러 제품 식별  

    Copilot 창에서 다음 프롬프트를 입력합니다.  

    ```text
    Identify the product ID with the highest total revenue in 2024. Provide both total revenue and total units sold for better comparison.
    ```  

    - Copilot은 데이터 세트를 분석하고 가장 많이 판매되는 제품을 제공합니다.
    - **"Sales by Product"** 탭으로 돌아가거나 Copilot의 마지막 응답 아래에서 **"데이터로 돌아가기"** 를 선택합니다.  

1. 수익별로 고객 정렬

    - Excel에서 **"Customers"** 시트로 이동합니다.

    Copilot 창에서 다음 프롬프트를 입력합니다.  

    ```text
    Sort the 'Customers' tab by annual revenue in descending order.
    ```  

    - Copilot은 **연간 수익**을 기준으로 고객을 정렬합니다.  
    - 정렬 후 **"적용"** 을 선택합니다.  

1. 고객당 평균 수익 계산

    다음 프롬프트를 입력합니다.  

    ```text
    Calculate the average revenue per customer.
    ```  

    - Copilot이 평균을 계산하여 결과를 더합니다.  
    - **"행 삽입"** 을 선택하여 평균 수익 값을 저장합니다.  

1. 가장 많은 전력을 사용하는 산업 찾기  

    Copilot 창에서 다음 프롬프트를 입력합니다.  

    ```text
    Analyze the data to determine which industry has the highest total power consumption. Provide the industry name and total power usage.
    ```  

    - Copilot은 데이터를 처리하고 전력 소비가 가장 많은 산업을 제공합니다.

1. 문서를 저장합니다. 문서에서 공유 URL을 복사합니다(자동 저장을 사용하도록 설정하고 메시지가 표시되면 OneDrive 계정을 선택합니다).

    ![링크 공유](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

Copilot Chat을 사용하여 재무 성과를 업계 벤치마크 및 경쟁업체와 비교합니다.

1. 브라우저를 열고 [M365copilot.com](https://m365copilot.com/)으로 이동합니다.

1. 웹 모드가 선택되어 있는지 확인합니다.

    ![웹 모드 탭을 보여 주는 스크린샷.](../Prompts/Media/web-mode.png)

1. 프롬프트 창에 다음을 입력합니다.

    ```text
    Our total revenue for [EV chargers] exceeded $50,000,000 for firth half of 2024. Compare this to the industry average and provide insights on whether we are above or below industry standards. If possible, include market share estimates and trends
    ```

1. 이제 Copilot Chat에 이를 경쟁업체와 비교해 달라고 요청합니다.

    ```text
    Summarize the key financial statements of two major competitors in the [EV charging] industry. Include revenue, net profit, and any other relevant financial insights. If available, provide comparisons to our financial performance.
    ```

1. 마지막으로, Copilot에게 채팅 기록을 Word 문서로 내보내도록 요청합니다.

    ```text
    Export this conversation, including financial insights, to a Word document for further review.
    ```

1. 다운로드할 연결된 파일을 선택한 다음 문서를 엽니다.

1. **편집 사용**을 선택합니다.

1. 파일 제목은 "**Charging_industry_Financial_Summary.docx**"와 유사해야 합니다. 문서에서 공유 URL을 복사합니다(자동 저장을 사용하도록 설정하고 메시지가 표시되면 OneDrive 계정을 선택합니다).

    ![링크 공유](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Word의 Copilot

Word의 Copilot을 사용하여 재무 인사이트를 이메일에 요약하여 팀에 전달합니다.

1. 브라우저 또는 데스크톱 응용 프로그램에서 새 Word 문서를 엽니다.

1. **"작성하고 싶은 내용을 설명하세요"** 프롬프트 상자에 다음을 입력합니다.

    ```text
    Draft an email to my team summarizing the key insights from [Charging_industry_Financial_Summary.docx].
    ```

    > **참고:** 이전 작업에서 만든 Charging_industry_Financial_Summary.docx 파일을 첨부하거나 공유 링크를 프롬프트에 직접 붙여넣어 Copilot이 관련 콘텐츠에 액세스할 수 있도록 합니다.

1. Copilot의 출력을 검토합니다. **유지**를 선택하기 전에 Copilot에게 질문하여 응답을 구체화합니다.

    ```text
    Shorten this email draft
    ```

1. 기타 선택적 개선 사항:

    - Copilot에게 보다 전문적인 어조를 위해 섹션을 다시 작성해달라고 요청합니다.
    - 추가 섹션을 사용하여 확장합니다.
    - 덜 형식적으로 만들기

1. 완료되면 **유지**를 선택할 수 있습니다.
