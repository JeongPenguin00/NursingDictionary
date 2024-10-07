NursingDictionary
NursingDictionary는 간호학과 학생 및 의료 전문가들을 위해 필수적인 간호용어와 의료용어를 쉽게 접근할 수 있도록 도와주는 모바일 애플리케이션입니다. 이 앱은 React Native로 개발되었으며, iOS와 Android 플랫폼 모두에서 사용할 수 있습니다.

주요 기능
포괄적인 간호 사전: 다양한 간호 및 의료 용어에 접근할 수 있습니다.
영어 의료 용어 포함: 관련된 영어 용어도 함께 제공하여 이해를 돕습니다.
동적 홈 화면: 앱을 열 때마다 새로운 콘텐츠가 홈 화면에 노출됩니다.
크로스 플랫폼: Android 및 iOS 기기에서 원활하게 작동합니다.
설치 방법
사전 준비
Node.js와 npm 설치
React Native CLI 설치
Android Studio 및/또는 Xcode 설치 (플랫폼별 빌드를 위해)

레포지토리 클론
bash
git clone https://github.com/your-username/NursingDictionary.git
cd NursingDictionary

의존성 설치
npm install

iOS 설정
iOS 개발을 위해 ios 디렉토리로 이동한 후 필요한 의존성을 설치합니다:
cd ios
pod install

애플리케이션 실행
iOS
Xcode가 설치되어 있어야 합니다. iOS 시뮬레이터에서 앱을 실행하려면:
npx react-native run-ios

Android
Android Studio와 Android SDK가 설정되어 있어야 합니다. Android 에뮬레이터에서 앱을 실행하려면:
npx react-native run-android

프로젝트 구조
src/: 앱의 모든 소스 코드가 포함된 폴더
assets/: 이미지 및 폰트와 같은 정적 파일들
components/: 재사용 가능한 React 컴포넌트
screens/: 앱의 여러 화면
ios/: iOS 관련 파일 및 설정
android/: Android 관련 파일 및 설정

라이센스
이 프로젝트는 MIT 라이센스에 따라 배포됩니다. 자세한 내용은 LICENSE 파일을 참조하세요.

문의
궁금한 사항이나 문의가 있으시면 아래로 연락 주세요:
wodyd818@naver.com