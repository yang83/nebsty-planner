# 개인정보 처리방침 — Nebsty Planner

[English](../privacy.md) · **한국어**

시행일: 2026년 10월 12일

Nebsty Planner(이하 "앱")는 **개인정보를 수집하지 않습니다.** 계정 · 서버 · 광고 · 사용 통계(분석 도구)가 없습니다.

## 1. 앱이 저장하는 정보와 위치
- 플래너에 쓴 내용(할 일 · 일정 · 메모 · 프로젝트 문서 · 이미지)은 **사용자가 고른 데이터 폴더**에 Markdown 파일과 이미지 파일로 저장됩니다. 기본 위치는 `~/Documents/Nebsty Planner` 입니다.
- 앱 설정(데이터 폴더 위치, 동기화 설정, 구독 캘린더 주소 등)은 앱의 설정 폴더에 저장됩니다. Mac App Store 판은 앱 전용 샌드박스 공간(`~/Library/Containers/me.yspace.nebsty-planner/`) 안에 저장합니다.
- Mac App Store 판은 사용자가 고른 데이터 폴더만 열 수 있으며, 그 선택을 macOS 의 보안 북마크(security-scoped bookmark)로 설정에 기억합니다.
- 이 파일들은 사용자의 컴퓨터에만 있으며, 앱이 다른 곳으로 보내지 않습니다. 데이터 폴더를 iCloud Drive · Nextcloud 등 동기화 폴더에 두는 경우, 그 서비스의 정책에 따라 동기화됩니다.

## 2. 미리 알림 · 캘린더 (선택)
- 사용자가 ⚙ 설정 › 외부 동기화에서 켠 경우에만, macOS 의 권한 요청을 거쳐 Apple 미리 알림 · 캘린더에 접근합니다.
- 오늘 마감인 할 일과, 사용자가 고른 캘린더의 일정을 이 Mac 안에서 플래너 파일과 맞춥니다. 이 정보는 앱 밖으로 전송되지 않습니다.
- 권한은 언제든 **시스템 설정 › 개인정보 보호 및 보안**에서 끌 수 있습니다.

## 3. Google Tasks · Google 캘린더 (선택)
- 사용자가 ⚙ 설정 › 외부 동기화에서 **Google 계정 연결**을 누르고 Google 로그인 화면에서 허용한 경우에만 Google 계정에 접근합니다.
- 요청하는 권한: Google Tasks (할 일 읽기 · 쓰기), Google 캘린더 일정 (사용자가 고른 캘린더의 일정 읽기 · 쓰기), 캘린더 목록 (읽기 전용 — 고를 수 있는 캘린더를 보여 주기 위해).
- 앱은 사용자의 컴퓨터에서 Google 서버와 **직접** 통신합니다. 중간에 Nebsty 서버가 없고, 개발자는 사용자의 Google 데이터나 로그인 정보를 볼 수 없습니다.
- 로그인 토큰은 사용자의 컴퓨터, 앱 설정 폴더의 `google_token.json` 에만 저장되며 해당 사용자 계정만 읽을 수 있습니다.
- Google 데이터는 오늘의 할 일 · 일정을 플래너 파일과 동기화하는 데에만 쓰입니다. 광고에 쓰지 않고, 판매하거나 다른 곳에 넘기지 않으며, 사람이 읽지 않습니다. Nebsty Planner 가 Google API 에서 받은 정보를 사용하는 방식은 제한적 사용(Limited Use) 요건을 포함한 [Google API 서비스 사용자 데이터 정책](https://developers.google.com/terms/api-services-user-data-policy)을 따릅니다.
- 접근을 끊으려면 앱에서 **연결 해제**를 누르거나 (Google 쪽 토큰도 폐기됩니다), [myaccount.google.com/permissions](https://myaccount.google.com/permissions) 에서 Nebsty Planner 를 삭제하세요.

## 4. 인터넷 사용
사용자가 직접 켜는 Google 동기화(3항) 외에는, 앱은 다음 경우에만 인터넷에 접속합니다. 어느 경우에도 플래너 내용이나 개인정보를 보내지 않습니다.
- **구독 캘린더(ICS):** 사용자가 직접 넣은 캘린더 주소에서 일정 파일을 내려받습니다.
- **업데이트 확인 (Windows 판만):** Mac App Store 판은 App Store 가 업데이트를 맡으므로 스스로 확인하지 않습니다. Windows 판은 하루 한 번(또는 사용자가 요청할 때) 이 저장소의 공개 파일(`latest.json`)을 읽어 새 버전이 있는지 확인합니다. 이 요청에는 앱 버전 외의 정보가 포함되지 않습니다. GitHub 는 일반적인 웹 서버처럼 접속 기록(IP 주소 등)을 남길 수 있습니다 — [GitHub 개인정보 처리방침](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## 5. 인앱 구매 (Nebsty Pro)
Nebsty Pro 는 App Store 를 통해 판매됩니다. 결제는 전부 Apple 이 처리하며, 앱은 결제 정보나 Apple ID 를 볼 수 없습니다. 앱은 이 Mac 에서 App Store 에 Nebsty Pro 구매 여부만 확인합니다.

## 6. 제3자 제공 · 판매
없습니다.

## 7. 문의
[GitHub Issues](https://github.com/yang83/nebsty-planner/issues) 로 문의해 주세요.

## 8. 변경
이 방침이 바뀌면 이 페이지에 시행일과 함께 알립니다.

