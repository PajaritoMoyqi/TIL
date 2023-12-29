## 개요

2023년의 거의 다 갔다. 12월을 지나며 알고리즘, 자료구조 및 반도체 공정의 정리까지 끝났다. 올해 내가 할 수 있는 만큼의 정리는 끝낸 것 같아 올해의 남은 기간은 쉬려고 한다. 8월부터 타인의 삶에 대한 공부에 관심도를 높게 두기 시작하고 10월 중순부터는 아예 거기에 집중하면서(여행도 다녀왔다) 생각보다 진도를 많이 빼지는 못했다. 그리고 여전히 컴퓨터 공학이나 프로그래밍을 0순위로 두고 있지 않기 때문에 내년에는 올해에 비하면 욕심과 시간을 덜고 병행한다는 느낌으로 가져갈 것 같다.

## 대상 분야

올해 초중반에 썼던 자료를 그대로 가져왔다. 다시 봐도 CS(Computer Science) 분야에는 정말 많은 분야가 있다는 생각이 든다.

| 분야 | 지식 수준 | 관심도 |
|:---:|:---:|:---:|
| 신호 | 0 | 1 |
| ADC/DAC | 0 | 1 |
| 반도체 | 3 | 1 |
| 회로 | 1 | 1 |
| CPU/Memory | 2 | 3 |
| I/O | 1 | 3 |
| ROM | 1 | 3 |
| 자료구조 | 3 | 1 |
| Assembly | 1 | 1 |
| Linux | 0 | 1 |
| OS | 1 | 2 |
| Kernel | 1 | 2 |
| 라즈베리파이 | 0 | 1 |
| C언어 | 2 | 2 |
| 알고리즘 | 3 | 1 |
| 클린코드 | 0 | 1 |
| 컴파일러 | 0 | 1 |
| 네트워크 | 1 | 1 |
| 보안 | 1 | 1 |
| 가상머신 | 1 | 1 |
| 클라우드 | 0 | 1 |
| 임베디드 | 0 | 1 |
| 인공지능 | 0 | 1 |

지식 수준의 숫자의 의미는 아래와 같다.

- 0 : 아예 기초적인 것도 제대로 들어보지 못했다.
- 1 : 기초적인 내용만 들어보았고, 장기 기억에 남았다기보다는 그냥 '어, 그거 들어봤는데' 하는 정도다.
- 2 : 해당 분야가 어떻게 돌아가는지에 대해서 대강 머리속에 그림이 그려진다. 남에게 설명할 수도 있지만 체계적이지 못하다.
- 3 : 강의/책 내용 정리 혹은 실습 등을 통해서 내 지식으로 만드는 작업이 병행되었으며, 남에게 어느 정도 체계적으로 설명할 수 있다.
- 4 : 별도의 참고자료 필요 없이 내 스스로 자유롭게 남에게 설명이 가능하고, 응용이나 추론이 가능하다.
- 5 : 내 컨텐츠를 만들어 보았다.

관심도의 숫자의 의미는 아래와 같다.

- 0 : 관심 없음
- 1 : 관심 조금 있는데 시간 없음, 혹은 이미 공부를 충분히 해서 가끔만 볼 생각
- 2 : 관심이 있고 여유가 생기면 시간 낼 의향 있음
- 3 : 관심이 있고 공부 계획을 세워놓은 상태

## 아키텍처

우선 올해 해낸 것들을 보자. 결국 C언어와 자료구조 및 알고리즘, 그리고 반도체에 관한 정리를 끝내면서 저번 글과 비교해 지식 수준이 올라간 것이 보인다(C언어 : 0 -> 2, 자료구조 1 -> 3, 알고리즘 1 -> 3, 반도체 : 2 -> 3).

재미있는 것은 올해에 가장 많은 시간을 투자한 것이 아키텍처 파트(회로, CPU/Memory, I/O, ROM)인데, 지식 수준은 그대로인 것이 보인다. 이는 이 분야가 올해 초중순에 집중했던 분야인데 당시에 정리를 하기보다는 하나라도 더 받아들이려고 강의를 더 듣고 책을 더 보는 것에 집중했기 때문이다. 그 이후로 C언어와 알고리즘, 자료구조, 반도체 등이 끼어들면서 점점 기억에서 잊혀져갔던 점도 크다.

따라서 내년 초부터는 올해 초중순에 공부했던 아키텍처 정리에 집중할 생각이다. 아쉽게도 '회로' 파트는 대학교 전공 강의를 두 개나 들었음에도 당장 정리할 엄두가 나지 않아서 제껴두고 아래에 써둔 세 권의 책으로 CPU/Memory, I/O, ROM 파트를 정리할 생각이다.

조너선 스타인하트, 2021, 책만, 『한 권으로 읽는 컴퓨터 구조와 프로그래밍』<br>
에반 업튼·제프 듄트만·랄츠 로버츠·팀 맴로타·벤 에버라드, 2017, 위키북스, 『라즈베리 파이로 배우는 컴퓨터 아키텍처』<br>
정기철, 2018, 연두에디션, 『컴퓨터 구조: 프로그래밍 관점에서 바라보는 컴퓨터 구조』

다만 다른 정리 글들에 비해 일반적으로 컴퓨터 구조를 정리하는 명확하게 정해진 시퀀스가 없다보니, 순서를 정하고 글 하나의 범위를 정하는 것이 어렵다. 전에 한참 공부를 하고 있을 때도 정리해야겠다는 생각을 했지만 실천하지 못한 이유가 이것이었다. 일단 더 미루기 싫으니, 눈에 보이는 분야별로 정리를 하고 나서 계속 글을 써가기로 했다. 그러다보면 어떤 글은 다른 글과 합쳐지는 게 더 낫다거나 글들의 순서가 어떻게 되었으면 좋겠다는 등의 아이디어가 떠오르지 않을까 싶다.

자료구조, 알고리즘, 반도체 같은 것들은 좀 아깝다는 생각이 커서 정리했기 때문인지 스트레스도 많이 받으면서 정리를 했는데, 아키텍처는 여전히 프로그래밍 내에서 재미있는 분야 중 하나여서 스트레스가 덜 할 것이라 기대된다. 주의할 점 단 한 가지는 '빨리 정리하려는 마음', '끝내버리고 홀가분하려는 마음'을 수시로 지워내는 것(다른 분야도 이러한 마음이 나를 종종 힘들게 했던 것 같다).

## 자료구조 및 알고리즘

정리했다고 끝은 아니다. 백준 문제를 조금 더 풀어볼 생각이다. 어떤 분야는 이론만 빠삭한 상황이라 어떻게 응용해서 사용하는지 직접 부딪혀볼 필요가 있다. solved.ac 점수를 기준으로 어디까지 한다, 라고 정하는 것도 좋겠지만 점수를 목표로 무언가를 해보니 심적으로 쫓기는 느낌이 들어서 신경쓰지 않으려고 한다.

## 이후의 프로그래밍 (공부)길

아키텍처 정리를 끝낸 그때의 나에게 맡기자.