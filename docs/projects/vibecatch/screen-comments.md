# 바이브캐치 화면 코멘트

화면 설계 리뷰 시스템의 코멘트/디스크립션에서 확인한 업무성 내용을 화면별로 정리합니다. Slack에서 논의된 정책과 이어지는 내용은 함께 참고할 수 있도록 관련 Slack 기록을 덧붙입니다.

## 회원가입 화면

- 화면: VibeCatch 사용자 > 회원관련 > 회원가입
- 경로: `app/preview/vibecatch/auth/signup.html`
- 확인일: 2026-06-22
- 리뷰 데이터: 코멘트 0건, 디스크립션 11건

### 입력 및 인증 정책

| 항목 | 업무 기록 | 원문 |
| --- | --- | --- |
| 이메일 입력 | 이메일은 `example@email.com` 형태의 올바른 주소 형식을 사용합니다. 한 글자 이상 입력하면 placeholder는 사라지고 입력값을 표시합니다. 계정 인증 정책과 연결됩니다. | [🔗](https://screen-workspace.web.app/workspace-next?ws=vibecatch&viewport=desktop&page=app%2Fpreview%2Fvibecatch%2Fauth%2Fsignup.html&tab=descriptions&item=description-0815f948-083c-45d0-9fb1-3df081dad9ce) |
| 이메일 인증 요청 | 이메일 미입력 또는 형식 불일치 시 인증 요청 버튼은 비활성화합니다. 이메일 형식이 충족되면 활성화하고, 클릭 시 입력 이메일로 6자리 인증번호를 발송합니다. | [🔗](https://screen-workspace.web.app/workspace-next?ws=vibecatch&viewport=desktop&page=app%2Fpreview%2Fvibecatch%2Fauth%2Fsignup.html&tab=descriptions&item=description-066737a0-25b6-4711-a3ac-87c20825205c) |
| 휴대폰번호 입력 | 숫자만 입력 가능하며 최소 7자, 최대 11자입니다. 포커스 아웃 시 자동 하이픈을 적용합니다. `+82` 케이스는 `010` 또는 `10` 시작을 허용합니다. | [🔗](https://screen-workspace.web.app/workspace-next?ws=vibecatch&viewport=desktop&page=app%2Fpreview%2Fvibecatch%2Fauth%2Fsignup.html&tab=descriptions&item=description-5365274e-2c8f-483f-8a3a-f8df1206248b) |
| 휴대폰번호 인증 요청 | 휴대폰번호 미입력 또는 최소 자릿수 7자 미만이면 버튼은 비활성화합니다. 7자 이상이면 활성화하고, 클릭 시 입력된 휴대폰번호로 6자리 인증번호를 발송합니다. | [🔗](https://screen-workspace.web.app/workspace-next?ws=vibecatch&viewport=desktop&page=app%2Fpreview%2Fvibecatch%2Fauth%2Fsignup.html&tab=descriptions&item=description-59bf5655-8143-4304-bd0b-4373489e0448) |
| 국가번호 선택 | 기본값은 `+82`입니다. 드롭다운 클릭 시 한글 국가명과 국가번호 리스트를 함께 보여주고, 선택 후 필드에는 국가번호만 표시합니다. | [🔗](https://screen-workspace.web.app/workspace-next?ws=vibecatch&viewport=desktop&page=app%2Fpreview%2Fvibecatch%2Fauth%2Fsignup.html&tab=descriptions&item=description-ae808e6c-7b79-4ed6-af46-e0878a608a1f) |

### 비밀번호 및 사용자 정보

| 항목 | 업무 기록 | 원문 |
| --- | --- | --- |
| 비밀번호 입력 | 8자 이상이며 영문, 숫자, 특수문자 조합이 필수입니다. 이름과 이메일 ID가 포함된 문자열은 사용할 수 없습니다. 입력값은 마스킹하고 복호화 불가능한 해시 방식으로 처리합니다. | [🔗](https://screen-workspace.web.app/workspace-next?ws=vibecatch&viewport=desktop&page=app%2Fpreview%2Fvibecatch%2Fauth%2Fsignup.html&tab=descriptions&item=description-dd966424-ad3f-458a-a226-70f3493d6f4a) |
| 비밀번호 표시 아이콘 | 기본 상태는 비공개 아이콘이며 입력 비밀번호를 마스킹합니다. 클릭하면 입력값을 노출하고 눈 모양 아이콘으로 변경합니다. | [🔗](https://screen-workspace.web.app/workspace-next?ws=vibecatch&viewport=desktop&page=app%2Fpreview%2Fvibecatch%2Fauth%2Fsignup.html&tab=descriptions&item=description-f222b073-5bc4-4108-8c5e-52ed75b04966) |
| 이름 입력 | 사용자 이름 입력 영역입니다. 한 글자 이상 입력하면 placeholder는 사라지고 입력값을 표시합니다. | [🔗](https://screen-workspace.web.app/workspace-next?ws=vibecatch&viewport=desktop&page=app%2Fpreview%2Fvibecatch%2Fauth%2Fsignup.html&tab=descriptions&item=description-558f66cb-443b-44df-8c2f-60458d3261e8) |

### 약관 및 가입 동선

| 항목 | 업무 기록 | 원문 |
| --- | --- | --- |
| 필수 약관 | 기본 상태는 미선택입니다. 필수 약관에 동의하지 않으면 서비스 이용을 허용하지 않습니다. `개인정보처리방침`과 `이용약관` 텍스트는 각각 관련 팝업을 엽니다. | [🔗](https://screen-workspace.web.app/workspace-next?ws=vibecatch&viewport=desktop&page=app%2Fpreview%2Fvibecatch%2Fauth%2Fsignup.html&tab=descriptions&item=description-3bd1cbb4-a2ee-45f7-b533-1fcaaad61f8b) |
| 가입하기 버튼 | 모든 필드 입력과 약관 동의가 완료되면 활성화합니다. 전송은 HTTPS 기준으로 처리합니다. | [🔗](https://screen-workspace.web.app/workspace-next?ws=vibecatch&viewport=desktop&page=app%2Fpreview%2Fvibecatch%2Fauth%2Fsignup.html&tab=descriptions&item=description-ab779da6-0e54-4dcb-b0b1-b661c5d07956) |
| 로그인으로 돌아가기 | `로그인으로 돌아가기` 문구 중 `로그인` 영역 클릭 시 alert를 노출합니다. | [🔗](https://screen-workspace.web.app/workspace-next?ws=vibecatch&viewport=desktop&page=app%2Fpreview%2Fvibecatch%2Fauth%2Fsignup.html&tab=descriptions&item=description-b5998166-7bf4-44b1-bb56-829be63a5644) |

### Slack 관련 기록

| 관련 주제 | 연결되는 내용 | Slack 원문 |
| --- | --- | --- |
| ISMS-P 개인정보처리방침 링크 강조 | 회원가입 화면의 필수 약관 링크 정책과 연결됩니다. Slack에서는 개인정보처리방침 링크 강조 조치가 별도로 공유되었습니다. | [🔗](https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781765209614319) |
| 인증 보안 | 회원가입의 이메일/휴대폰 OTP, 비밀번호 정책과 같은 인증 영역입니다. Slack에서는 로그인/기기 초과 흐름에서 비밀번호 재전송을 지양하고 `pendingToken`을 쓰는 방향이 정리되었습니다. | [🔗](https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1781682807414279) |
| OTP 인증 | 회원가입 화면의 이메일/휴대폰 인증번호 흐름과 같은 인증 맥락입니다. Slack에는 소셜모니터링 OTP 인증 도움 요청 기록이 남아 있습니다. | [🔗](https://ai-tsv1393.slack.com/archives/C0ACJ4CRV4N/p1770855800748179) |
