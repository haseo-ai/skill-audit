# oc-skill-audit

OpenClaw AgentSkill의 다차원 품질 평가.

## 설치

```bash
openclaw skills install oc-skill-audit
```

## 차별점

- **6개 평가 차원**: 구조, 트리거, Style Guide, 워크플로우, Sub-Agent 설계, 간결성
- **N/A 가중치 재분배**: 모든 차원이 필요 없는 스킬에도 공정한 평가
- **이중 언어 보고서**: 사용자 언어 + 영어로 결과 제공
- **타임스탬프 기록**: 이전 결과를 덮어쓰지 않고 재평가 가능
- **다국어 평가 기준**: EN/KO/JA/ZH

## 빠른 시작

```bash
# 특정 스킬 평가
openclaw skills install oc-skill-audit
"summarize 스킬 평가해줘"

# 여러 스킬 평가
"skills/ 폴더의 모든 스킬 평가해줘"
```

## 평가 차원

| 차원 | 가중치 | 평가 내용 |
|------|--------|-----------|
| A. 구조 | 20% | 프론트매터, 파일 레이아웃, 명명 규칙 |
| B. 트리거 | 15% | 설명 품질, 키워드 |
| C. Style Guide | 20% | 보존/압축 기준 |
| D. 워크플로우 | 15% | Phase 0, 검증, 에러 처리 |
| E. Sub-Agent 설계 | 15% | 템플릿, 컨텍스트 주입 |
| F. 간결성 | 15% | 길이, 중복, 에이전트 스마트 작성 |

## 링크

- **ClawHub**: https://clawhub.ai/haseo-ai/oc-skill-audit
- **GitHub**: https://github.com/haseo-ai/skill-audit
- **라이선스**: MIT-0
