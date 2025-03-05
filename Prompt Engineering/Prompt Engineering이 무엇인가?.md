# Prompt Engineering?
Chat GPT는 사람처럼 생각하지 않기 때문에 사용자의 질문을 이해하는 방식도 사람과 다르게 동작함
그렇기 때문에 Chat GPT한테 물어보는 방법에 따라 정확한 답을 얻을 수도, 엉뚱한 답을 얻을 수도 있음

원하는 정확한 답변을 얻기 위한 방식을 정형화 시키는 것이 Prompt Engineering의 핵심

Semantic association
유의어, 연관된 단어 등이 매우 중요하게 동작함
GPT는 이 것을 기반으로 동작함
하나의 단어에서 연관되는 다른 단어들을 이어서


질문을 매우 짧게 하는 경우 (맥락이 없이 )
오는 답변도 구체적이지 않음

질문에 맥락을 추가하자! 질문을 하기 전에 현재 어떤 상황인지를 설명하는 문구를 넣을 것

# 구조화된 프롬프트!
Modifier + Topic + Multiple Modifiers

최적화된 프롬프트는 위와 같은 구조를 갖고 있음
Modifier는 요청되는 특수한 타입을 지정함, 예를 들면 트위터 스레드, 위키피디아 같이 검색을 요구할 때 사용할 수 있음

Topic은 요청하는 구체적인 내용 - ~를 알려줘 같은 내용들

추가적인 맥락은 요청에 추가로 더 구체화되는 것들, ~들이 사용하는 단어로 답변해줘 같은 것들

https://www.promptingguide.ai/
https://learnprompting.org/docs/introduction
위의 두 링크를 참고하여 프롬프트를 더 잘 짜볼 수 있음

Instruction 프롬프트를 추가할 것
즉, GPT의 응답을 어떤 형태로 할 것인지 미리 정의해둔 방식대로 응답하도록 설정하기

role prompt
