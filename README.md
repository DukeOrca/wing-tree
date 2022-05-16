# KIM SEONGJU
# Introduce
1년 차 안드로이드 개발자 김성주입니다.<br>
현재 마드라스체크에서 Android 개발자로 근무하고 있습니다.<br> 

함께 성장할 수 있는 개발 문화를 지향합니다.

좋은 프로그래밍이란 일을 줄여나가는 것이라고 생각합니다. 이는 훌륭한 서비스로 이어진다고 믿고 있습니다.<br>
보다 간결하고 '쉬운' 코드를 지향합니다.<br>

개인 프로젝트를 즐기며, 언젠가는 괜찮은 수준의 수익을 내는 것을 목표로 진행하고 있습니다.

# My Tech Stack
-

# Work Experience
## 마드라스체크 (2021.03~현재)
Android 개발자로 근무 중
- 협업툴 플로우 태블릿 버전 개발

기존 버전은 각 화면이 모두 Activity로 구성되어 태블릿에서 분할 화면으로 볼 수 없다는 단점이 존재했습니다.<br>
태블릿의 분할 화면을 구성하기 위해 대부분의 Activity를 Fragment로 변환하고, 올바르게 동작할 수 있도록 Fragment 스택 관리와 통합적인 navigation을 위한 기능등을 개발했습니다.
- 엔터프라이즈 앱 보안 취약점 조치

저희 서비스를 도입하기 전에 여러 고객사에서 보안 취약점 점검을 진행하였고,<br>
해당 보안 취약점에 대한 조치를 수행했습니다.<br>
1. Anti-Debugging
네이티브 코드를 사용한 안티 디버깅 로직을 적용하였습니다.
2. Heap 상 중요 정보 노출
패스워드 등의 중요 정보를 암호화 전에 String 객체로 저장하면, heap dump 를 통해 메모리상에서 확인이 가능한 이슈였습니다.
CharArray로 변환하여 조치했습니다.
3. 위변조 방지
Smali 수준에서 코드 조작이 가능하다는 취약점으로, 서버에 저장한 앱 signing key를 불러와, 앱의 signing key 와 비교하는 것으로 조치했습니다. 

# My Recent Projects
## Wordle (In progress)
워들 게임 앱을 개발하고 있습니다.<br>
현재 진행 중인 프로젝트입니다.

## N-Back Training
<img src="https://github.com/wing-tree/wing-tree/blob/master/image/graphic_image_en.png" alt="image" width="512"/><br>
[_**Github**_](https://github.com/wing-tree/n-back-training)<br>
[_**Google Play**_](https://play.google.com/store/apps/details?id=com.wing.tree.n.back.training)

### Tech Stack
- Clean Architecture
- Firebase (DataStore)
- Flow
- Jetpack Compose
- LiveData
- MVVM

## Bible In You
![image](https://github.com/wing-tree/wing-tree/blob/master/image/graphic_image_bible_in_you.png)<br>
[_**Github**_](https://github.com/wing-tree/bible-lock-screen)<br>
[_**Google Play**_](https://play.google.com/store/apps/details?id=com.duke.orca.android.kotlin.biblelockscreen)
### Tech Stack
- Firebase (Crashlytics)
- Lock Screen
- MVVM
- Room (Multilingual Database)
- RxJava
