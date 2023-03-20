# Open AI의 GPT를 활용한 채팅웹사이트<채진이>

요즘 ChatGPT, OpenAI 등 이슈가 되어가고 있어서 OpenAI의 GPT-3를 이용하여 대화형 AI를 웹사이트로 꾸며보았습니다.

`채진이`라는 이름으로 지은 이유는 `Chat GPT`에서 따왔으며 한국적인 이름으로 만들어보고자 하였습니다.

**text-davinci-003** 모델을 사용하여 대화의 퀄리티를 높였습니다.

[https://gusgh00.github.io/chaejin-ai-vanilia/](https://gusgh00.github.io/chaejin-ai-vanilia/)

# 채팅 기능 사용법

![메인페이지 및 채팅 화면](/imgs/1.jpg)

메인페이지 및 채팅 화면

1. 친절한 설명과 토큰 입력칸, 메세지 입력칸으로 작성할 수 있습니다.
2. 이미지의 친절한 설명은 다음과 같습니다.
    1. 토큰을 먼저 입력하세요!
    Get Token in OpenAI
    [https://openai.com/product](https://openai.com/product)
    2. 토큰 입력 후 지우지 마세요!
    3. 그리고 채진이와 채팅을 해보세요!
3. 메세지 입력 후 <SEND 버튼> 또는 <엔터키>를 클릭하면 메세지 전송이 완료 됩니다.
4. AI가 해당 input의 value 값에 반응하여 메세지를 읽고 답장을 합니다.
    
    ![토큰 입력 후 메세지를 전송하는 이미지](/imgs/4.jpg)
    
    토큰 입력 후 메세지를 전송하는 이미지
    
5. 각 메세지 박스는 마우스 오버 시 확대가 되며 모바일 또는 태블릿에서는 클릭 시 확대가 가능합니다.
    
    ![점심 메뉴 추천 메세지 전송 후 받은 메세지를 확대한 이미지](/imgs/5.jpg)
    
    점심 메뉴 추천 메세지 전송 후 받은 메세지를 확대한 이미지
    
6. <RESET 버튼> 클릭 시 모든 로그와 메세지 기록이 초기화 됩니다.

# 미디어 쿼리 이용한 반응형 웹

![모바일 뷰](/imgs/2.jpg)

모바일 뷰

![태블릿 뷰](/imgs/3.jpg)

태블릿 뷰

css의 `@media (max-width: 900px)` 미디어 쿼리 사용법으로 각 하드웨어 마다 사이즈 변화를 주었습니다.

# 정리

![GPT 모델의 농담](/imgs/6.jpg)

GPT 모델의 농담

리액트.js를 활용하여 만들었으나 깃허브 page에 호스팅하여 원할한 사용을 위해 바닐라로 작성한 웹페이지 입니다.

해당 <채진이> 웹사이트는 리액트로 만든 것과 바닐라로 만든 것 둘다 깃허브에서 확인하실 수 있습니다.

### 웹사이트

[채진이](https://gusgh00.github.io/chaejin-ai-vanilia/)

### 리액트

[https://github.com/gusgh00/chaejin-ai-chat](https://github.com/gusgh00/chaejin-ai-chat)

### 바닐라

[https://github.com/gusgh00/chaejin-ai-vanilia](https://github.com/gusgh00/chaejin-ai-vanilia)
