# 딸기 정식기 광합성 ↔ 에너지 · 온톨로지 제어 (web)

OnAndOn 연구의 인터랙티브 시각화 정적 사이트 (Vercel 배포용).

- `index.html` — 랜딩
- `tools/conflict.html` — 구동기 충돌 온톨로지 맵
- `tools/layer-demo.html` — Layer 방식 의사결정 · P–I 곡선
- `tools/api-responses.html` — 실제 API 응답 비교 (거대 LLM vs Layer)
- `results.html` — 검증 결과 (정량 차트)

모든 페이지는 외부 의존성 없는 self-contained 정적 파일.

## 배포 (Vercel)
- Framework Preset: **Other** (빌드 없음, 정적)
- 이 디렉터리를 레포 루트로 두면 제로 설정으로 배포됨.

생성 원본: 경희대학교 스마트팜과학과 · AGIS Lab
