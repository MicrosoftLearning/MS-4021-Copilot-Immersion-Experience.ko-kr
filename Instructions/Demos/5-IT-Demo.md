---
demo:
  title: IT 데모
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# IT 데모

**시나리오**:  

IT 인프라 관리자는 회사 네트워크에 새 네트워크 보안 제품을 설치할 계획입니다.

## 데모 설정

샘플 문서는 MS-4021 GitHub 리포지토리 [여기](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)에서 찾을 수 있습니다.

이 데모에 필요한 특정 파일은 다음과 같습니다.

- [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)

> **참고:** 다운로드 후 해당 파일이 OneDrive에 동기화될 때까지 최대 10분 정도 걸릴 수 있습니다. 데모 중에 지연을 방지하려면 해당 파일을 다운로드하여 OneDrive에서 미리 사용할 수 있는지 확인합니다. 파일을 사용할 수 없는 경우 문서를 열고 데모에서 사용할 공유 파일 링크를 복사합니다.

## 데모

### Copilot Chat

먼저 Copilot에 프로젝트 구현 계획을 만들도록 요청해 보겠습니다.

1. 브라우저를 열고 [M365copilot.com](https://m365copilot.com/)으로 이동합니다.

1. 웹 모드가 선택되어 있는지 확인합니다.

    ![웹 모드 탭을 보여 주는 스크린샷.](../Prompts/Media/web-mode.png)

1. 프롬프트 창에 다음을 입력합니다.

    ```text
    You are an IT infrastructure manager at Contoso. Your task is to create a detailed project implementation plan for installing a new network security product in your corporate network. Your plan should include key milestones, resource allocation, potential risks, and a timeline to ensure successful deployment and minimal disruption to operations.
    ```

    > **참고:** 역할 기반 프롬프트는 Copilot이 사용자의 책임과 컨텍스트를 이해하고 출력의 관련성과 특이성을 개선하는 데 도움이 됩니다.

1. 이제 프로젝트 계획에 새 섹션을 추가하도록 Copilot에 요청하여 프로젝트 계획을 구체화합니다.

    다음 프롬프트를 입력합니다.

    ```text
    Please add the following sections to the existing plan: testing and QA, training, communication, documentation and reporting, stakeholder analysis, project timeline, and risk assessment and mitigation. Ensure these sections provide detailed action steps and align with the existing content. Avoid duplicating any items already included in the original plan.
    ```

1. 마지막으로, Copilot이 제안된 프로젝트 계획을 Word 문서에 출력하도록 합니다.

    다음 프롬프트를 입력합니다.

    ```text
    Please export the project plan to a Word document.
    ```

1. 생성된 Word 문서를 **Project_Implementation_Plan.docx**로 저장합니다. 문서에서 공유 URL을 복사합니다(자동 저장을 사용하도록 설정하고 메시지가 표시되면 OneDrive 계정을 선택합니다).

    ![링크 공유](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Word의 Copilot

이제 Copilot에게 이러한 전략을 확장하고 이를 구현하는 방법에 대한 제안서 초안을 작성하도록 요청할 것입니다.

1. 브라우저 또는 데스크톱 응용 프로그램에서 Word를 엽니다.

1. **작성하고 싶은 내용을 설명하세요** 프롬프트 상자에 다음을 입력합니다.

    ```text
    Using the Contoso [/CipherGuard Product Specification.docx] and the 'Project Implementation Plan' template provided in [paste in link to Project_Implementation_Plan.docx], draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template.
    ```

    > **참고:** 대괄호는 문서가 참조되고 있음을 나타냅니다.
    > 1. CipherGuard Product Specification.docx = [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)
    > 1. Project Implementation Plan.docx = 이전 데모에서 복사한 링크를 사용합니다.
    > 문서를 참조할 때 링크를 직접 붙여넣거나 OneDrive에서 사용할 수 있는 경우 파일 이름을 참조할 수 있습니다.

1. **유지**를 선택하거나 시간이 허락한다면 Copilot을 사용하여 문서를 조정하는 방법을 시연합니다.

1. 완료되면 문서를 **Contoso_Project_Plan.docx**로 저장하고 공유 URL을 복사합니다(자동 저장을 활성화하고 메시지가 표시되면 OneDrive 계정을 선택합니다).

    ![링크 공유](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### PowerPoint의 Copilot

이제 Copilot을 사용하여 Contoso CipherGuard 제품을 구현하는 새로운 제안에 따라 PowerPoint 프레젠테이션을 생성합니다.

1. 브라우저([PowerPoint.new](https://PowerPoint.new))에서 Microsoft PowerPoint를 시작하거나 데스크톱 응용 프로그램을 사용합니다.

1. 새 빈 프레젠테이션을 엽니다.

1. Copilot 창에서 "파일에서 프레젠테이션 만들기" 프롬프트를 선택합니다.

1. **Contoso_Project_Plan.docx** 문서의 공유 링크를 붙여넣고 **보내기**를 선택합니다.

    전체 프롬프트는 다음과 같이 표시되어야 합니다.

    ```text
    Create a presentation from [Link to Contoso_Project_Plan.docx].
    ```

1. Copilot은 프로젝트 계획에 따라 슬라이드를 생성하여 발표자 노트, 이미지, 슬라이드 레이아웃, 일반 민감도 레이블과 같은 기능과 함께 개요를 제공합니다.

    > **참고:** 문서의 복잡성과 슬라이드 수에 따라 슬라이드를 생성하는 데 최대 2분이 걸릴 수 있습니다.

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
