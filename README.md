# Prototype-of-Fashion-Jiok-Dating-App
 AI 패션·라이프스타일 기반 매칭 소개팅 앱

#파일구조

```
fashion-jiok/
├── .gitignore
├── android/
├── assets/
│   ├── adaptive-icon.png
│   ├── favicon.png
│   ├── icon.png
│   └── splash-icon.png
├── ios/
├── src/
│   ├── screens/
│   │   ├── Auth/
│   │   │   ├── LoginScreen.js
│   │   │   └── OnboardingScreen.js
│   │   ├── Main/
│   │   │   ├── MainHome.js       <-- 메인 홈
│   │   │   ├── ExploreScreen.js  <-- 탐색
│   │   │   ├── MatchesScreen.js  <-- 매칭
│   │   │   └── HomeLoading.js
│   │   └── Chat/
│   │   │   ├── ChatListScreen.js  <-- 채팅 목록
│   │   │   └── ChatScreen.js
│   │   │
│   │   │
│   │   └── Profile/
│   │         └── MyProfileScreen.js
│   ├── navigation/
│   │   ├── AppNavigator.js
│   │   ├── AuthNavigator.js
│   │   └── MainTabNavigator.js
│   ├── context/
│   │   └── AuthContext.js
│   ├── services/
│   │   └── firebase.js
│   └── constants/
│       └── styles.js
├── App.js
├── app.json
├── babel.config.js
├── google-services.json   
├── index.js
├── package.json
└── tailwind.config.js
```


터미널 설치, 실행 구조
```
install npm  --> node.js
install expo --> expo 설치

[실행]
npx expo start

```
