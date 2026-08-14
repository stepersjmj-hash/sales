# 패밀리세일 모아보기

인터넷·SNS에 흩어진 패밀리세일 정보를 한곳에 모아 보여주는 정적 웹페이지입니다.

**👉 바로가기: https://stepersjmj-hash.github.io/sales/**

## 소개

- 진행 중 / 예정 / 종료 상태와 카테고리·장소 필터, 브랜드 검색을 지원합니다.
- 카드를 클릭하면 해당 브랜드의 판매 페이지로 이동합니다.
- 새 세일 발견 시 페이지 하단의 **구글폼으로 제보**할 수 있습니다 (로그인 불필요).

## 구성

| 파일 | 설명 |
|------|------|
| `index.html` | 페이지 전체 (HTML·CSS·JS·데이터 단일 파일) |
| `CLAUDE.md` | 데이터 갱신 워크플로우·카드 작성 규칙 문서 |

데이터는 `index.html` 안의 `const SALES = [...]` 배열 하나로 관리되며,
별도 빌드 과정 없이 GitHub Pages로 바로 서빙됩니다.

## 데이터 출처

- [딜링크 패밀리세일](https://dealink.co.kr/familysale)
- Threads·Instagram [@familysale](https://www.threads.com/@familysale)
- 방문자 구글폼 제보

행사 일정과 할인율은 주최 측 사정에 따라 변경될 수 있으니, 방문·구매 전 공식 채널에서 재확인하세요.
