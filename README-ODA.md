# ORACLE Cloud Test Drive #

## Oracle Digital Assistant ##

### 소개 ###
최근 몇년 사이 각 세대 또는 기업의 조직들 사이에 비즈니스 수행하기 위해 의사소통 또는 의견을 교환 하는 과정에 많은 변화가 있습니다. 여전히 전화 또는 웹이나 모바일을 통해 의사소통을 하고 있고, 그 가운데 온라인 상의 챗팅을 통한 의사소통도 많은 부분을 차지 하고 있습니다. (예) 카카오톡, 페이스북, 라인) 대부분의 모바일 기기에서 가장 많이 사용하는 앱으로 챗팅 앱이 사용되고 있습니다.

<img src="ODA/img/Intro-1.png" width="100%"/>

만약에 개발한 모바일 앱을 설치 할 수 없다면 어떻게 서비스를 이용할 수 있을 까요?  
이런 경우 이미 기존에 설치되어 있는 채팅 앱을 이용할 수 있습니다. 
이 문서에서는 챗봇을 통해서 별도의 앱을 설치하거나 웹 사이트를 방문하지 않고 사용자가 서비스와 상호작용을 할 수 있는 방법을 소개 합니다.

챗봇 이란?

간단히 말해서 챗봇은 인터넷 환경에서 컴퓨터 프로그램을 디자인되어 사람과 같이 대화 하는 것이라고 할 수 있습니다. 모든 사용자는 대화를 통해 의사소통하는데 익숙한 메타포 인터페이스, 즉 기존의 보편적인  클라이언트(챗팅 클라이언트)를 사용하여 기업의 데이터에서 및 프로세스에 쉽고 빠르게 접근 할 수 있습니다.

### 오늘 실습에 대해서 ###

오늘의 워크샵은 Cafe Supremo 라고 불리는 가상의 카페의 디지털화된 기능을 중심으로 진행됩니다.

<img src="ODA/img/Intro-2.png" width="40%"/>

Care Supremo 는 고객이 많이 사용하고 있는 모바일 앱을 가지고 있지만, 마케팅 부서에서는 새로운 또는 잠재 고객이 앱을 다운로드지 않고 있는 것을 인식하고 있습니다. (앱을 검색하였지만 다른 앱들도 너무 많아 검색을 못할 수 있음) 마케팅 부서에서는  패이스북 메신저와 같은 소셜 채널을 통해 잠재 고객에게까지 서비스를 제공 할 수 있는 방법을 찾고 있습니다.

이 워크샵은 CafeSupremo Bot 을 소개하고 Bot에서 사용된 다양한 컴포넌트를 살펴보고, 새로운 기능을 확장 하는지에 대해 알아 보겠습니다.

# 준비 사항 #
본 클라우드 워크샵은 사용자 가지고 있는 클라우드 계정을 기반으로 준비되어 있습니다. 클라우드 계정을 가지고 있음에도, 클라우드 계정 안에서 Digital Assistant / Chatbot 환경이 확인되지 않은 경우 [Provisioning Steps](Provisioning/Provisioning.md) 를 통해서 확인 하시기 바랍니다.

#### 금일 사용하실 환경 접속 URL 입니다. [URL: https://9a08295d.ngrok.io/botsui/home ] 복사하셔서 크롬 브라우저에서 여시면 됩니다.

# 준비된 실습: #

#### 1: Cafe Supremo Digital Assistant 에 대한 소개 [(시작)](ODA/100-IB.md) 
#### 2: Bot 생성 및 개발 [(시작)](ODA/200-IB.md) ####
#### 3: Custom Components [(시작)](ODA/300-IB.md) ####
#### 4: Instant Apps for Structured Data [(시작)](ODA/400-IB.md) ####
#### 5: Exposing the Digital Assistant within a Web Page [(시작)](ODA/500-IB.md)

#### OPTIONAL Labs - Exposing the Digital Assistant within Social Channels. ####

- 6: Via Facebook Messenger [(Start)](ODA/600-IB.md)

## 실습 파일 ##
- [Intents, Entities and Utterances for FoodMenu Bot](ODA/Lab_Files/Intents-And-Entities.zip)
- [OBotML dialogue flow markup for ordering Food](ODA/Lab_Files/DialogYAML.zip)
- [Custom Component Template](ODA/Lab_Files/Custom-Component-Template.zip)
- [Web Application](ODA/Lab_Files/CTD3.0-CafeSupremo-Web.zip)



