# LFS Tools v0.1.1

Git LFS 자동 등록 및 마이그레이션 GUI 도구

## 시스템 요구사항

- Windows 10 이상
- Git 및 Git LFS 설치 필수

## 구성 파일

- `LFS-Launcher.exe` - 메인 런처
- `LFS-Tools/LFS-Unified-Tool.exe` - 실제 작업 도구

## 사용법

### 1. 런처 실행
`LFS-Launcher.exe` 실행

### 2. 기능 선택

**LFS 자동 등록**
- 대용량 파일 스캔
- .gitattributes 자동 설정
- 마이그레이션 연결 옵션

**LFS 마이그레이션**  
- 기존 파일을 LFS로 변환
- Git 히스토리 자동 재작성
- 안전 백업 생성

### 3. 로그 확인
"로그 확인" 버튼으로 작업 결과 확인 가능

## 주의사항

- 마이그레이션은 Git 히스토리를 변경합니다
- 작업 전 백업을 권장합니다
- 팀 프로젝트는 사전 협의 필요

**환경 확인**
런처 하단에서 Git/LFS 설치 상태 확인

---
Created by H.S.Kim