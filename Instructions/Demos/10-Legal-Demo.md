---
demo:
  title: 법적 데모
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 법적 데모

**시나리오**:  

Contoso의 법률 고문은 회사의 AI 이력서 스크리닝 소프트웨어가 EU AI 법을 준수하는지 여부를 평가하는 역할을 담당합니다. 고문의 목표는 법적 위험성을 연구하고, 실행 요약 초안을 작성하고, 리더십에 권장 사항을 전달하는 것입니다.

## 데모 설정

이 데모에는 샘플 문서가 필요하지 않습니다.

## 데모

### Copilot Chat

먼저 EU 인공 지능법과 Contoso의 AI 채용 도구에 미치는 잠재적 영향을 조사해 보겠습니다.

1. 브라우저를 열고 [M365Copilot.com](https://m365Copilot.com/)으로 이동합니다.

1. **웹 모드**가 선택되어 있는지 확인합니다.

    ![웹 모드 탭을 보여 주는 스크린샷.](../Prompts/Media/web-mode.png)

1. 프롬프트 창에 다음을 입력합니다.

    ```text
      Contoso is launching an AI Resume Screening Software to evaluate job applicants. As a legal advisor, I need to assess whether it complies with the EU Artificial Intelligence Act. Summarize key provisions related to AI in hiring, compliance requirements for high-risk systems, and potential legal risks.
    ```

1. Copilot의 응답을 검토하고 관련 법적 위험 및 규정 준수 요구 사항을 메모합니다.

1. 이제 더 많은 정보를 수집하기 위해 Copilot에 일련의 후속 질문을 해보겠습니다.

    ```text
    Does the AI Act classify resume screening software as a high-risk AI system?
    ```

    ```text
    What are the key obligations for high-risk AI systems under the AI Act?
    ```

    ```text
    Are there any exemptions in the AI Act that could apply to Contoso’s system?
    ```

1. 이제 Copilot에게 지금까지의 모든 정보를 요약하도록 요청합니다.

    ```text
    Summarize all the information we've discussed into a structured list, ensuring no key details are missed. Then, export the summary to a Word document
    ```

1. Copilot이 제공하는 새 Word 문서에 대한 하이퍼링크를 선택하여 열 수 있습니다.

1. 열면 **편집 사용**을 선택한 다음 "자동 저장"을 켭니다. 메시지가 표시되면 OneDrive 계정을 선택합니다.

1. 다음 단계에서 사용할 공유 URL을 복사합니다. (자동 저장을 사용하도록 설정하고 메시지가 표시되면 OneDrive 계정을 선택합니다.)

    ![링크 공유](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Word의 Copilot

이제 Contoso의 리더십에 대한 법적 위험 및 권장 사항을 요약한 실행 요약 초안을 작성합니다.

1. 브라우저 또는 데스크톱 응용 프로그램에서 Word의 새 인스턴스를 엽니다.

1. **"작성하고 싶은 내용을 설명하세요"** 프롬프트 상자에 다음을 입력합니다.

    ```text
    Reference the following document [Link to exported Copilot Chat summary from the first task] and draft an executive summary outlining key legal risks, compliance requirements, and recommendations for Contoso’s AI Resume Screening Software.
    ```

    > **참고:** 문서를 첨부하거나 공유 링크를 프롬프트에 직접 붙여넣어 Copilot이 관련 콘텐츠에 액세스할 수 있는지 확인합니다.

1. Copilot의 출력을 검토합니다. **유지**를 선택하기 전에 Copilot에게 질문하여 응답을 구체화합니다.

    ```text
    Add a section on the potential business impact of these compliance requirements.
    ```

1. 기타 선택적 개선 사항:

    - Copilot에게 보다 전문적인 어조를 위해 섹션을 다시 작성해달라고 요청합니다.
    - 요약이 너무 길면 더 짧고 간결한 버전을 요청합니다.
    - 추가 섹션을 사용하여 확장합니다.

1. 문서를 검토하고 마무리한 후 **생성된 실행 요약을 클립보드에 복사하여** 다음 데모에서 사용할 수 있도록 합니다.

### Outlook의 Copilot

마지막으로 Contoso 임원진에게 조사 결과와 다음 단계를 요약한 이메일 을 작성합니다.

1. 브라우저 또는 데스크톱 응용 프로그램에서 Outlook을 엽니다.

1. **새 이메일**을 선택합니다.

1. 리본에서 **Copilot**을 선택합니다. 드롭다운 메뉴에서 **Copilot으로 초안 작성**을 선택합니다.

1. **“이 이메일에 어떤 내용을 입력하시겠어요?”** 프롬프트 창에서 다음을 입력합니다.

   ```text
    Draft an email to Contoso’s executive leadership summarizing our legal assessment of the AI Resume Screening Software under the EU AI Act. Use the following executive summary as a reference.

    [paste Executive Summary from the previous task]

    Conclude the email with a request for leadership’s input on the next steps, including a proposed compliance review meeting.
   ```

    > **참고:** 이전 데모에서 복사한 실행 요약 내용을 붙여넣습니다.

1. 초안이 생성되면 **조정** 기능을 사용하여 어조, 길이 또는 형식 수준을 수정할 수 있습니다.

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
