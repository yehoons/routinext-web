# routinext.kr

루티넥스트 공식 웹사이트 (정적 파일).

- 홈 `/`
- 개인정보처리방침 `/privacy/`
- 이용약관 `/terms/`
- 회사 정보 `/company/`

## 고치는 방법

**이 저장소의 HTML을 직접 고치지 마십시오.** 생성물입니다.

원본은 비공개 앱 저장소(`yehoons/RoutineX`)의 `site/` 에 있습니다.

```bash
# 앱 저장소에서
python site/build.py          # docs/legal/*.md → site/public/
# site/public/ 내용을 이 저장소로 복사 후 커밋
```

## 배포

Cloudflare Pages가 이 저장소의 `main` 브랜치를 보고 자동 배포합니다.
빌드 명령 없음, 출력 디렉터리 `/`.
