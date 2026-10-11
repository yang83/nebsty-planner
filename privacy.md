# 개인정보 처리방침 — Nebsty Planner

시행일: 2026년 10월 11일

Nebsty Planner(이하 "앱")는 **개인정보를 수집하지 않습니다.** 계정 · 서버 · 광고 · 사용 통계(분석 도구)가 없습니다.

## 1. 앱이 저장하는 정보와 위치
- 플래너에 쓴 내용(할 일 · 일정 · 메모 · 프로젝트 문서 · 이미지)은 **사용자가 고른 데이터 폴더**에 Markdown 파일과 이미지 파일로 저장됩니다. 기본 위치는 `~/Documents/Nebsty Planner` 입니다.
- 앱 설정(데이터 폴더 위치, 동기화 설정, 구독 캘린더 주소, 마지막 실행 날짜 등)은 `~/Library/Application Support/Nebsty Planner/` 에 저장됩니다.
- 이 파일들은 사용자의 Mac 에만 있으며, 앱이 다른 곳으로 보내지 않습니다. 데이터 폴더를 iCloud Drive · Nextcloud 등 동기화 폴더에 두는 경우, 그 서비스의 정책에 따라 동기화됩니다.

## 2. 미리 알림 · 캘린더 (선택)
- 사용자가 ⚙ 설정 › 외부 동기화에서 켠 경우에만, macOS 의 권한 요청을 거쳐 Apple 미리 알림 · 캘린더에 접근합니다.
- 오늘 마감인 할 일과, 사용자가 고른 캘린더의 일정을 이 Mac 안에서 플래너 파일과 맞춥니다. 이 정보는 앱 밖으로 전송되지 않습니다.
- 권한은 언제든 **시스템 설정 › 개인정보 보호 및 보안**에서 끌 수 있습니다.

## 3. 인터넷 사용
앱은 다음 두 경우에만 인터넷에 접속합니다. 어느 경우에도 플래너 내용이나 개인정보를 보내지 않습니다.
- **구독 캘린더(ICS):** 사용자가 직접 넣은 캘린더 주소에서 일정 파일을 내려받습니다.
- **업데이트 확인:** 하루 한 번(또는 사용자가 요청할 때) 이 저장소의 공개 파일(`latest.json`)을 읽어 새 버전이 있는지 확인합니다. 이 요청에는 앱 버전 외의 정보가 포함되지 않습니다. GitHub 는 일반적인 웹 서버처럼 접속 기록(IP 주소 등)을 남길 수 있습니다 — [GitHub 개인정보 처리방침](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## 4. 제3자 제공 · 판매
없습니다.

## 5. 문의
[GitHub Issues](https://github.com/yang83/nebsty-planner/issues) 로 문의해 주세요.

## 6. 변경
이 방침이 바뀌면 이 페이지에 시행일과 함께 알립니다.

---

# Privacy Policy — Nebsty Planner

Effective: October 11, 2026

Nebsty Planner **does not collect personal data.** There are no accounts, servers, ads or analytics.

- **Your planner content** is stored as Markdown and image files in the data folder you choose (default `~/Documents/Nebsty Planner`). App settings are stored in `~/Library/Application Support/Nebsty Planner/`. Nothing is sent anywhere by the app.
- **Reminders & Calendar (optional):** only when you turn on sync, and only after macOS asks for your permission. Matching happens on your Mac; nothing leaves it. You can revoke access in System Settings › Privacy & Security.
- **Network use:** the app downloads only (1) the subscribed calendar (.ics) addresses you enter and (2) a public `latest.json` from this repository to check for updates. No planner content or personal data is sent. GitHub may keep standard server logs (such as IP addresses).
- **Sharing or selling data:** none.
- **Contact:** [GitHub Issues](https://github.com/yang83/nebsty-planner/issues).
