## MyVelog
- 간단한 멀티모듈 프로젝트를 개발한다.

#### 기술스택
| Tech Stacks              | 기술 스택                          |
|--------------------------|--------------------------------|
| Language                 | Kotlin                         |
| Async                    | Coroutine, Flow                |
| DI                       | Hilt                           |
| UI                       | Jetpack Compose, Lottie        |
| Local Storage            | Data Store               |
| Architecture             | MVVM Repository, Multi Module  |
| 3rd party library manage | Gradle Version Catalog         |
| Test                     | Mockk, Junit4, Turbine, Kotest |
| Lint                     | Ktlint, DeteKt                 |

#### 요구사항
- Velog 닉네임을 입력하면 입력한 Velog 블로그로 연결되는 웹뷰가 존재한다.
- 뒤로가기, 앞으로가기를 지원한다.
- 닉네임 초기화가 가능하다.
- 확장성 있는 구조를 취한다.