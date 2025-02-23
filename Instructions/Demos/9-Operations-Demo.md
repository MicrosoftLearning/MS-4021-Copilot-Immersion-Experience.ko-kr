---
demo:
  title: 작업 데모
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 작업 데모

## 시나리오

Contoso의 Operations Manager는 공급업체 조달 및 프로젝트 실행을 담당합니다. 목표는 과거 RFP를 검토하고, 주요 선택 기준을 추출하고, 예정된 이니셔티브를 위한 새 RFP 초안을 작성하는 것입니다.

## 데모 설정

샘플 문서는 MS-4021 GitHub 리포지토리 [여기](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)에서 찾을 수 있습니다.

이 데모에 필요한 특정 파일은 다음과 같습니다.

- [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

- [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

- [Contoso_RFP_Template.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_RFP_Template.docx)

> **참고:** 다운로드 후 해당 파일이 OneDrive에 동기화될 때까지 최대 10분 정도 걸릴 수 있습니다. 데모 중에 지연을 방지하려면 해당 파일을 다운로드하여 OneDrive에서 미리 사용할 수 있는지 확인합니다. 파일을 사용할 수 없는 경우 문서를 열고 데모에서 사용할 공유 파일 링크를 복사합니다.

## 데모

### Word의 Copilot

먼저 RFP(제안 요청서) 문서에 대한 몇 가지 질문을 Word의 Copilot에게 물어보겠습니다.

1. 브라우저 또는 데스크톱 응용 프로그램에서 Word를 엽니다.
1
1. 다음 문서를 엽니다. [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

1. Word 리본에서 Copilot 아이콘을 선택하여 채팅 창을 엽니다.

    ![작업 모드 탭을 보여 주는 스크린샷.](../Demos/Media/copilot-ribbon-word.png)

1. 채팅 창에서 프롬프트를 선택하거나 입력합니다.

   ```text
   Summarize this document
   ```

1. 그리고 다음 프롬프트를 입력합니다.

   ```text
   Analyze this document and generate a categorized list of required items needed to create an RFP.
   ```

1. 다음으로, 다음을 입력하여 RFP 템플릿을 만들도록 Copilot에 요청합니다.

   ```text
   Analyze this document and create an RFP template based on the content.
   ```

    > **참고:** 다음 데모에서 미리 만든 템플릿 문서를 사용하므로 생성된 콘텐츠를 복사할 필요가 없습니다. 그러나 대상 그룹과 관련된 경우 Copilot의 응답을 복사하거나 문서에 삽입하는 방법을 보여줄 수 있습니다.

### Copilot Chat

이제 RFP 문서를 요약하고 RFP 템플릿을 만들었으므로 Copilot Chat을 사용하여 새 RFP에 대한 프로젝트 요구 사항을 요약해 보겠습니다.

1. 브라우저를 열고 [M365copilot.com](https://m365copilot.com/)으로 이동합니다.  

1. **웹 모드**가 선택되어 있는지 확인합니다.

    ![웹 모드 탭을 보여 주는 스크린샷.](../Prompts/Media/web-mode.png)

1. 다음 프롬프트를 입력합니다.

   ```text
   Summarize [Project_Guidelines_Contoso.docx] highlighting the key objectives, scope, implementation timeline, budget, compliance needs, and vendor selection criteria in a bulleted list.
   ```

    > **참고:** 대괄호는 문서가 참조되고 있음을 나타냅니다. 링크 사용: [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

1. 다음으로, Copilot에게 공급업체 선택 기준을 추출하도록 요청합니다.

   ```text
   Extract and summarize the key vendor selection criteria from this document, including weight percentages and evaluation factors.
   ```

1. 그런 다음, 프로젝트 지침에 따라 RFP를 만들도록 Copilot에 요청합니다.

   ```text
   Using the project requirements outlined above, draft an RFP using the following template: [Contoso_RFP_Template.docx].
   ```

    > **참고:** 대괄호는 문서가 참조되고 있음을 나타냅니다.

1. 다음 데모에서 사용할 수 있도록 **생성된 RFP를 클립보드에 복사합니다.**

1. 필요에 따라 생성된 RFP를 Word 문서로 내보내도록 Copilot에 요청합니다.

### Outlook의 Copilot

마지막으로 Outlook의 Copilot을 사용하여 잠재적 공급업체에게 보낼 RFP 문서를 요약하는 이메일 초안을 작성합니다.

1. 브라우저 또는 데스크톱 응용 프로그램에서 Outlook을 엽니다.

1. **새 이메일**을 선택합니다.

1. 리본에서 **Copilot**을 선택합니다. 드롭다운 메뉴에서 **Copilot으로 초안 작성**을 선택합니다.

1. **“이 이메일에 어떤 내용을 입력하시겠어요?”** 프롬프트 창에서 다음을 입력합니다.

   ```text
   Draft an email to potential suppliers summarizing the RFP below:

   [paste contents of RFP]
   ```

    > **참고:** 이전 데모에서 복사한 RFP 콘텐츠를 붙여넣습니다.

1. 초안이 생성되면 **조정** 기능을 사용하여 어조, 길이 또는 형식 수준을 수정할 수 있습니다.

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
