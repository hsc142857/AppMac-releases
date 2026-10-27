# AppMac 배포 파일

AppMac Mac 유틸리티 모음의 설치 파일(DMG)만 올리는 저장소입니다. 소스는 비공개입니다.

## 설치 (지금)

[Releases](https://github.com/hsc142857/AppMac-releases/releases)에서 필요한 프로그램의 DMG를 받아, 열고 앱을 Applications로 끌어다 놓습니다.

처음 열 때 "확인되지 않은 개발자" 경고가 나오면 **앱을 우클릭 → 열기**, 또는 **시스템 설정 → 개인정보 보호 및 보안 → 그래도 열기**를 누릅니다. (ad-hoc 서명, Apple 공증 안 됨)

| 프로그램 | 내용 |
|----------|------|
| ZipWinZip | Windows에서도 한글 이름이 유지되는 ZIP 압축·ZIP/ALZ/EGG 해제 |
| yt-dlp GUI | yt-dlp 기반 영상 다운로더 (yt-dlp·ffmpeg는 따로 설치, 앱 안에 설치 도우미) |
| AppstallManager | 설치 기록 기반 앱 관리자 (현재 앱 목록 단계) |

## 앞으로

AppstallManager가 AppMac의 시작점이 됩니다. 다음 버전부터 AppstallManager 하나를 설치하면 나머지 프로그램을 **"다운로드 및 설치하시겠습니까?"** 로 받아 설치하고, Dock 아이콘을 누르면 프로그램이 부채꼴로 펼쳐집니다.
(이 기능을 먼저 시험하던 AppMacShell은 AppstallManager로 합쳐져 배포를 멈췄습니다.)

## 릴리스 규칙

- 태그: `<프로그램>-v<버전>` (예: `ZipWinZip-v1.1.0`), 파일: 프로그램 DMG 하나
- 설치 도구는 정식 릴리스 중 가장 높은 버전을 받고, GitHub가 제공하는 SHA-256으로 파일을 확인한 뒤 설치합니다.
- 미리보기(pre-release)로 표시된 릴리스는 설치하지 않습니다.
