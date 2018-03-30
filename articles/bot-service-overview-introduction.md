---
title: About Bot Service | Microsoft Docs
description: Learn about Bot Service, a service for building, connecting, testing, deploying, monitoring, and managing bots.
author: RobStand
ms.author: kamrani
manager: kamrani
ms.topic: article
ms.prod: bot-framework
ms.date: 12/13/2017
---

# 봇 서비스에 대해

봇 서비스는 봇을 빌드하고 연결하고 테스트하며 배포와 모니터링 및 관리를 위해 필요한 모든것을 제공합니다. 
또한 봇 서비스는 봇을 개발하기 위한 Bot Builder SDK 및 각종 채널과의 연결을 위한 Bot Framework를 포함하여 봇을 만들기 위한 주요 컴포넌트들을 제공합니다. 

봇 서비스는 봇 개발을 위해 특별히 고안된 통합 환경도 제공합니다.
간단한 봇 개발을 위해서 여러분들은 별도의 에디터 나 소스제어 필요 없이도 웹 브라우저만을 통해서 코드 작성없이 봇을 만들고 연결,테스트,배포 및 관리작업을 할수도 있습니다.

봇프레임워크를 기반으로 하는 두종류의 봇 서비스 호스팅 방법을 제공합니다.

-Azure Web App 방식: 어플리케이션 서비스 관점으로 봇은 예측 가능한 비용과 확장성을 가진 미리 정의 된 용량을 할당하도록 설정할 수있는 표준 Azure Web App 방식으로 서비스할수 있습니다. 
-Azure Functions 방식: 서비스 사용 관점으로 봇은 사용한 만큼만 지불하는 Azure Functions 가격정책 기반의 Azure Functions 에서 작동되는 서버리스 방식으로 서비스 될수 있습니다. 

봇 서비스는 봇을 만들때 선택할수 있는 5개의 봇 개발 템플릿을 통해  봇 개발을 좀더 쉽고 빠르게 시작 할수 있습니다.
Visual Studio, Visual Studio Code 와 같은 통합개발환경(IDE)을 사용하거나 Azure Editor를 이용해 브라우저 기반에서도 직접 여러분의 봇을 개발 수정할수 있습니다. 

## 봇이란?
대화 방식으로 사용자와 상호작용하는 앱으로 생각하시면 좋을듯합니다. 봇은 텍스트, 카드 또는 음성으로 대화를 나눌 수 있습니다.
하나의 봇은 묻고 답하기와 같은 패턴 처럼 간단 할 수도 있고, 복잡한 대화 상태 추적과 기존 비즈니스 서비스와의 통합을 갖춘 인공 지능 기법의 정교한 조합으로 구성될수도 있습니다.

봇 서비스를 사용하면 사용자와의 다양한 유형의 상호 작용을 지원하는 봇을 만들 수 있으며 봇의 대화를 자유롭게 설계 할 수도 있습니다.
여러분의 봇은 사용자 선택이나 행동을 촉발할수 있는 보다 많은 상호 작용을 할 수 있습니다.
대화방식에는 텍스트, 이미지 및 액션 버튼이 포함 된 간단한 텍스트 문자열이나 보다 복잡한 리치 카드를 사용할 수 있습니다.
또한 자연어 상호작용 기능을 추가하여 봇이 자연스러운 표현 방법으로 사용자와 함께 상호 작용할수도 있습니다.

## 봇 서비스를 왜 사용해야 하는가?
다음은 봇 서비스의 주요기능입니다.

- **다중 개발언어 지원 **. Bot 서비스는 Bot Builder 기반에서 .NET 및 Node.js를 지원합니다. 
- **봇 템플릿 제공**. 봇 서비스 개발 템플릿을 사용하면 필요한 코드와 기능으로 봇을 신속하게 생성할수 있습니다.기본적인 봇, 사용자 입력정보를 수집하는 문서 양식 봇, LUIS를 사용하여 사용자의 의도를 이해하는 언어 이해 봇, FAQ를 처리하는 QnA 봇,사용자에게 적절히 상황별 이벤트를 알려주는 상황인지 봇 등 다양한 봇을 선택할수 있습니다.
- **외부 패키지 사용성 **. 봇은 NuGet 및 NPM을 지원하므로 봇 개발시 여러분들이 즐겨찾는 패키지를 사용할 수도 있습니다.
- **개발의 확장성 지원**. Azure 포털에서 봇을 코딩하거나 GitHub, Visual Studio Team Services 및 기타 지원되는 개발 도구를 통해 지속적인 통합을 설정하고 봇을 배포할수 있으며 Visual Studio에서도 봇을 게시 할수 있습니다.
- **다양한 채널과의 연결성**. 봇 서비스는 봇과 이를 사용하는 사람들을 연결하는 여러가지 인기있는 채널을 지원합니다. 사용자는 Skype, Facebook, Teams, Slack, SMS 및 기타 여러 가지 기능을 포함하여 봇을 구성한 모든 채널에서 봇과의 대화를 시작할 수 있습니다.
- **각종 도구 와 서비스 지원**. Bot Framework Emulator로 봇을 테스트하고 Channel Inspector로 다른 채널에서 봇의 작동을 미리보기 할수 있습니다.
- **오픈소스 지원**. Bot Builder SDK 는 오픈소스이며 [GitHub](https://github.com/microsoft/botbuilder) 를 통해 제공됩니다.

## Bot Builder 란?
[Bot Builder](bot-builder-overview-getstarted.md) 는 봇을 만들고 디버그하는 데 도움이 되는 SDK, 라이브러리, 샘플 및 도구등을 제공합니다. 봇 서비스로 봇을 만들면 봇 빌더 SDK에 의해 봇이 지원됩니다. 또한 Bot Builder SDK를 사용하여 C# 또는 Node.js를 사용하여 처음부터 봇을 만들 수 있습니다. Bot Builder 에는 봇 테스트를 위한 봇 프레임워크 에뮬레이터와 채널별로 봇의 사용자 경험을 미리보기위한 채널 인스펙터가 포함되어 있습니다.

## 다음 단계
이제 봇 서비스에 대해 개괄적으로 살펴 보았으므로 다음 단계에서는 봇으로 들어가 직접 봇을 만들어 보겠습니다.

> [!div class="nextstepaction"]
> [Create a bot with Bot Service](bot-service-quickstart.md)
