# ElderCare-Android
> 치매 환자를 위한 실시간 응급 대응 앱  
> Android 클라이언트 팀 (24.12 ~ 25.01)  


## 📖 프로젝트 소개
ElderCare는 치매 환자를 위한 **실시간 응급 대응** 및 **복용 알람/건강 관리 기능**을 제공하는 모바일 애플리케이션입니다.  
본 프로젝트는 Android 클라이언트 개발을 목표로 진행되었으며, Clean Architecture 기반의 구조 설계와 다양한 Jetpack 기술 적용을 통해 확장성과 유지보수성을 고려했습니다.  
※ 현재 프로젝트는 초기 기능 구현 단계까지만 진행되었습니다.

## 🍨 *****Contributors*****

| 김성민 <br> [@1971123-seongmin](https://github.com/1971123-seongmin) | 허성현 <br> [@hyeonhh](https://github.com/hyeonhh) | 성규현 <br> [@dmp100](https://github.com/dmp100) | 조정범 <br> [@BeomBeom2](https://github.com/BeomBeom2) |
|:---:|:---:|:---:|:---:|
| <img width="150" src="https://github.com/user-attachments/assets/fca542a2-5d32-40f3-aea1-99bb81424a10"/> | <img width="150" src="https://github.com/user-attachments/assets/06a7d15f-000b-436c-b655-62333d48166c"/> | <img width="150" src="https://github.com/user-attachments/assets/daa04602-4d2d-456e-a11b-0c97509ea0c1"/> | <img width="150" src="https://github.com/user-attachments/assets/01261fa2-9cfd-43af-9a6a-6520ed01b4a8"/> |
| 기기 정보 등록 및 관리 | 메인 홈 / 복용 알람 추가/삭제, 활동 탭 | 건강정보 등록 / 설정 / 스플래시 및 소셜 로그인 | 복용 알람 수정 / 기본 정보 등록 |


## 📗 *****Convention*****
[📕 Git Convention & Branch Strategy]()
<br>
[📘 Android Coding Convention]()
<br>
[📒 Package Convention]()

<br/>

## 🔧 *****TECH STACKS*****
| **Category** | **TechStack** |
| --- | --- |
| Language | Kotlin |
| Architecture | Clean Architecture, MVVM |
| DI | Hilt |
| Network | Retrofit |
| Asynchronous | Coroutines, Flow |
| Jetpack | ViewBinding, Navigation, DataStore |
| Image | Glide, Coil |

<br/>

## 📁 *****Foldering*****

```
📂 org.sopt.linkareer
┣ 📂 core
┃ ┣ 📂 designsystem
┃ ┣ 📂 state
┃ ┣ 📂 navigation
┣ 📂 data
┃ ┣ 📂 datasource
┃ ┣ 📂 datasourceimpl
┃ ┣ 📂 model
┃ ┃ ┣ 📂 request
┃ ┃ ┣ 📂 response
┃ ┣ 📂 repositoryimpl
┃ ┣ 📂 service
┣ 📂 domain
┃ ┣ 📂 model
┃ ┣ 📂 repository
┣ 📂 presentation
┃ ┣ 기능 별 패키징
