# NursingDictionary

## 프로젝트 설명
NursingDictionary는 간호학 및 관련 의학 용어를 쉽게 검색하고 학습할 수 있는 모바일 애플리케이션입니다. 안드로이드와 iOS에서 모두 지원되며, 사용자에게 매번 새로운 용어를 제공하여 학습 효과를 극대화합니다.

## 주요 기능
- **간호학 및 의학 용어 검색**: 주요 간호 및 의학 용어를 손쉽게 검색 가능
- **랜덤 용어 표시**: 앱을 열 때마다 새로운 용어가 홈 화면에 표시
- **안드로이드 및 iOS 지원**: 두 플랫폼 모두에서 호환 가능
- **다국어 지원**: 간호 용어와 관련된 영어 번역 제공

## 설치 방법

### 1. 저장소 클론
```bash
git clone https://github.com/JeongPenguin00/NursingDictionary.git
cd NursingDictionary
```

### 2. 의존성 설치
```bash
npm install 
```

### 3. iOS 설정 (MacOS에서만)
```bash
cd ios
pod install
cd ..
```

### 4. 앱실행
#### Android에서만
```bash
npm run android
```

#### ios에서만
```bash
npm run ios
```

## 프로젝트 구조
- src/
  - components/      # 앱에 사용되는 공통 컴포넌트
  - screens/         # 앱의 화면별 구성 파일
  - assets/          # 이미지 및 리소스 파일
- ios/               # iOS 관련 프로젝트 파일
- android/           # Android 관련 프로젝트 파일


## 기타문의

- Email : wodyd818@naver.com

