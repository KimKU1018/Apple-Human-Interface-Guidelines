## Gestures

**플랫폼 제스처를 무시하지 마십시오.** 사용 중인 앱에 관계없이 Notification Center를 표시하도록 아래로 쓸어내리거나 시스템 설정에서 사용할 수 있는 macOS 트랙패드 제스처와 같은 시스템 제스처가 작동하기를 기대합니다.
> **Don’t override the platform gestures.**
 People expect system gestures — such as swiping down to reveal Notification Center or the macOS trackpad gestures available in System Settings — to work regardless of the app they’re using.


**일반적인 상호작용을 위해 단순화된 제스처를 선호합니다.** 여러 손가락 제스처, 길게 누르거나 버튼을 반복적으로 누르는 것과 같은 복잡한 제스처는 많은 사람들에게 어려울 수 있습니다. 가능한 한 간단한 제스처를 사용하면 앱과 상호작용하는 모든 사용자의 겨ㅇ험이 향상됩니다.
> **Prefer simplified gestures for common interactions.**
Complex gestures such as multifinger gestures, long presses, or repeated button presses can be challenging for many people. Using the simplest gestures possible improves the experience for everyone who interacts with your app.


**제스처 기반 작업을 수행하는 다른 방법을 제공합니다.** 특정 제스처를 수행할 수 없는 사용자를 위한 옵션을 포함합니다. 예를 들어, 스와이프를 사용하여 테이블의 행을 삭제하는 경우 편집 모드를 통해 또는 항목 세부 정보 보기에서 삭제 단추를 제공하여 항목을 삭제할 수도 있습니다.
> **Provide alternative ways to perform gesture-based actions.**
 Include an option for people who may not be able to perform a specific gesture. For example, if swiping deletes a row in a table, you can also provide an alternative way to delete items through an edit mode or by offering a Delete button in an item detail view.
<img width="249" alt="11" src="https://user-images.githubusercontent.com/86593582/210487085-59d5cce0-6eef-4617-86d1-208d5a7eb93d.png">

**가능한 경우 두 가지 이상의 물리적 상호 작용을 통해 앱의 핵심 기능에 액세스할 수 있도록 합니다.** 예를 들어, iPhone과 iPad의 Camera를 사용하면 화면 버튼을 누르거나 장치의 볼륨을 낮춰서 사진을 찍을 수 있습니다. 이러한 대체 상호 작용은 사진 촬영을 모두에게 더 편리하게 할 뿐만 아니라 그립 강도나 손재주가 제한된 사람들에게도 옵션을 제공합니다.
> **When possible, make your app’s core functionality accessible through more than one type of physical interaction.**
 For example, Camera on iPhone and iPad lets people take a photo by tapping the onscreen button or by pressing the device's volume down button. In addition to making photo-capture more convenient for everyone, these alternative interactions provide options to people who might have limited grip strength or dexterity.
>

iOS 또는 iPadOS 앱에서 드래그 앤 드롭에 액세스 할 수 있습니다. 접근성 API를 사용하여 앱에서 드래그 소스와 드롭 대상을 식별할 때 보조 기술은 사람들이 화면 항목을 드래그 앤 드롭하는 것을 도울 수 있습니다. 개발자 지침은 [accessibilityDragSourceDescriptors](https://developer.apple.com/documentation/objectivec/nsobject/2891001-accessibilitydragsourcedescripto) 그리고 [accessibilityDropPointDescriptors](https://developer.apple.com/documentation/objectivec/nsobject/2891048-accessibilitydroppointdescriptor) 에서 확인할 수 있습니다.
> Make drag and drop accessible in your iOS or iPadOS app. When you use the accessibility APIs to identify drag sources and drop targets in your app, assistive technologies can help people drag and drop onscreen items. For developer guidance, see accessibilityDragSourceDescriptors and accessibilityDropPointDescriptors.
>

