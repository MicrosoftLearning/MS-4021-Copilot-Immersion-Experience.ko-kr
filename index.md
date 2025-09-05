---
title: 온라인 호스팅 지침
permalink: index.html
layout: home
---

아래에는 각 데모의 하이퍼링크 목록이 나와 있습니다.

## 데모

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| 데모 |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## 몰입 환경을 위한 샘플 프롬프트

#### [임원](https://learn.microsoft.com/en-us/training/modules/envision-new-ideas-with-microsoft-365-copilot/)(Microsoft Learn로 리디렉션)

#### [연락](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Communications-Prompts.html)

#### [HR](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/HR-Prompts.html)

#### [Sales](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Sales-Prompts.html)

#### [IT](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/IT-Prompts.html)

#### [임원 도우미](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/EA-Prompts.html)

#### [비즈니스 관리자](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Business-Manager-Prompts.html)

#### [Marketing](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Marketing-Prompts.html)

#### [작업](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Operations-Prompts.html)

#### [Legal](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Legal-Prompts.html)
          

#### [Finance](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Finance-Prompts.html)

#### [에이전트 - 비즈니스 사용자](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/EU-Agents.html)

#### [에이전트 - 임원](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Exec-Agents.html)