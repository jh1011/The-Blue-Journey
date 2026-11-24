## Featured project — The Blue Journey

치어에서 번식까지의 생애주기와 생존 전략을 직접 조작하는 2D 해양 생태 교육 게임입니다.

### My role

- 2인 팀 Project Lead, 기여도 약 90%
- 게임 기획, 시스템 설계, Phaser/TypeScript 개발
- UI/UX, 사운드, 조작감 개선, 통합 QA
- 팀원은 플레이테스트와 오류·완성도 검수를 담당

### Why these systems exist

| 플레이에서 발견한 문제 | 판단과 구현 |
| --- | --- |
| 실패 위험이 없어 긴장감이 약함 | LIFE, 피격·회복·실패 조건 추가 |
| 반복 구간이 같은 패턴으로 흐름 | 경고 후 5초간 추격하는 포식자 이벤트 추가 |
| 엔딩 후 다시 플레이할 이유가 없음 | 4종 어류·8개 개체군 선택과 관찰 도감 저장 연결 |
| 빠른 장애물로 위험을 읽기 어려움 | 속도·충돌 범위 조정, 경고·색·사운드 피드백 분리 |

즉시 보상은 FLOW와 먹이 콤보, 한 판의 긴장은 LIFE와 포식자, 재도전 동기는 개체군 도감으로 설계했습니다.

### Tech

`Phaser 4.2.1` · `TypeScript 6` · `Vite` · frame-independent movement · `localStorage`

## Local preview

저장소 루트에서 정적 웹 서버를 실행한 뒤 `index.html`을 엽니다. 플레이 가능한 빌드는 `game/`에 포함되어 있습니다.
