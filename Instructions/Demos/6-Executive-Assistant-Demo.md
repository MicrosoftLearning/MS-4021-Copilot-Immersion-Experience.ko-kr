---
demo:
  title: 임원 보조 데모
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 임원 보조 데모

**시나리오**:

임원을 위해 최신 실적 컨퍼런스 콜 대화록을 요약하는 임무를 맡았습니다. 이 작업에는 주요 인사이트 추출, 실행 요약 만들기, 후속 모임 준비 등이 포함됩니다.

## 데모 설정

샘플 문서는 MS-4021 GitHub 리포지토리 [여기](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)에서 찾을 수 있습니다.

이 데모에 필요한 특정 파일은 다음과 같습니다.

- [Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx)

> **참고:** 다운로드 후 해당 파일이 OneDrive에 동기화될 때까지 최대 10분 정도 걸릴 수 있습니다. 데모 중에 지연을 방지하려면 해당 파일을 다운로드하여 OneDrive에서 미리 사용할 수 있는지 확인합니다. 파일을 사용할 수 없는 경우 문서를 열고 데모에서 사용할 공유 파일 링크를 복사합니다.

## 데모 단계

### Word의 Copilot

가장 최근 실적 발표의 대화록을 검토하고 임원을 위한 핵심 사항을 요약하는 것부터 시작하겠습니다.

1. 브라우저 또는 데스크톱 응용 프로그램의 Word에서 **Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx** 파일을 선택하여 엽니다.

    > **참고:** 문서가 얼마나 방대한지, 그리고 이를 요약하는 일이 간단하지 않다는 점을 보여주기 위해 빠르게 스크롤해보는 것이 좋습니다.

1. 리본에서 Copilot 아이콘을 선택합니다.

    ![Word의 Copilot 아이콘](../Demos/Media/Copilot-in-word-ribbon.png)

1. Copilot 창이 열립니다. **이 문서에 대해 무엇이든 질문**이라고 표시된 곳에 다음 프롬프트를 입력합니다.

    ```text
    Summarize the key points from the Microsoft FY24 Second Quarter Earnings Conference Call.
    ```

1. 임원진이 Satya Nadella가 통화 중에 구체적으로 어떤 내용을 논의했는지 알고 싶어한다고 상상해 보세요. 다음 프롬프트를 사용합니다.

    ```text
    Provide a brief summary of Satya Nadella's remarks during the earnings call.
    ```

   - Copilot에 각 글머리 기호에 대한 참조가 포함되어 있어 특정 섹션으로 빠르게 이동할 수 있는 방법을 보여줍니다.  
   - 하나의 참조를 클릭하여 Copilot이 문서에서 관련 콘텐츠로 즉시 이동하는 모습을 보여줍니다.

1. 자세한 보고서를 만들려면 Copilot에 문의하세요.

    ```text
    Analyze the Microsoft FY24 Second Quarter Earnings Conference Call document to provide a comprehensive report that includes:
    - A summary of the key points from each speaker
    - Identification of the top three growth areas and their contributing factors.
    - A detailed breakdown of the financial performance, including revenue, operating income, and earnings per share.
    - Trends in AI adoption and its influence on Microsoft's business strategy.
    - A comparison of this quarter's performance with the same quarter last year, highlighting significant changes.
    - Key strategic initiatives and future outlook as discussed in the call.
    ```

    > **팁:** 이는 복잡한 프롬프트이며 Copilot이 응답을 생성하는 데 시간이 걸릴 수 있다는 점을 언급합니다.

1. Copilot이 분석을 완료하면 **복사** 아이콘을 선택하여 다음 단계를 위해 결과를 저장합니다.

    ![결과 복사](../Demos/Media/Copilot-in-word-copy-results.png)


### Copilot Chat

Word에서 제공하는 보고서는 훌륭한 출발점이지만, 이제 Copilot Chat을 사용하여 실행 요약을 작성하고자 합니다.

1. 브라우저를 열고 [M365copilot.com](https://m365copilot.com/)으로 이동합니다.

1. **웹 모드**가 선택되어 있는지 확인합니다.

    ![웹 모드 탭을 보여 주는 스크린샷.](../Prompts/Media/web-mode.png)

1. 다음 프롬프트를 사용하여 Word의 Copilot 응답을 Copilot Chat에 붙여넣습니다.

    ```text
    Based on the following information, provide an executive summary on the following information:

    [paste the Word output here]
    ```

    > **참고:** 명확하게 하기 위해 복사한 콘텐츠에서 불필요한 텍스트를 정리합니다.

1. 요약을 간결한 형식으로 구체화합니다.

    ```text
    Summarize this executive summary into a more concise format by focusing on the most critical insights and metrics for each speaker. Use a structured format with headings and bullet points to improve readability. Export to a Word document.
    ```

   - Copilot에서 문서를 내보내지 않으면 "이 요약을 Word 문서로 저장"이라는 요청을 다시 바꾸어 표시합니다.

1. 실행 요약이 완료되면 Copilot에게 다음을 요청합니다.

    ```text
    Based on the summarized executive summary, generate 5-7 concise and impactful talking points my manager can use in their next leadership call. Focus on key achievements, growth areas, and strategic priorities.
    ```

### Outlook의 Copilot

이 데모에서는 Outlook의 Copilot을 사용하여 임원진과의 회의를 설정하고 2분기 실적 전화 회의에서 일어난 모든 일을 빠르게 파악하는 방법을 보여 드리겠습니다.

1. 브라우저를 열고 [outlook.office.com](https://outlook.office.com.com/)으로 이동합니다.

1. Outlook 리본에서 Copilot 아이콘을 선택하여 Copilot 창을 엽니다.

1. 다음 프롬프트에 따라 동기화를 예약합니다.

    ```text
    I need to schedule a 30-minute meeting with [/Pick a colleague] tomorrow afternoon to discuss the Second Quarter Earnings Conference Call. Can you suggest a time that works? If they are unavailable, provide an alternative.
    ```

1. Copilot은 모임 시간과 날짜를 제안해야 합니다. 프롬프트에 전송하거나 편집할 수 있는 일정 항목이 표시됩니다. **편집**을 선택합니다.

1. 일정 정리로 전환하여 Copilot이 제안한 시간이 프로젝트 관리자에게 적합한지 확인합니다. 둘 다 시간이 비어있어야 합니다.

1. 이벤트 탭으로 다시 전환한 다음 이벤트 본문에서 **Copilot으로 초안 작성**을 선택합니다.

1. 프롬프트 창에 다음을 입력합니다.

    ```text
    I’m meeting with my boss to discuss key updates and strategic initiatives they missed from the Second Quarter Earnings Conference Call. Create an agenda to discuss financial performance, AI and technology integration, strategic acquisitions, productivity updates, and future outlook.
    ```

1. 선택적으로 **유지**를 선택하기 전에 Copilot에게 안건 초안의 길이를 늘리거나 줄이거나 어조를 변경하도록 요청할 수 있습니다.

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
