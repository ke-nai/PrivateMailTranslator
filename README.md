# PrivateMailTranslator

![image](https://user-images.githubusercontent.com/66747535/100091215-ab12af80-2e97-11eb-8f16-4144ee235c72.png)

[플레이스토어에서 보기](https://play.google.com/store/apps/details?id=com.kenai.izone.privatemailtranslator)

파파고 api를 활용해서 만든 번역앱입니다.
Papago, AdMob, Firebase 등의 인증 정보가 포함되어 코드는 업로드하지 않았습니다. 

## 일반적인 향상점
### 줄별 번역 기능
전체 문장을 일괄 처리하는 파파고 앱과 달리

번역할 문장을 줄별로 분할하여 처리합니다.

따라서, 여러 언어가 혼합되어 쓰여진 글을 번역하는데 유용하단 점이

기존의 파파고 번역기 앱과의 차별점입니다.

### 멀티 스레딩
줄별로 나눠진 문장을 순서대로 처리하지 않고

멀티 스레딩으로 한번에 처리해서 속도를 향상시켰습니다.

## 특수 용도용 향상점
### 닉네임 설정 기능
Private Mail 번역시 닉네임이 번역기에 포함되면서

번역 내용이 꼬이는 경우가 발생하는데

몇가지 특정 언어별 닉네임을 설정해둬서 이를 방지합니다.

### 단어 사전 처리
API 자체에서 잘못 번역하는 단어를

따로 설정해두면 그 단어만 자동으로 변환해줍니다.

번역기 전체로는 바꿀 수 없는 부분이지만

특수 용도이므로 유용하게 적용됩니다.
