# 🛒 쇼핑 리스트 앱

오늘 사야 할 것들을 빠르게 기록하고 체크할 수 있는 가벼운 웹앱입니다. 단일 HTML 파일로 동작하며 별도 서버나 빌드 도구가 필요 없습니다.

## ✨ 주요 기능

- **아이템 추가**: 입력창에 텍스트를 입력 후 Enter 또는 "추가" 버튼 클릭
- **완료 체크**: 체크박스로 구매 완료 표시 (취소선 표시)
- **개별 삭제**: 각 항목 우측 × 버튼으로 삭제
- **완료 항목 일괄 정리**: 하단 "완료 항목 지우기" 버튼
- **남은/완료 항목 카운터**: 푸터에 실시간 표시
- **자동 저장**: `localStorage`에 저장되어 새로고침 후에도 유지

## 🚀 사용 방법

1. 이 저장소를 클론하거나 `index.html` 파일을 다운로드합니다.
   ```bash
   git clone https://github.com/hwijang/shopping-listapp.git
   ```
2. `index.html`을 브라우저로 열기만 하면 끝.
   ```bash
   open index.html   # macOS
   ```

별도의 의존성이나 설치 과정이 없습니다.

## 🛠 기술 스택

- **HTML / CSS / JavaScript** (Vanilla)
- **localStorage** — 브라우저에 데이터 영속 저장
- 외부 라이브러리 없음, 빌드 도구 없음

## 📁 프로젝트 구조

```
shopping-listapp/
├── index.html   # 앱 전체 (HTML + CSS + JS 단일 파일)
└── README.md
```

## 📝 라이선스

자유롭게 사용 가능합니다.
