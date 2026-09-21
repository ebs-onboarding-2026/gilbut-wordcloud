# 길벗 신간의 언어

길벗출판사 신간 150권의 제목과 부제를 모아 낱말 빈도를 세고, 어떤 말이 얼마나
자주 쓰였는지 한 장으로 보여주는 워드클라우드입니다. 낱말을 누르면 그 말이 들어간
책 목록이 열립니다. 2026년 EBS 신규사원 연수과정 실습 결과물입니다.

## 실행

`gilbut_wordcloud.html`을 브라우저로 열면 됩니다. 외부 라이브러리 없이 HTML 한 파일로
동작하며, 데이터는 파일 안에 들어 있습니다.

## 구조

```
gilbut_books.csv       수집 데이터 150권 (제목·부제·저자·가격·쪽수·발행일·표지 URL)
gilbut_wordcloud.html  워드클라우드 + 낱말별 도서 목록 (단일 파일)
.agents/skills/        작업에 쓴 에이전트 스킬 (find-skills, karpathy-guidelines, web-design-guidelines)
```

낱말은 AI · 개발 · 자격증 · 재테크 · 어학 · 생활의 여섯 갈래로 색을 나눠 표시합니다.
`prefers-color-scheme`에 따라 밝은 테마와 어두운 테마가 자동으로 바뀝니다.
