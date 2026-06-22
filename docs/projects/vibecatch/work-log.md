# 바이브캐치 업무 로그

Slack 채널 `#바이브캐치`에서 확인한 업무성 대화를 날짜별로 정리합니다.

## 정리 범위

- Slack 채널: <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N>
- 확인 범위: 2026-02-03 채널 생성 시점부터 2026-06-22까지 접근 가능한 전체 메시지
- 제외 기준: 채널 입장 메시지, 반복 Jira 봇 요약 원문, 단순 반응, 민감정보가 포함된 원문 세부값
- 민감정보 처리: 계정, 비밀번호, 내부망 주소, 파일 원문 세부값은 본문에 직접 기록하지 않음

## 2026-06

| 일자 | 주제 | 업무 기록 | 원문 |
| --- | --- | --- | --- |
| 2026-06-22 | Jira 현황 | 2026-06-19 기준 총 3건, 해야 할 일 2건, 개발중(BE) 1건으로 공유됨. | 채널 |
| 2026-06-18 | ISMS-P 조치 | 개인정보처리방침 링크 강조 요청. 이전 심사에서 바로가기 버튼 강조 부족 지적이 있었고, 볼드 적용 필요. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781765209614319> |
| 2026-06-18 | 헤더 알림 | 헤더 알림 영역 화면설계 v1.68 배포 완료. 알림, 읽음, 알림 없음 상태와 정책 문서 링크 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781764914785209> |
| 2026-06-18 | 알림 정책 | 알림 scope를 개인 전역과 워크스페이스 단위로 구분. SNS 연동 이슈는 등록자와 워크스페이스 관리자에게 전달하는 방향. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781764914785209> |
| 2026-06-18 | 화면설계 v1.68 | 테스트 시나리오 완성 공지. 페이지 새로고침 후 미반영 시 캐시 삭제 안내. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781757962648619> |
| 2026-06-18 | 실시간 키워드 다이제스트 | 콘텐츠 정렬 시 에러 페이지로 진입하는 현상 확인 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781743275504079> |
| 2026-06-17 | 기기 관리 | 기기 한도 초과 모달, 날짜/시간 표기, 빈/로딩/에러 상태, 강제 로그아웃 alert 필요 여부 논의. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781682807414279> |
| 2026-06-17 | 인증 보안 | 기기 초과 후 재로그인은 신규 `POST /auth/login/continue`와 httpOnly `pendingToken` 쿠키 방식으로 정리. 이메일/비밀번호 재전송은 지양. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781682807414279> |
| 2026-06-17 | 이상징후 감지 | 기준 평균 언급량 산출 범위와 임계치 정보가 필요하다는 질문 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781674990720459> |
| 2026-06-17 | SNS 수집 실패 이벤트 | SNS 수집 실패 이벤트 명세 문서 전달 및 확인 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781674027147299> |
| 2026-06-17 | 인스타그램 수집 중단 알림 | 알림 대상은 워크스페이스 관리자와 계정 등록자이나, 실제 재연결 관리는 계정 등록자만 가능하다는 권한/문구 이슈 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781672733768749> |
| 2026-06-17 | 로그인 API 오류 | 로그인 API 500 오류 확인 요청. 원문에 계정/비밀번호가 포함되어 있어 위키에는 세부값 미기록. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781663612076039> |
| 2026-06-16 | AI 예상 언급량 | 현재 언급량은 이번 주 누적, AI 예상 언급량은 다음 주 예측, 예측 근거는 직전 완료 4개 주차 데이터로 정리. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781576151983269> |
| 2026-06-16 | 동기간 대비 | 특정 기간 조회 시 선택 기간과 동일 길이의 직전 기간을 비교. 빠른 날짜 선택에는 전주 대비/전반부 대비/월초 대비 표현 사용 가능. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781576151983269> |
| 2026-06-16 | 키워드 비교 주가 표시 | 사용자 입력 키워드와 종목 매핑 방식, 복수 후보 선택 UI, 실시간 주가/해외 종목 지원 여부 확인 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781572335886319> |
| 2026-06-15 | 화면설계 v1.67 | 기기 관리, 워크스페이스 초대 수락/거절, 테스트 시나리오 초안 업데이트. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781521187896839> |

## 2026-05

| 일자 | 주제 | 업무 기록 | 원문 |
| --- | --- | --- | --- |
| 2026-05-28 | 영향력/수집기 업데이트 | 하이닉스/텔레콤 문의 대응으로 영향력 표를 갱신하고 수집기 목록 관련 업데이트 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779946494317819> |
| 2026-05-27 | 화면설계 v1.65 | 실시간 키워드 다이제스트, 여론 동향, 마이페이지 SNS 연동관리 업데이트. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779868230010929> |
| 2026-05-27 | 키워드 추천 주기 | `/workspaces/{workspaceId}/keywords/{keywordId}` 응답의 모든 채널 `recommendedCycleMinutes`가 null인 현상 확인 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779857154206699> |
| 2026-05-27 | AI 요약 오인식 | 게시글 작성자명 때문에 AI 요약이 본문 주어를 오인식한 사례 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779848555633549> |
| 2026-05-27 | 관련어 추적 | 다중 키워드 선택 시 관련어가 어떤 콘텐츠/키워드를 통해 추출됐는지 추적 가능 여부 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779846271870839> |
| 2026-05-27 | 관련어 파일 출력 | 수집키워드별 연관어 언급량 조회 및 순위 파일 출력 가능성 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779848340556949> |
| 2026-05-26 | 워크스페이스 정보 조회 | 워크스페이스 구독 정보 없음 오류 확인 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779783050332379> |
| 2026-05-26 | 원문 링크 | 실시간 키워드 다이제스트 관련 콘텐츠에 원문 링크 추가 의견 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779781358687309> |
| 2026-05-26 | 리포트 기능 | 키워드별 일간/주간/월간 요약 리포트는 1차 오픈 후 8월 중 기능 추가 방향. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779772876003069> |
| 2026-05-26 | SNS 연동 | 인스타그램 로그인 실패 사유 구분값, 토큰 저장 실패/Meta API 응답 실패/권한 부족/네트워크 오류 등의 구분 가능성 질의. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779756820136999> |
| 2026-05-26 | 영향력 색상 | 소셜모니터 관련어 노출 색상 기준 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779763426421229> |
| 2026-05-22 | 소셜모니터 화면설계 | 영향력 지표 가이드 버튼/새 창, 데이터 팝업 다운로드 description 추가. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779423546519659> |
| 2026-05-22 | 기능 얼라인 | 소셜모니터 영향력 지표, 관련어 노출 팝업, 리포트, 인스타그램 연동 가이드가 바이브캐치와 연결됨. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779417115101389> |
| 2026-05-22 | 화면설계 v1.64 | 고객지원 1:1 문의 신규 화면과 답변 완료 alert, 처리중 description 수정. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779410192248129> |
| 2026-05-21 | Meta for Developers | 인스타그램 콘텐츠 수집/계정 연동을 위해 팀/회사 Meta for Developers 계정 필요. 기존 개인 계정보다 회사 계정 생성 권장. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779341933065319> |
| 2026-05-21 | 인스타그램 연동 가이드 | 기획/FE 공용 문서 전달. 일반 계정은 수집 불가하여 비즈니스/크리에이터 계정 전환 안내 플로우 필요. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779341451046939> |
| 2026-05-21 | 1:1 문의 목록 API | 1:1 문의 목록 조회 API에 keyword 검색 파라미터 누락 확인 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779340061014939> |
| 2026-05-21 | 클라우드 배포 | 클라우드 환경 배포 방식 관련 스레드 생성. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779338863184569> |
| 2026-05-21 | AI 감지 유사도 | 키워드 설정에서 AI 감지-키워드 유사도 API 호출 시점 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779336794970439> |
| 2026-05-21 | 작성자 추정 정보 | 작성자 추정 정보 관련 스레드 생성. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779328670719939> |
| 2026-05-20 | 권한관리 ISMS-P | 운영자 마스터만 계정 생성/삭제 가능하도록 권한 적용. 운영자 일반/광고주 마스터는 광고주 회원 목록 조회만 가능. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779268698145139> |
| 2026-05-20 | 영향력 산정 기준표 | 특정 URL 진입 시 백엔드에서 영향력 산출 기준표를 보여주는 기능 적용. 프론트 바로가기 버튼 필요 시 추가 요청 예정. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779268698145139> |
| 2026-05-20 | 1:1 문의 답변 | 관리자 답변 화면, 자동 답변 2종, 담당자 배정 시점/처리중 상태 관련 기획 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779260095606659> |
| 2026-05-20 | 공지사항 카테고리 API | 공지사항 카테고리 탭을 글이 있는 카테고리만 동적 노출하기 위해 `/notices/categories` 신규 endpoint 제안. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779237051128659> |
| 2026-05-19 | ISMS-P 심사 | 소셜모니터 계정생성/삭제 권한은 운영자 Master만 가능해야 함. 휴대전화번호 1년 보관과 위탁업체 개인정보 폐기 확인 책임도 논의. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779173138533389> |
| 2026-05-19 | AI 인사이트 API | `dateRangeLabel` 값이 기존 “최근 30일” 라벨에서 날짜 범위 문자열로 내려오는 현상 확인 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779173055021749> |
| 2026-05-19 | 여론동향 description | 여론 동향 페이지 26번 description 제외 여부 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779165099569179> |
| 2026-05-18 | 필터 옵션 날짜 파라미터 | `filter-options` API에 `dateFrom`, `dateTo` 쿼리 파라미터 추가 필요. 실제 수집된 국가/지역만 반환해야 함. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779089813380189> |
| 2026-05-18 | 키워드 검색 API | `/workspaces/{workspaceId}/keywords/search` 응답의 `data.keywords`, `data.categories`에 `pageInfo` 누락 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779085908994779> |
| 2026-05-18 | DB 전환 | 바이브캐치 API DB가 MariaDB에서 PostgreSQL로 변경 예정. 반영 중/직후 일시 오류 가능성 공지. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779067994025989> |
| 2026-05-18 | 필터 옵션 국가/지역 | `filter-options` API에서 countries/regions가 빈 배열로 내려와 필터 모달에 값이 미노출되는 현상 확인 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1779067037623989> |
| 2026-05-15 | 관련 콘텐츠 pageSize | `/contents/{contentId}/related` API에서 pageSize를 다르게 전달해도 항상 30개 반환되는 현상 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1778819943141089> |

## 2026-04

| 일자 | 주제 | 업무 기록 | 원문 |
| --- | --- | --- | --- |
| 2026-04-24 | 일별 그래프 기준 | 실시간 키워드 다이제스트 일별 그래프가 선택일 D 기준 D-7~D로 산출되는지, 하단 콘텐츠 기간도 동일한지 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1777004914815589> |
| 2026-04-23 | enum-labels API | enum 라벨 매핑 전용 `/enum-labels` API 추가. 앱 부팅 시 1회 호출 후 전역 캐시하는 패턴. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776942014476869> |
| 2026-04-23 | 키워드 API | `/keywords/count` 신설, `/keywords/summary`에 파라미터 추가. Swagger와 프론트 가이드 확인 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776937504042669> |
| 2026-04-23 | 화면설계 v1.6 | 키워드 설정 상세의 등록 가능 수 추가, 인스타그램 전용 영역 텍스트 변경. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776919658560039> |
| 2026-04-22 | 최근 방문 페이지 | 헤더 메가메뉴 최근 방문 페이지는 계정 단위 저장 필요. `GET/POST /users/me/recent-pages` 제안, LRU 최대 6개, 현재 페이지 제외 등 FE 스펙 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776837323735249> |
| 2026-04-21 | 국가/지역 라벨 매핑 | 실시간 키워드 다이제스트 AI 요약의 국가/지역 값 변환 및 매핑 API 필요. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776762069004339> |
| 2026-04-21 | 트렌드 알림 메시지 | `/realtime/daily-graph` API에서 트렌드 알림 메시지 값 미전송 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776756440449099> |
| 2026-04-21 | 키워드 비교 API | `/reports/compare/buzz` 응답을 `seriesByKeyword` 객체에서 `series` 배열로 변경, `shareData.keywordId` 추가, `priceByKeyword` 삭제. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776753280155999> |
| 2026-04-21 | API mock | 실시간 다이제스트/여론 동향/키워드 비교 API의 페이지네이션 및 필터 파라미터별 데이터 변화 세팅 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776749418780669> |
| 2026-04-21 | 키워드 프리셋 소유자 | `keyword-presets` 응답 items에 `isOwner` boolean 추가 요청. 공유 프리셋 삭제 버튼 노출/차단 판단용. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776735596819279> |
| 2026-04-20 | 키워드 비교 색상 | 테이블 셀 배경색을 행 내 상대 순위 기준으로 할지, 퍼센트 구간 기준으로 할지 논의. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776658882564649> |
| 2026-04-20 | 페이지별 필터값 API | 이전 API 피드백 회의에서 논의한 페이지별 필터값 조회 API 확인 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776658755363669> |
| 2026-04-20 | 채널/카테고리 매칭 | 채널별 카테고리-수집기 매칭 스프레드시트 공유. 유튜브, X, 인스타그램, 페이스북, 블로그, 카페, 커뮤니티, 뉴스, 지식인, 정부/공공, 기업/단체, 기타 12개 분류. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776651223762449> |
| 2026-04-20 | 백엔드 인프라 | 바이브캐치 백엔드 인프라와 데이터 흐름도 공유. 프리셋별 독립 수집 스케줄, 동적 인프라 확장, 안정적 DB 커넥션, ETL 워커 취합 필요. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776649249281319> |
| 2026-04-20 | 수집 정책 | 유튜브/뉴스 댓글은 정책 및 저작권 이슈로 수집/노출하지 않음. 유튜브 조회수는 알림 임계값 조건에 필요하므로 수집. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776649249281319> |
| 2026-04-20 | API 가이드 | Swagger API 명세, 프론트 API 가이드, mock response 사용 가이드 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776643325335599> |
| 2026-04-17 | 카테고리 옵션 | 화면별 카테고리 옵션 차이와 `수집 채널` 워딩을 `카테고리`로 변경할지 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776399353874619> |
| 2026-04-17 | 알림 영향력 선택 | 알림 등록/수정 페이지에서 영향력 복수 선택 가능 여부 확인. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776391796272909> |
| 2026-04-16 | 카테고리/채널 용어 변경 | 카테고리/채널 정의 변경에 따라 API URL, 파라미터, request/response 변경 문서 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776324809112999> |
| 2026-04-16 | AI 분석 문의 | AI 분석 문의사항 스레드 생성. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776312548080179> |
| 2026-04-16 | 화면설계 v1.5 | 키워드 비교 프리셋 삭제 버튼, 삭제 alert, toast popup 케이스 추가. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776303241476589> |
| 2026-04-16 | 프로젝트 일정 | 개발 ~6/30, 개발자 단위 테스트 7/1~7/10, 기획 QA 7/13~7/31 일정 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776300271066549> |
| 2026-04-15 | Swagger/API 회의 | Swagger API 명세와 회의 일정 공유. API 컨벤션 수정 필요 부분과 일정 논의 예정. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776216290488919> |
| 2026-04-15 | API 가이드 업데이트 | Swagger API 명세와 프론트엔드 가이드 문서 업데이트, 회의 피드백 반영. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776257317164609> |
| 2026-04-15 | 키워드 비교 API 질의 | 버즈량/버즈량 추이 API 누락, 작성자 토글 범위, `mixed` 감성 의미, 등급 enum을 S~D에서 1~5로 변경 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776239440168529> |
| 2026-04-15 | 프리셋 삭제 | 등록한 프리셋 삭제 기능은 화면설계서 추가 후 업데이트 예정. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1776241535927289> |

## 2026-02

| 일자 | 주제 | 업무 기록 | 원문 |
| --- | --- | --- | --- |
| 2026-02-24 | SKT 회의록 | 전일 SKT 미팅 회의록 공유. 당장 개발해야 할 내용은 아니며 업무 참고용. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1771895892722749> |
| 2026-02-24 | 수집 비용 | Apify 수집 비용이 1/22~2/21 기간에 큰 폭으로 소진된 이슈 공유. 유튜브 자막과 Google Trends 기반 연관 키워드 수집에서 비용 발생이 큼. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1771930254295639> |
| 2026-02-24 | 수집기 표준화 | 수집기는 검색어별로 개별 검색 후 키워드 데이터로 연결. 3월 중 수집기 동작 표준화 예정이며, 표준을 바이브캐치에 확장 적용할 계획. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1771930254295639> |
| 2026-02-24 | 기존 기획 자료 | 알림 메일 발송 포맷, SK하이닉스 대시보드 기능 정의서 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1771928466779009> |
| 2026-02-24 | 중복 키워드 | 키워드 설정 시 수집 키워드 중복 허용 여부 질문. 예: SK하이닉스와 SKT 프리셋에 동일 키워드가 포함될 수 있는지. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1771900574633719> |
| 2026-02-20 | 알림 기능 고도화 | SK하이닉스 요구사항 반영을 위해 알림 기능 고도화 관련 문의 시작. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1771562234556959> |
| 2026-02-19 | 데이터 단계 분리 | 데이터 신속성을 위해 1차 수집단계와 2차 분석단계를 나눠 정의할 필요가 있음. 수집 속도와 분석 속도를 별도로 명시해야 함. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1771491747293729> |
| 2026-02-19 | 소셜모니터 설계서 | 소셜모니터 화면설계서 최종본 공유 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1771464280829689> |
| 2026-02-12 | 수집기 성능 지표 | 수집기 벤치마크 측정시간, 검색량, 신규 수집량, 22개 키워드 기준 추산 전체 소요시간 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1770885649484739> |
| 2026-02-12 | OTP 인증 | 소셜모니터링 OTP 인증 도움 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1770855800748179> |
| 2026-02-11 | 유튜브 정책 | 유튜브 정책 위반 관련 메일 공유. 정식 제품화 시 정책 위반 내용에 대해 사업적 협의 필요. 원문에는 데모 계정 정보가 있어 위키에는 미기록. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1770798506320819> |
| 2026-02-10 | 정책 초안 | 바이브캐치 관련 정책 정리 문서 공유. 원문에는 로그인 계정/초기 비밀번호가 있어 위키에는 세부값 미기록. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1770696906592929> |
| 2026-02-06 | 뉴스 원문 저작권 | 백엔드 로직 미팅 후 뉴스 원문 활용 저작권 이슈를 Confluence에 정리. 실무자가 전체 맥락을 이해하도록 공유. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1770339126915849> |
| 2026-02-05 | 백엔드 로직 Q&A | 바이브캐치 기획을 위해 기존 소셜모니터링 백엔드 로직, 데이터 수집 항목, 작동 방식 설명/Q&A 미팅 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1770265268705469> |
| 2026-02-03 | 채널 생성/기획 착수 | 바이브캐치 기획 진행을 위해 실제 개발 기술 정보와 소셜모니터링/데이터 수집 담당자 초대 요청. | <https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1770094759565719> |

## 반복 봇 요약 처리 기준

`aibizsolution-bot`의 Jira 요약은 업무 현황 추적에는 유용하지만, 거의 매일 반복되는 상태 집계입니다. 이 문서에는 개별 봇 메시지 전체를 복제하지 않고, 중요한 일정/상태 변화가 있는 경우 타임라인과 운영 메모에 요약합니다.
