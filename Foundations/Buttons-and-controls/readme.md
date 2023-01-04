## Buttons and controls

**모든 터치스크린 컨트롤과 대화형 요소에 최소 44x44pt의 적중 표준을 지정합니다.** 이동성이 제한된 사용자는 앱과 상호 작용할 수 있도록 더 큰 적중 대상이 필요합니다. 사람들이 포인터를 사용하는 경우에도 어떤 플랫폼에서든 너무 작은 컨트롤과 상호 작용하는 것은 답답할 수 있습니다.
> **Give all touchscreen controls and interactive elements a hit target that measures at least 44x44 pt.** People with limited mobility need larger hit targets to help them interact with your app. It can be frustrating to interact with too-small controls in any platform, even when people use a pointer.

**사용자 지정 요소의 접근성을 특성화합니다.** 시스템 API를 사용하여 보조 기술에 구성 요소가 어떻게 동작하는지 알려줄 수 있습니다. 예를 들어, 단추 또는 NS AccessibilityButton을 사용하여 보기를 단추로 특성화하는 것은 VoiceOver가 보기의 설명을 말하고 단어 단추 다음에 보기가 단추처럼 작동한다는 것을 의미합니다.
> **Characterize the accessibility of custom elements.**
 You can use system APIs to tell assistive technologies how a component behaves. For example, using [button](https://developer.apple.com/documentation/uikit/uiaccessibility/uiaccessibilitytraits/1620194-button)
 or [NSAccessibilityButton](https://developer.apple.com/documentation/appkit/nsaccessibilitybutton) to characterize a view as a button means that VoiceOver speaks the view’s description followed by the word *button* , which tells people that the view behaves like a button.

**일관된 스타일 계층을 사용하여 단추의 상대적 중요성을 전달합니다.** 단추 스타일의 일관된 계층 구조를 사용할 때 사람들은 모양에 따라 단추의 중요성을 파악할 수 있습니다. 예를 들어 iOS, iPadOS 및 TVOS에서는 보기에서 가장 가능성이 높은 작업을 수행하는 단추에 시각적으로 눈에 띄는 채워진 스타일을 사용할 수 있으며, 덜 중요한 작업을 사용하는 단추에는 회색 또는 일반 스타일을 사용할 수 있습니다.(개발자 지침은 UIButton 참조) 구성 또한 단추 모양을 설정하여 활성 단추를 주변 내용과 쉽게 구분할 수 있습니다.
> **Use a consistent style hierarchy to communicate the relative importance of buttons.**
 When you use a consistent hierarchy of button styles, people can grasp the importance of buttons based on their appearance. In iOS, iPadOS, and tvOS, for example, you can use the visually prominent filled style for the button that performs the most likely action in a view, using less prominent styles — such as gray or plain — for buttons that enable less important actions. (For developer guidance, see [UIButton.Configuration](https://developer.apple.com/documentation/uikit/uibutton/configuration).) People can also turn on Button Shapes to make it easier to distinguish active buttons from surrounding content.

시스템에서 제공하는 스위치 구성 요소를 선호합니다. SwiftUI는 노브의 위치와 채우기 색상으로 상태를 표시하는 스위치를 제공합니다. 그러나 일부 사람들에게는 라벨을 추가하면 스위치가 켜져 있는지 또는 꺼져 있는지를 더 쉽게 인식할 수 있습니다. 시스템 제공 스위치, iOS, iPadOS, TVOS 및 시계를 사용하는 경우OS는 사람들이 On/Off 라벨을 켤 때 자동으로 그 안에 있는 글리프를 표시합니다.
> **Prefer the system-provided switch component.**
 SwiftUI provides a switch that indicates its state by the position of its knob and its fill color. For some people, however, the addition of labels makes it easier to perceive whether a switch is on or off. When you use system-provided switches, iOS, iPadOS, tvOS, and watchOS automatically displays on/off glyphs within them when people turn on On/Off Labels.
>
