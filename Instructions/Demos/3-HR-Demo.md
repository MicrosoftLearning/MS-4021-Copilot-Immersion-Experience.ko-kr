---
demo:
  title: HR 데모
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# HR 데모

**시나리오**:  

맞춤형 직무 설명을 만들고, 이력서에 따라 후보자 명단을 작성하고, 팀을 조정하기 위한 채용 전략 초안을 작성하여 UX 디자이너 팀의 채용 프로세스를 간소화합니다.

## 데모 설정

샘플 문서는 MS-4021 GitHub 리포지토리 [여기](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)에서 찾을 수 있습니다.

이 데모에 필요한 특정 파일은 다음과 같습니다.

- [Design_Team_Responsibilities.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Graphic_Design_Institute_Design_Team_Responsibilities.docx)

- [Resume_Patti_Fernandez.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Patti_Fernandez.docx)

- [Resume_Nestor_Wilke.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Nestor_Wilke.docx)

- [Resume_Holly_Dickson.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Holly_Dickson.docx)

- [Resume_Alex_Wilber.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Alex_Wilber.docx)

> **참고:** 다운로드 후 해당 파일이 OneDrive에 동기화될 때까지 최대 10분 정도 걸릴 수 있습니다. 데모 중에 지연을 방지하려면 해당 파일을 다운로드하여 OneDrive에서 미리 사용할 수 있는지 확인합니다. 파일을 사용할 수 없는 경우 문서를 열고 데모에서 사용할 공유 파일 링크를 복사합니다.

## 데모

### Word의 Copilot

먼저 Word의 Copilot에게 작업 설명을 생성하도록 요청해 보겠습니다.

1. 브라우저 또는 데스크톱 응용 프로그램에서 Word를 엽니다.

1. **"작성하고 싶은 내용을 설명하세요"** 프롬프트 상자에 다음을 입력합니다.

    ```text
    I'm the HR Manager at the Graphic Design Institute. We've currently started the hiring process for a new Senior Animation Designer. Please review the attached document outlining the job responsibilities for this role and generate a detailed job description based on this information.

    [copy link or reference file to Design_Team_Responsibilities.docx]
    ```

    > **참고:** Design_Team_Responsibilities.docx 파일을 첨부하거나 공유 링크를 프롬프트에 직접 붙여넣어 Copilot이 관련 콘텐츠에 액세스할 수 있도록 합니다.

1. 직무 설명을 검토하고 마무리한 후 문서를 **GDI_Job_Description.docx**로 저장하고 다음 단계에 사용할 공유 URL을 복사합니다. (자동 저장을 사용하도록 설정하고 메시지가 표시되면 OneDrive 계정을 선택합니다.)

    ![링크 공유](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

다음으로 Copilot Chat을 사용하여 받은 이력서를 직무 설명과 비교하고 최적의 후보자를 식별합니다.

1. 브라우저를 열고 [M365copilot.com](https://m365copilot.com/)으로 이동합니다.

1. 작업 모드가 선택되어 있는지 확인합니다.

    ![웹 모드 탭을 보여 주는 스크린샷.](../Prompts/Media/work-mode.png)

1. 프롬프트 창에 다음을 입력합니다.

    ```text
    We are hiring for the position of Senior Animation Designer. Please analyze the attached resumes and compare them to the requirements outlined in the job description provided here: [paste link to GDI_Job_Description.docx]. Rank the candidates from most qualified to least qualified, based on their alignment with the role.

    [Resume - Patti Fernandez
    Resume - Nestor Wilke
    Resume - Holly Dickson
    Resume - Alex Wilber]
    ```

    > **참고:** 이력서를 첨부하거나 프롬프트 창에 업로드합니다. 또는 OneDrive에서 공유 링크 또는 파일 이름을 사용하여 각 파일을 참조합니다.

1. 필요에 따라 Copilot Chat에 해당 응답을 Word 문서로 내보내서 이 기능을 강조 표시하도록 요청할 수 있습니다.

### Outlook의 Copilot

마지막으로 Outlook의 Copilot을 사용하여 최고 후보자에 대해 채용 팀에 보낼 이메일 초안을 작성합니다.

1. 브라우저 또는 데스크톱 응용 프로그램에서 Outlook을 엽니다.

1. **새 이메일**을 선택합니다.

1. 리본에서 **Copilot**을 선택합니다. 드롭다운 메뉴에서 **Copilot으로 초안 작성**을 선택합니다.

1. **“이 이메일에 어떤 내용을 입력하시겠어요?”** 프롬프트 창에 다음을 입력합니다.

    ```text
    Please draft an email to the hiring team to share that Nester Wilke and Patti Fernandez align best with the Senior Animation Designer role based on their qualifications. Include a recommendation to schedule interviews for these candidates and request feedback on next steps.
    ```

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
