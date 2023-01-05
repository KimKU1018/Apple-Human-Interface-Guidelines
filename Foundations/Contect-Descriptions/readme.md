## Content descriptions

**의미를 전달하는 모든 이미지에 대한 대체 설명을 제공합니다.** 콘텐츠의 의미 있는 이미지를 설명하지 않으면 VoiceOver 사용자가 앱을 완전히 경험하지 못하게 됩니다. 유용한 설명을 만들려면 이미지를 볼 수 있는 사람에게 설명이 필요한 내용을 보고하는 것부터 시작하십시오. VoiceOver는 이미지와 캡션을 둘러싼 텍스트를 읽기 때문에 이미지 자체에서 전달되는 정보에 설명을 집중합니다.
> **Provide alternative descriptions for all images that convey meaning.**
 If you don’t describe the meaningful images in your content, you prevent VoiceOver users from fully experiencing your app. To create a useful description, start by reporting what would be self-explanatory to someone who is able to see the image. Because VoiceOver reads the text surrounding the image and any captions, focus your description on information that’s conveyed by the image itself.
>
<img width="269" alt="33" src="https://user-images.githubusercontent.com/86593582/210491290-215a6b40-5b61-4e36-95eb-fb481e9a1962.png">

**인포그래픽에 완전히 액세스할 수 있도록 합니다.** 인포그래픽이 전달하는 내용을 설명하는 간결한 설명을 제공하십시오. 사람들이 인포그래픽과 상호 작용하여 더 많거나 다른 정보를 얻을 수 있다면VoiceOver 사용자도 이러한 상호 작용을 사용할 수 있도록 해야 합니다. 접근성 API는 보조 기술이 사람들이 사용하는 것을 도울 수 있도록 사용자 지정 대화형 요소를 나타내는 방법을 제공합니다.
> **Make infographics fully accessible.**
 Provide a concise description of the infographic that explains what it conveys. If people can interact with the infographic to get more or different information, you need to make these interactions available to VoiceOver users, too. The accessibility APIs provide ways to represent custom interactive elements so that assistive technologies can help people use them.

**이미지가 순전히 장식적이고 어떤 것도 전달하기 위한 것이 아니라면 보조 기술로부터 숨기십시오.** VoiceOver가 순전히 장식적인 이미지를 묘사하도록 만드는 것은 사람들의 시간을 낭비하고 아무런 이점도 제공하지 않고 그들의 인지적 부담을 가중시킬 수 있습니다.
> **When an image is purely decorative and isn't intended to communicate anything, hide it from assistive technologies.**
 Making VoiceOver describe a purely decorative image can waste people’s time and add to their cognitive load without providing any benefit.

**각 화면에 고유한 제목을 지정하고 정보 계층에서 섹션을 식별하는 제목을 제공합니다.** 사람들이 화면에 도착했을 때, 제목은 그들이 보조 기술로부터 받는 첫 번째 정보입니다. 사람들이 앱의 구조를 이해할 수 있도록 각 화면의 내용이나 용도를 간결하게 설명하는 고유한 제목을 만드십시오. 마찬가지로, 사람들은 각 화면의 정보 계층 구조에 대한 정신적 지도를 구축하는 데 도움이 되는 정확한 섹션 제목이 필요합니다.
> **Give each screen a unique title and provide headings that identify sections in your information hierarchy.**
 When people arrive on a screen, the title is the first piece of information they receive from an assistive technology. To help people understand the structure of your app, create a unique title for each screen that succinctly describes its contents or purpose. Similarly, people need accurate section headings to help them build a mental map of the information hierarchy of each screen.

**모든 사용자가 비디오 및 오디오 콘텐츠를 즐길 수 있도록 지원합니다.** 자막, 오디오 설명 및 스크립트를 제공하면 사용자에게 적합한 방식으로 오디오 및 비디오 콘텐츠의 이점을 제공할 수 있습니다.
> **Help everyone enjoy your video and audio content.**
When you provide closed captions, audio descriptions, and transcripts, you can help people benefit from audio and video content in ways that work for them.

Closed captions 은 사람들에게 비디오의 가청 정보와 동등한 텍스트를 제공한다. 또한 Closed captions 을 사용하여 동일한 콘텐츠에 대해 여러 개의 번역을 제공하여 시스템에서 장치의 현재 설정과 일치하는 버전을 선택할 수 있습니다. 자막을 항상 사용할 수 있는 것은 아니므로 자막을 제공하는 것도 중요합니다.
> *Closed captions* give people a textual equivalent for the audible information in a video. You can also use closed captions to provide multiple translations for the same content, letting the system choose the version that matches the device’s current settings. Because closed captions aren’t always available, it’s important to provide subtitles, too.

오디오 설명은 시각적으로만 표시되는 중요한 정보의 음성 내레이션을 제공합니다.
> *Audio descriptions* provide a spoken narration of important information that’s presented only visually.

녹취록은 사람들이 다양한 방법으로 비디오를 즐길 수 있도록 청각 및 시각 정보를 모두 포함하는 비디오에 대한 완전한 텍스트 설명을 제공하도록 합니다.
> A *transcript* provides a complete textual description of a video, covering both audible and visual information, so that people can enjoy the video in different ways.
>
