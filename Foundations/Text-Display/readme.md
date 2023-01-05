## Text display

**iOS, iPadOS, tvOS 및 watchOS에서 Dynamic Type을 사용하여 앱의 레이아웃이 모든 글꼴 크기에 맞게 조정되는지 테스트합니다.** 동적 유형을 사용하면 사용자가 자신에게 적합한 글꼴 크기를 선택할 수 있습니다. 설계에서 축척이 가능하고 텍스트와 문자가 모두 모든 글꼴 크기에서 읽을 수 있는지 확인합니다. 예를 들어, iPhone 또는 iPad의 경우, 설정 > 내게 필요한 옵션 > 디스플레이 & 텍스트 크기 > 큰 텍스트에서 내게 필요한 옵션 텍스트 크기를 설정하고 앱을 편안하게 읽을 수 있도록 합니다. Dynamic Type 크기 표는 각 플랫폼의 Sketch, Photoshop 및 Adobe XD Apple Design Resources에서 다운로드할 수 있습니다.
> **In iOS, iPadOS, tvOS, and watchOS, use Dynamic Type and test that your app’s layout adapts to all font sizes.**
Dynamic Type lets people pick the font size that works for them. Verify that your design can scale and that both text and glyphs are legible at all font sizes. On iPhone or iPad, for example, turn on Larger Accessibility Text Sizes in Settings > Accessibility > Display & Text Size > Larger Text, and make sure your app remains comfortably readable. You can download the Dynamic Type size tables in the Sketch, Photoshop, and Adobe XD [Apple Design Resources](https://developer.apple.com/design/resources/) for each platform.

<img width="513" alt="55" src="https://user-images.githubusercontent.com/86593582/210705433-6fd545b7-654e-49fa-876a-e139add9c040.png">

**글꼴 크기가 증가할 때 텍스트 잘라내기를 최소로 유지합니다.** 일반적으로 가장 큰 표준 글꼴 크기만큼 유용한 텍스트를 가장 큰 내게 필요한 글꼴 크기로 표시하는 것을 목표로 합니다. 사용자가 다른 보기를 열어 나머지 내용을 읽을 수 있는 경우가 아니면 스크롤 가능한 영역에서 텍스트를 자르지 마십시오. 유용한 텍스트 양을 표시하는 데 필요한 만큼의 줄을 사용하도록 레이블을 구성하여 레이블의 텍스트 잘림을 방지할 수 있습니다. 개발자 지침은 해당 링크를 참조하십시오.
> **As font size increases, keep text truncation to a minimum.**
 In general, aim to display as much useful text in the largest accessibility font size as you do in the largest standard font size. Avoid truncating text in scrollable regions unless people can open a separate view to read the rest of the content. You can prevent text truncation in a label by configuring it to use as many lines as needed to display a useful amount of text. for developer guidance, see [numberOfLines](https://developer.apple.com/documentation/uikit/uilabel/1620539-numberoflines).

**큰 글꼴 크기로 레이아웃을 조정하는 것이 좋습니다.** 글꼴 크기가 증가하면 인라인 항목과 컨테이너 경계가 텍스트를 군집화하여 읽을 수 없게 됩니다. 예를 들어, 문자나 타임스탬프와 같은 보조 항목에 줄을 맞춰 텍스트를 표시하는 경우 텍스트의 수평 공간이 줄어듭니다. 글꼴 크기가 크면 인라인 레이아웃으로 인해 텍스트가 잘리거나 텍스트 및 보조 항목이 겹칠 수 있습니다. 이 경우 텍스트가 보조 항목 위에 나타나는 스택형 레이아웃을 사용하는 것이 좋습니다. 마찬가지로, 각 열이 수평 공간을 제한하기 때문에 큰 글꼴 크기에서 텍스트의 여러 열을 읽을 수 없습니다. 이 경우 텍스트 잘림을 방지하고 전체 가독성을 향상시키기 위해 글꼴 크기가 증가할 때 열 수를 줄이는 것이 좋습니다. 개발자 지침은 해당 링크를 참조하십시오.
> **Consider adjusting layout at large font sizes.**
 When font size increases, inline items and container boundaries can crowd text, making it less readable. For example, if you display text inline with secondary items — such as glyphs or timestamps — the text has less horizontal space. At large font sizes, an inline layout might cause text to truncate or result in overlapping text and secondary items. In this case, consider using a stacked layout where the text appears above the secondary items. Similarly, multiple columns of text can become less readable at large font sizes because each column constrains horizontal space. In this case, consider reducing the number of columns when font size increases to avoid text truncation and improve overall readability. For developer guidance, see [isAccessibilityCategory](https://developer.apple.com/documentation/uikit/uicontentsizecategory/2897444-isaccessibilitycategory).

<img width="515" alt="66" src="https://user-images.githubusercontent.com/86593582/210705589-76c29695-a722-4bbc-988c-989bdabf31f3.png">

**글꼴 크기가 증가함에 따라 의미 있는 인터페이스 아이콘의 크기를 늘립니다.** 인터페이스 아이콘을 사용하여 중요한 정보를 전달하는 경우 더 큰 글꼴 크기에서도 쉽게 볼 수 있는지 확인하십시오. SF 기호를 사용하면 동적 유형 크기 변경에 따라 자동으로 크기가 조정되는 아이콘이 표시됩니다.
> **Increase the size of meaningful interface icons as font size increases.**
 If you use interface icons to communicate important information, make sure they are easy to view at larger font sizes, too. When you use [SF Symbols](https://developer.apple.com/design/human-interface-guidelines/foundations/sf-symbols/), you get icons that scale automatically with Dynamic Type size changes.

<img width="504" alt="77" src="https://user-images.githubusercontent.com/86593582/210705680-619257ad-3638-4cd6-89c2-c4c7006f6c8d.png">

**현재 글꼴 크기에 관계없이 일관된 정보 계층을 유지합니다.** 예를 들어 글꼴 크기가 매우 큰 경우에도 기본 요소를 화면 맨 위로 유지하여 사용자가 이러한 요소를 추적하지 않도록 합니다.
> **Maintain a consistent information hierarchy regardless of the current font size.**
 For example, keep primary elements toward the top of the screen even when the font size is very large, so that people don’t lose track of these elements.

**앱에서 일반 또는 무거운 글꼴 가중치를 선호합니다.** 일반, 중간, 세미볼드 또는 굵은 글꼴 가중치를 사용하는 것이 더 보기 쉽기 때문에 고려해 보십시오. 보기가 더 어려울 수 있는 초경량, 얇은 및 가벼운 글꼴 가중치는 피합니다.
> **Prefer regular or heavy font weights in your app.**
 Consider using Regular, Medium, Semibold, or Bold font weights, because they are easier to see. Avoid Ultralight, Thin, and Light font weights, which can be more difficult to see.

**사용자가 굵은 텍스트를 활성화할 때 앱이 올바르게 응답하고 좋아 보이는지 확인하십시오.** iOS, iPadOS, tvOS, watchOS에서 사람들은 텍스트와 기호를 더 쉽게 볼 수 있도록 굵은 텍스트 접근성 설정을 켭니다. 이에 대응하여, 당신의 앱은 모든 텍스트를 더 굵게 만들고 모든 글리프에 증가된 스트로크 가중치를 주어야 합니다. 시스템 글꼴 및 SF 기호는 굵은 텍스트 내게 필요한 옵션 설정에 자동으로 조정됩니다.
> **Ensure your app responds correctly and looks good when people enable bold text.**
 In iOS, iPadOS, tvOS, and watchOS, people turn on the bold text accessibility setting to make text and symbols easier to see. In response, your app should make all text bolder and give all glyphs an increased stroke weight. The system fonts and SF symbols automatically adjust to the bold text accessibility setting.

<img width="504" alt="88" src="https://user-images.githubusercontent.com/86593582/210705883-2b01555e-4fcb-49c9-bece-24f4f74c88de.png">

**사용자 지정 글꼴을 읽을 수 있는지 확인합니다.** 사용자 정의 글꼴은 때때로 읽기 어려울 수 있습니다. 브랜딩 목적이나 몰입형 게임 환경과 같은 사용자 지정 글꼴이 앱에 강제적으로 필요한 경우가 아니라면 일반적으로 시스템 글꼴을 사용하는 것이 가장 좋습니다. 사용자 지정 글꼴을 사용하는 경우 작은 크기에서도 쉽게 읽을 수 있는지 확인하십시오.
> **Make sure custom fonts are legible.**
 Custom typefaces can sometimes be difficult to read. Unless your app has a compelling need for a custom font, such as for branding purposes or to create an immersive gaming experience, it’s usually best to use the system fonts. If you do use a custom font, make sure it’s easy to read, even at small sizes.

**전체 텍스트 정당화를 피합니다.** 완전히 정당화된 텍스트에 의해 만들어진 공백은 많은 사람들이 텍스트를 읽고 집중하기 어렵게 만드는 패턴을 만들 수 있습니다. 왼쪽 정당화 또는 오른쪽에서 왼쪽 언어로 된 오른쪽 정당화는 난독증과 같은 학습 및 읽기 능력 문제가 있는 사람들에게 프레임 참조를 제공합니다.
> **Avoid full text justification.**
 The whitespace created by fully justified text can create patterns that make it difficult for many people to read and focus on the text. Left justification — or right justification in right-to-left languages — provides a framing reference for people with learning and literacy challenges, such as dyslexia.

**텍스트의 긴 구절에는 기울임꼴 또는 모두 대문자를 사용하지 마십시오.** 이탤릭체와 모든 대문자는 때때로 강조할 때 유용하지만, 이러한 스타일을 과도하게 사용하면 텍스트를 읽기가 어렵습니다.
> **Avoid using italics or all caps for long passages of text.**
Italics and all caps are great for occasional emphasis, but overuse of these styles makes text hard to read.
>
