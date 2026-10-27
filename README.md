# AppMac 배포 파일

AppMac Mac 유틸리티 모음의 설치 파일(DMG)만 올리는 저장소입니다. 소스는 비공개입니다.

## 설치

1. [Releases](https://github.com/hsc142857/AppMac-releases/releases)에서 **AppstallManager** DMG를 받아 `AppstallManager.app`을 Applications로 끌어다 놓습니다.
   - 바로 받기: [AppstallManager.dmg (최신)](https://github.com/hsc142857/AppMac-releases/releases/latest/download/AppstallManager.dmg)
2. 처음 열 때 "확인되지 않은 개발자" 경고가 나오면 **앱을 우클릭 → 열기**, 또는 **시스템 설정 → 개인정보 보호 및 보안 → 그래도 열기**를 누릅니다. (ad-hoc 서명, Apple 공증 안 됨)
3. AppstallManager가 설치되지 않은 AppMac 프로그램을 보여 주며 **"다운로드 및 설치하시겠습니까?"** 를 묻습니다. 창의 **AppMac** 화면에서도 설치·업데이트할 수 있습니다.
4. Dock의 AppstallManager 아이콘을 누르면 프로그램이 Dock 스택처럼 부채꼴로 펼쳐집니다.

## 프로그램

| 프로그램 | 내용 |
|----------|------|
| AppstallManager | AppMac의 시작점 — AppMac 프로그램 설치·업데이트, Dock 펼치기, 설치 기록 기반 앱 관리 |
| ZipWinZip | Windows에서도 한글 이름이 유지되는 ZIP 압축·ZIP/ALZ/EGG 해제 |
| yt-dlp GUI | yt-dlp 기반 영상 다운로더 (yt-dlp·ffmpeg는 따로 설치, 앱 안에 설치 도우미) |

각 프로그램 DMG를 직접 받아 설치해도 됩니다.

## 릴리스 규칙

- 태그: `<프로그램>-v<버전>` (예: `ZipWinZip-v1.1.0`), 파일: 프로그램 DMG 하나
- AppstallManager는 정식 릴리스 중 가장 높은 버전을 받고, GitHub가 제공하는 SHA-256으로 파일을 확인한 뒤 설치합니다.
- 미리보기(pre-release)로 표시된 릴리스는 설치하지 않습니다.
- 이전에 시험하던 AppMacShell은 AppstallManager로 합쳐져 배포를 멈췄습니다.
