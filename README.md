# Apple-Human-Interface-Guidelines
---
### 애플의 HIG(Human Interface Guidelines) 문서를 정리합니다.

취업준비를 하며 여러 iOS개발자 채용 공고를 보았습니다. RxSwift, MVVM 만큼이나 많이 볼 수 있었던 단어가 있었습니다. 바로 **"HIG"** 입니다. 많은 기업들은 HIG에 대해 이해를 하고 있는 개발자를 우대사항으로 두고 있습니다. 즉, **HIG는 iOS개발자가 되기 위해 알아야 하는 중요한 공식 문서라는 뜻** 입니다.

HIG 공식 문서 링크: https://developer.apple.com/design/human-interface-guidelines/guidelines/overview

---

**Q: HIG가 무엇인가?**

A: Apple은 사용자가 익숙한 방식으로 앱을 사용하는 것을 추구합니다. 따라서 앱의 모든 요소에 대해 원칙을 정해두었는데 그 문서가 바로 HIG입니다. 공식문서에 따르면, HIG는 모든 Apple 플랫폼에서 개발하기를 원하는 디자이너와 개발자를 위한 종합 리소스라고 합니다. 쉽게 이야기하면 일관된 사용자 경험, 익숙한 방식을 제공하기 위해 애플의 제품에서 구동될 어플을 제작할 때 지켜야할 가이드라인이라고 할 수 있을것 같습니다.

**Q: HIG는 왜 중요한가?**

A: 중요한 이유는 많습니다, 그 중에서 몇 가지만 살펴보자면,
- 애플의 identity를 이해하여 앱을 설계할 수 있고, 협업 시에도 분명한 기준이 되어 원활한 소통이 가능합니다.
- HIG 기준에 맞추면 사용자들이 쓰기 편한 앱이 됩니다.
- HIH를 지키지 않으면 스토어에서 리젝사유가 될 수 있습니다.

이번 레포에는 HIG의 모든 문서를 정리해보려고 합니다.

---
# Designing for iOS

### 사람들은 어디에서나 이동 중에도 연결을 유지하고, 게임을 하고, 미디어를 보고, 작업을 수행하고, 개인 데이터를 추적할 수 있도록 아이폰에 의존합니다.
> **People depend on their iPhone to help them stay connected, play games, view media, accomplish tasks, and track personal data in any location and while on the go.**
>

&nbsp;&nbsp; 

훌륭한 아이폰 경험은 사람들이 가장 중요하게 여기는 플랫폼과 장치 기능을 통합합니다. 당신의 디자인이 iOS에서 편한함을 느낄 수 있도록 다음과 같은 기능을 통합하는 방법에 우선순위를 두십시오.
> Great iPhone experiences integrate the platform and device capabilities that people value most. To help your design feel at home in iOS, prioritize the following ways to incorporate these features and capabilities.
>


- 최소한의 상호 작용으로 보조 세부 정보와 작업을 검색할 수 있도록 하는 동시에 화면 제어 수를 제한하여 사람들이 기본 작업과 콘텐츠에 집중할 수 있도록 지원합니다.
    
    > Help people focus on primary tasks and content by limiting the number of onscreen controls while making secondary details and actions discoverable with minimal interaction.
    >
    
&nbsp;&nbsp;  
    
- 장치 방향, 다크 모드 및 동적 유형과 같은 모양 변화에 원활하게 적응하여 사용자가 자신에게 가장 적합한 구성을 선택할 수 있습니다.
    
    > Adapt seamlessly to appearance changes — like device orientation, Dark Mode, and Dynamic Type — letting people choose the configurations that work best for them.
    >
    
&nbsp;&nbsp; 
    
- 사용자가 일반적으로 단말기를 잡는 방식을 지원하는 상호 작용을 활성화합니다. 예를 들어 조정기가 디스플레이 중간 또는 하단 영역에 있을 때 사용자가 조정기에 더 쉽게 접근할 수 있는 경향이 있으므로 사용자가 뒤로 이동하거나 목록 행에서 작업을 시작할 수 있도록 하는 것이 특히 중요합니다.
    
    > Enable interactions that support the way people usually hold their device. For example, it tends to be easier and more comfortable for people to reach a control when it’s located in the middle or bottom area of the display, so it’s especially important let people swipe to navigate back or initiate actions in a list row.
    >
    
&nbsp;&nbsp; 
    
- 사용자의 허가를 받아 플랫폼 기능을 통해 사용 가능한 정보를 통합하여 사용자에게 데이터를 입력을 요청하지 않고도 사용자 경험을 향상시킬 수 있습니다. 예를 들어 결제를 수락하거나 생체 인증을 통해 보안을 제공하거나 장치의 위치를 사용하는 기능을 제공할 수 있습니다.
    
    > With people’s permission, integrate information available through platform capabilities in ways that enhance the experience without asking people to enter data. For example, you might accept payments, provide security through biometric authentication, or offer features that use the device’s location.
    >
   
