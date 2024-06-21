# Huge-Traffic-Handling
대용량 트래픽 및 데이터 처리 프로젝트

# Git-Flow 전략
1. Master-Branch : Main
2. Develop-Branch : (Master-Branch -> Develop-Branch) 개발 중심의 브랜치, 개발 중인 기능을 통합 및 테스트 진행
3. Feature-Branch : (Develop-Branch -> Feature-Branch) Develop-Branch에서 생성하는 브랜치. 주로 새로운 기능을 개발할 때마다 생성.
  3.1. 기능 통합 및 테스트 : 기능 개발 완료시 Feature-Branch -> Develop-Branch
4. Release-Branch : (Develop-Branch -> Release-Branch) 새로운 릴리스를 준비할 때 Develop-Branch에서 Release-Branch를 생성.
  4.1. 릴리스 테스트 및 완료 : Release-Branch에서 Release 후보를 테스트함. 테스트 완료시 Release-Branch를 Master-Branch로 병합하여 새로운 Release 배포.
5. HotFix-Branch : (Master-Branch -> HotFix-Branch) 운영 환경에서 발견된 긴급한 버그를 수정해야할 때 Master-Branch에서 HotFix-Branch 생성. 수정 후 Master, Develop-Branch에 병합.

# Code Convention
![스크린샷 2024-06-21 오후 8 23 27](https://github.com/shwhdgns/Huge-Traffic-Handling/assets/55942478/d4df56ce-6563-492e-b597-bbd13ebf4faa)
