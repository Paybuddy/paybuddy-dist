# PayBuddy Data Distribution

PayBuddy 앱이 내려받는 데이터 배포용 저장소입니다.

## 파일

여덟 개 모두 저장소 **맨 위**에 있어야 합니다. 폴더 안에 들어가면 앱이 못 찾습니다.

| 파일 | 내용 |
|---|---|
| `card_products.pbd` | 카드 상품 목록 |
| `benefit_rules.pbd` | 카드 혜택 규칙 |
| `benefit_limit_groups.pbd` | 실적 구간별 통합 한도 |
| `card_excluded_clauses.pbd` | 카드 실적 제외 조항 |
| `merchants.pbd` | 가맹점 사전 |
| `sms_patterns.pbd` | 결제 문자 파싱 패턴 |
| `reference_prices.pbd` | 기준 단가 (유가·마일 가치) |
| `release_notes.pbd` | 앱 업데이트 소식 |

`.pbd`는 PayBuddy 앱 전용 형식이며, 앱 외부에서 사용할 수 없습니다.

## 갱신

앱의 **설정 → 데이터 업데이트**에서 최신 파일을 받아 갑니다.
파일명은 고정이며, 내용만 갱신됩니다.

같은 이름으로 다시 올리면 그대로 덮어쓰면 됩니다. 앱은 파일이 바뀐 것을
알아채고 필요한 것만 내려받습니다.

## 이용 조건

이 저장소의 데이터는 PayBuddy 앱 안에서 쓰기 위한 것입니다.
복제·재배포·상업적 이용을 금지합니다.

문의: paybuddy.help@gmail.com
