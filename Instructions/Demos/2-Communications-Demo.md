---
demo:
  title: ' 데모'
---

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

#  데모

**시나리오**:  
유명 뉴스 매체의 기자와의 인터뷰를 준비하고 있습니다. 목표는 기자에 대한 인사이트를 수집하고, 대상 그룹에게 전할 메시지를 조정하고, 잠재적인 인터뷰 질문에 대한 정교한 답변을 개발하는 것입니다. Copilot이 이 프로세스 전반에 걸쳐 도움을 줍니다.

## 데모 설정

이 데모에는 샘플 문서가 필요하지 않습니다.

## 데모

### Copilot Chat

1. 브라우저를 열고 [M365copilot.com](https://m365copilot.com/)으로 이동합니다.

1. 웹 모드가 선택되어 있는지 확인합니다.

    ![웹 모드 탭을 보여 주는 스크린샷.](../Prompts/Media/web-mode.png)

1. 프롬프트 창에 다음을 입력합니다.

    ```text
    I am going to be interviewed by {Reporter Name} from {News Outlet Name} about {Specific Topic, e.g., 'sustainability in tech'}. What are some key things I should know about their previous work and approach to this topic?
    ```

1. 뉴스 매체의 대상 그룹을 이해하여 접근 방식을 조정합니다. Copilot을 사용하여 인구 통계 및 관심사를 분석합니다.

    다음 프롬프트를 입력합니다.

    ```text
    Tell me about {News Outlet Name}'s demographic and their audience's interests and knowledge level on {Specific Topic}.
    ```

1. Copilot에게 메시지를 표시하여 잠재적인 인터뷰 질문을 예상합니다.

    다음 프롬프트를 입력합니다.

    ```text
    Generate the top 10 questions that {Reporter Name} might ask in my interview. They should be informed by the research conducted above and crafted to be conversational yet concise.
    ```

1. 예상되는 질문에 대한 답변 초안을 작성하고 테이블 형식으로 구성합니다. 나중에 사용할 수 있는 Word 문서에 테이블을 저장합니다.

    다음 프롬프트를 입력합니다.

    ```text
    Draft answers to the questions in a table format. Save the table with questions and answers into a Word document.
    ```

    > **참고:** 이 Word 문서는 다음 데모에서 참조됩니다.

### Word의 Copilot

이제 Copilot Chat에서 생성된 인사이트 및 초안이 구체화되어 Word의 FAQ로 구성됩니다.

1. 5단계의 Q&A 테이블을 사용하여 저장된 Word 문서를 엽니다.

1. 문서 본문에서 아무 곳이나 선택하고 Copilot 아이콘을 선택합니다. 다음 프롬프트를 입력합니다.

    ```text
    Create an FAQ for a technical audience who are new to {Specific Topic}. Include the top 15 questions for publishing on a blog. Leverage the questions and answers from this document.
    ```

1. FAQ를 검토하고 구체화합니다. 다음을 확인합니다.
    - 정확하고 관련성이 있으며 간결한 답변을 포함합니다.
    - 명확성과 가독성을 위해 논리적으로 구조화됩니다.

1. FAQ를 반영합니다. 정보에 차이가 있나요? 대상 그룹에 포괄적인 가치를 제공하기 위해 필요에 따라 질문을 추가합니다.

[인덱스로 돌아가기](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
