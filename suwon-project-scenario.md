# 문화의 도시 수원 — 제작 및 배포 시나리오

작성일: 2026년 10월 25일

## 1. 프로젝트 목적

LEEJINHEANG의 고향인 수원을 소개하는 개인용 웹사이트를 제작한다. 수원의 명소와 문화, 여행 코스, 맛집을 소개하며, 우선 무료 계정과 무료 호스팅을 사용한다.

## 2. 시작 환경과 첫 편집

- 원본 파일: `C:\Workshop\sites\stu10\index.html`
- 작업 폴더: `C:\Users\opc\Documents\ChatGPT\C++`
- 최초 공개 주소: https://stu10.oraclebio.kr/
- 처음에는 VS Code로 열기를 요청했으나, 이후 Visual Studio를 의미한다고 확인했다.
- 설치된 Visual Studio Community 2026을 찾아 파일을 편집 모드로 열도록 실행했다. 이후 확인한 실행 화면은 초기 로그인 화면이었다.
- 기본 페이지의 큰 제목을 `LEEJINHEANG`으로 변경했다.
- 원본 파일은 일반 실행 계정에 읽기 권한만 있어 직접 저장이 거부됐다. 사용자의 승인에 따라 Windows 관리자 권한으로 파일 저장을 실행했고, 원본에 변경된 내용을 확인했다.
- 실제 공개 사이트에서 이름이 표시되는 것을 확인하고 스크린샷을 저장했다.

## 3. 초기 양식 백업

웹사이트를 새롭게 만들기 전, 이름이 반영된 초기 양식을 별도 HTML 파일로 저장했다.

- 백업: `C:\Users\opc\Documents\ChatGPT\C++\stu10-backup.html`
- 백업 당시 원본과 파일 해시가 같은 것을 확인했다.

## 4. 주제 선정과 웹사이트 제작

여러 웹사이트 아이디어를 검토한 뒤, 사용자의 요청에 따라 수원 소개 사이트로 방향을 정했다.

### 첫 화면과 이동 구조

- 첫 화면 제목: **수원에 대해 소개합니다!**
- 작성자: **LEEJINHEANG**
- **다음** 버튼을 누르면 여섯 장소의 목차가 표시된다.
- 장소 카드를 누르면 사진, 소개글, 즐기는 방법, 사진 출처가 있는 상세 화면으로 이동한다.
- 상세 화면에서 이전·다음 장소 및 목차로 이동할 수 있다.

### 첫 번째 테마: 수원 명소 여섯 곳

1. 행궁동·행리단길
2. 방화수류정·용연
3. 수원화성·화성행궁
4. 스타필드 별마당도서관
5. 일월수목원
6. 수원 통닭거리

수원시 공식 관광 안내 등을 검색해 실제 장소 사진과 정보를 확인했다. 사진은 HTML 파일 안에 포함해 별도 이미지 폴더 없이 파일 하나로 화면이 표시되도록 구성했다.

### 문구와 번호 수정

- 상단 제목을 `나의 고향, 수원`에서 **문화의 도시 수원**으로 변경했다. 브라우저 제목과 하단의 동일 문구도 함께 변경했다.
- 첫 화면 하단을 **경기도 수원에 대한 첫번째 게시글**로 변경했다.
- 장소 카드의 표기를 `01 / SUWON`에서 **SUWON / 01** 형식으로 바꿨다. 여섯 카드 모두 `SUWON / 01`부터 `SUWON / 06`으로 표시한다.

## 5. 두 번째 테마: 문화와 여행

기존 여섯 장소 아래에 추가 게시글 두 개를 배치했다.

### ARTICLE / 01 — 수원시립미술관 소개

- 미술관 외관 사진과 소개글
- 작품을 감상하는 방법과 관람 순서 제안
- 주소, 관람시간, 휴관일, 관람료 안내
- 현재 전시와 관람 안내를 확인할 공식 홈페이지 링크
- 행궁동 산책과 함께 즐기는 방법

관람 정보는 2026년 10월 25일 확인한 내용을 기준으로 작성하고, 방문 전 공식 안내를 확인하도록 표시했다.

### ARTICLE / 02 — 반나절 여행 코스

약 4시간의 제안 일정으로 구성했다. 공식 운영 일정이나 확정된 이동시간을 뜻하지 않는다.

| 시간 예시 | 장소 | 활동 |
| --- | --- | --- |
| 13:00–14:00 | 화성행궁 | 역사와 건축 관람 |
| 14:00–15:00 | 행궁동·행리단길 | 골목 구경과 카페 휴식 |
| 15:00–16:00 | 방화수류정·용연 | 이동, 산책과 풍경 감상 |
| 16:00–17:00 | 수원 통닭거리 | 이동과 이른 저녁 |

- 각 장소의 기존 소개 화면으로 이동하는 링크를 넣었다.
- 미술관 관람을 추가할 경우 시간을 더 확보하도록 안내했다.
- 출발지까지의 교통시간은 별도이며, 실제 소요시간은 걷는 속도와 대기 등에 따라 달라진다고 표시했다.
- 처음에는 게시글 번호가 `02`, `03`이었으나 사용자 요청으로 목록과 상세 화면 모두 `01`, `02`로 수정했다.

## 6. 세 번째 테마: 수원 맛집 열 곳

사용자는 네이버 리뷰 1,000개 이상인 수원 맛집 열 곳을 요청했다. 기준은 **네이버 방문자 리뷰 1,000개 이상**으로 정했다.

### 확인 방법

- 네이버 플레이스의 방문자 리뷰 탭을 직접 열었다.
- 해당 탭 본문에 표시된 ‘리뷰’ 수를 확인했다.
- 블로그 리뷰 및 별도로 표시된 키워드·별점 리뷰는 합산하지 않았다.
- 기준에 미달한 후보인 수원만두는 최종 목록에서 제외했다.
- 수치 확인일은 2026년 10월 25일이며, 자동 갱신 기능은 없다.
- 식당 나열 순서는 맛의 순위가 아니다.

### 최종 선정 목록

| 번호 | 식당 | 확인한 방문자 리뷰 수 | 대표 메뉴 |
| --- | --- | ---: | --- |
| FOOD / 01 | 가보정 | 3,606 | 생갈비·양념갈비 |
| FOOD / 02 | 본수원갈비 | 3,209 | 생갈비·양념갈비 |
| FOOD / 03 | 신림춘천집 수원역직영점 | 8,395 | 닭갈비 |
| FOOD / 04 | 돌판짜장 짜마 수원행궁동본점 | 12,128 | 돌판짜장·탕수육 |
| FOOD / 05 | 이모네손칼국수 | 1,821 | 칼국수 |
| FOOD / 06 | 마포본가 본점 | 1,347 | 돼지양념구이·냉면 |
| FOOD / 07 | 로마경양식 | 1,609 | 돈까스·왕돈까스 |
| FOOD / 08 | 보영만두 북문본점 | 4,202 | 군만두·쫄면 |
| FOOD / 09 | 진미통닭 | 5,175 | 후라이드·양념통닭 |
| FOOD / 10 | 요미우돈교자 | 19,768 | 넓적우동·교자 |

각 카드에 대표 메뉴, 짧은 소개, 주소, 리뷰 수, 확인 날짜, 네이버 리뷰 링크와 지도 링크를 넣었다. 맛집 테마는 별도의 식당 사진 없이 정보 카드로 구성했다.

확인 기록: `C:\Users\opc\Documents\ChatGPT\C++\suwon-food-review-evidence.json`

## 7. 구현과 검증

- HTML, CSS, JavaScript로 만든 정적 웹사이트다.
- 사진은 base64 데이터로 HTML 안에 포함돼 있다.
- 별도 서버, 데이터베이스, 패키지 설치나 빌드 없이 표시된다.
- 화면 이동은 URL의 해시(`#`)로 처리한다.
- 화면 폭에 따라 카드와 첫 화면의 배치가 달라진다.
- 실제 사이트에서 사진 로딩, 다음 버튼, 여섯 상세 화면, 추가 게시글, 테마 이동을 확인했다.
- 맛집 카드가 정확히 열 개인지, 각 확인 수치가 1,000개 이상인지 검사했다.
- JavaScript 구문과 배포 설정 JSON을 검사했다.
- 주요 수정 및 배포 결과의 스크린샷을 작업 폴더에 저장했다.

### 주요 화면 주소

| 화면 | 해시 |
| --- | --- |
| 첫 화면 | `#home` |
| 명소 목차 | `#contents` |
| 명소 상세 | `#place-1` ~ `#place-6` |
| 문화와 여행 목록 | `#stories` |
| 미술관 게시글 | `#post-museum` |
| 반나절 코스 게시글 | `#post-halfday` |
| 맛집 열 곳 | `#food` |

## 8. GitHub 소스 첫 저장

사용자는 GitHub에 소스를 먼저 저장한 뒤, Vercel에서 무료로 배포하기를 요청했다.

- 별도 배포 폴더를 만들어 C++ 프로젝트나 기타 백업 파일이 함께 업로드되지 않도록 했다.
- GitHub 사용자 이름: **teg312v**
- 사용자가 생성한 최초 저장소: **ddollee**
- 공개 저장소에 아래 다섯 파일을 업로드했다.
  - `index.html`
  - `README.md`
  - `vercel.json`
  - `food-review-sources.json`
  - `.gitignore`
- 최초 커밋 메시지: `Initial release: Suwon culture website`
- 최초 커밋: `45aa05e8e39a806e36de6a4ad4f101f8649a3a41`

현재 저장소: https://github.com/teg312v/suwon

배포 폴더: `C:\Users\opc\Documents\ChatGPT\C++\suwon-culture-site`

압축본: `C:\Users\opc\Documents\ChatGPT\C++\suwon-culture-site.zip`

## 9. Vercel 진행 과정과 계정 문제

무료 개인용 **Hobby** 요금제로 진행하려 했으나, 계정 로그인 단계에서 제한이 발생했다. Vercel 프로젝트 생성과 실제 배포는 완료되지 않았다.

### 확인된 오류

1. GitHub 로그인 시:
   > There is already an account associated with your GitHub email address. Please login with your email then link your GitHub account.

   같은 이메일로 기존 Vercel 계정이 있지만 GitHub 로그인 연결이 없다는 안내였다.

2. 사용자가 Google 로그인도 실패했다고 알렸다.

3. 이메일 로그인 시:
   > We are unable to complete your login.

   계정 복구 양식을 작성하라는 안내가 이어졌다.

4. 이후 추가로 확인된 안내:
   > Your account requires further verification.

   계정에 추가 검증이 필요하다는 안내다. 구체적인 제한 사유는 확인되지 않았다.

### 복구 요청

- 복구 양식의 이름에 `LEEJINHEANG`을 입력했다.
- GitHub 사용자 이름 `teg312v`, 당시 저장소 주소, 실제 오류와 개인용 무료 배포 목적을 영어로 정리해 입력했다.
- 문제 유형은 `Other`로 선택했다.
- 양식을 작성한 뒤에는 제출 전 상태로 사용자에게 보여주었다.
- 이후 사용자가 직접 제출했고 답변을 기다리고 있다고 확인했다.

### 현재 상태

- Vercel 계정 복구 답변 및 추가 검증을 기다리는 상태다.
- 계정 제한을 설정으로 해제하거나 우회하지 않았다.
- 사이트 소스 오류나 요금제 결제 문제로 확인된 것은 아니다.
- 계정 접근이 복구되면 현재 저장소 `teg312v/suwon`을 연결하고 무료 Hobby로 배포한 뒤 실제 접속을 확인할 예정이다.
- 복구 신청 당시 저장소는 `teg312v/ddollee`였지만 이후 `teg312v/suwon`으로 이름을 변경했다.

## 10. 긴급 대안: GitHub Pages 무료 배포

사용자가 당장 사이트를 사용해야 한다고 요청해 GitHub Pages로 무료 배포를 진행했다.

### 설정

- 저장소 Settings → Pages
- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`
- 기본 GitHub Pages 주소와 HTTPS 사용

### 배포 결과

- GitHub Actions의 `pages build and deployment` 실행이 성공한 것을 확인했다.
- 실행 기록: https://github.com/teg312v/suwon/actions/runs/40169924308
- 최초 배포 주소: `https://teg312v.github.io/ddollee/`
- 실제 공개 주소에서 첫 화면 사진, 다음 버튼, 목차와 맛집 테마 이동을 확인했다.

## 11. 공개 주소 변경

사용자는 주소를 `teg312v.github.io/suwon/`으로 바꾸기를 요청했다.

- 저장소 이름을 `ddollee`에서 **suwon**으로 변경했다.
- 새 GitHub 저장소: https://github.com/teg312v/suwon
- 새 공개 사이트: https://teg312v.github.io/suwon/
- 새 주소에서 첫 화면 사진과 메뉴 이동, 맛집 열 곳 표시를 확인했다.
- 별도 유료 도메인은 구매하지 않았다.

이후 공유할 주소는 **https://teg312v.github.io/suwon/** 이다.

## 12. 주요 로컬 파일

| 용도 | 경로 |
| --- | --- |
| 최초 원본 사이트 | `C:\Workshop\sites\stu10\index.html` |
| 초기 양식 백업 | `C:\Users\opc\Documents\ChatGPT\C++\stu10-backup.html` |
| 현재 작업용 HTML | `C:\Users\opc\Documents\ChatGPT\C++\suwon-site.html` |
| 배포용 HTML | `C:\Users\opc\Documents\ChatGPT\C++\suwon-culture-site\index.html` |
| 배포 안내 | `C:\Users\opc\Documents\ChatGPT\C++\suwon-culture-site\README.md` |
| Vercel 설정 | `C:\Users\opc\Documents\ChatGPT\C++\suwon-culture-site\vercel.json` |
| 배포 소스 압축본 | `C:\Users\opc\Documents\ChatGPT\C++\suwon-culture-site.zip` |
| 맛집 확인 기록 | `C:\Users\opc\Documents\ChatGPT\C++\suwon-food-review-evidence.json` |
| 새 주소 확인 이미지 | `C:\Users\opc\Documents\ChatGPT\C++\suwon-new-address.png` |
| 이 시나리오 기록 | `C:\Users\opc\Documents\ChatGPT\C++\suwon-project-scenario.md` |

## 13. 출처와 이용조건

- 수원 명소 사진과 관광 정보: [수원시 추천 여행코스](https://www.suwon.go.kr/sw-www/sw-visitsuwon/sw-visitsuwon-02/sw-visitsuwon-02-01/sw-visitsuwon-02-01-01.jsp), [감성 핫플레이스 코스](https://www.suwon.go.kr/sw-www/sw-visitsuwon/sw-visitsuwon-02/sw-visitsuwon-02-05/sw-visitsuwon-02-05-02.jsp)
- 미술관 사진: [수원시 제공 관광 콘텐츠를 이용한 남수헌 안내](https://www.namsuheon.kr/main/?menu=72)
- 사진 조건: 공공누리 제4유형, 출처표시·상업적 이용금지·변경금지
- 미술관 관람 정보: [수원시립미술관](https://suma.suwon.go.kr/views/info.do)
- 코스 참고: [수원문화재단](https://www.swcf.or.kr/?p=66)
- 식당 리뷰 수: 각 식당 네이버 방문자 리뷰 페이지. 개별 링크는 확인 기록 JSON 및 사이트에 포함돼 있다.

## 14. 다음에 이어서 할 일

1. Vercel에서 복구 요청 답변을 받으면 요구된 확인 절차를 진행한다.
2. 계정 접속 후 무료 개인용 Hobby 요금제를 확인한다.
3. GitHub의 `teg312v/suwon` 저장소를 연결한다.
4. 정적 사이트로 배포하고 사진, 버튼, 각 게시글과 맛집 화면을 확인한다.
5. Vercel 배포가 완료되면 새 공개 주소를 별도로 기록한다.

현재 바로 이용할 수 있는 사이트는 **GitHub Pages 배포본**이다. 향후 소스를 수정할 때는 로컬 HTML 저장과 GitHub 업로드가 별도 단계라는 점을 확인하고, GitHub에 변경사항을 저장한 뒤 배포 결과를 검증한다.
