# 문화의 도시 수원

LEEJINHEANG의 수원 소개 웹사이트 첫 배포 소스입니다.

## 구성

- 첫 화면과 수원 명소 여섯 곳
- 수원시립미술관 소개 및 반나절 여행 코스
- 네이버 방문자 리뷰 1,000개 이상을 확인한 수원 식당 열 곳

HTML, CSS, JavaScript를 `index.html`에 포함했습니다. 사진도 파일에 포함되어 별도 패키지 설치나 빌드가 필요하지 않습니다.

## 로컬 확인

`index.html`을 브라우저에서 열면 됩니다. 화면 이동은 `#home`, `#contents`, `#stories`, `#post-museum`, `#post-halfday`, `#food` 주소를 사용합니다.

## Vercel 배포

1. 개인 GitHub 저장소에 이 폴더의 파일을 저장합니다.
2. Vercel의 개인용 무료 Hobby 계정에서 해당 저장소를 Import합니다.
3. Framework Preset은 **Other**, Root Directory는 저장소 최상위 폴더를 선택합니다.
4. 별도 Build Command나 환경변수 없이 정적 사이트로 배포합니다.

## 콘텐츠 출처

- 수원 명소 사진: [수원시 관광 추천 코스](https://www.suwon.go.kr/sw-www/sw-visitsuwon/sw-visitsuwon-02/sw-visitsuwon-02-01/sw-visitsuwon-02-01-01.jsp), [핫플레이스 코스](https://www.suwon.go.kr/sw-www/sw-visitsuwon/sw-visitsuwon-02/sw-visitsuwon-02-05/sw-visitsuwon-02-05-02.jsp)
- 미술관 사진: [수원시 제공 관광 콘텐츠를 이용한 남수헌 안내](https://www.namsuheon.kr/main/?menu=72)
- 사진 이용조건: 공공누리 제4유형, 출처표시·상업적 이용금지·변경금지. 사진에 대한 권리는 원저작자에게 있습니다.
- 미술관 관람 정보: [수원시립미술관](https://suma.suwon.go.kr/views/info.do)
- 여행 코스 참고: [수원문화재단](https://www.swcf.or.kr/?p=66)
- 맛집 리뷰 수: 각 식당 네이버 방문자 리뷰 페이지를 2026년 10월 25일 직접 확인했습니다. 확인 근거는 `food-review-sources.json`에 있습니다. 수치는 자동 갱신되지 않습니다.

개인용 비상업적 소개 사이트로 제작했습니다. 외부 콘텐츠에 별도의 재배포 라이선스를 부여하지 않습니다.
