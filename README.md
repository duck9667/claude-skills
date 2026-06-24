# claude-skills

Personal [Claude Code](https://claude.ai/code) skills for reuse across environments.

## Skills

### `management-mental-models`
의사결정·매니지먼트·조직 관련 대화에서 멘탈모델 렌즈를 적용하는 스킬.
달리오·메도즈·그로브 원문 기반. 스톡/플로우, 피드백 루프, 레버리지, one-way/two-way door, 심리적 안전감, 옵션성, pre-mortem 등의 프레임워크 포함.

### `ab-test`
A/B 테스트 설계·분석·의사결정을 위한 종합 가이드.
샘플 사이즈 계산, 통계적 유의성 검정, 베이지안 분석, SRM 검사, Ship/No-Ship 판단 프레임워크 포함.

## 설치

다른 환경에서 사용하려면 `~/.claude/skills/`에 클론:

```bash
git clone https://github.com/duck9667/claude-skills.git ~/.claude/skills/claude-skills
# 또는 개별 스킬만
cp -r claude-skills/management-mental-models ~/.claude/skills/
```

## 구조

```
claude-skills/
├── management-mental-models/
│   ├── SKILL.md
│   └── references/
│       ├── better-mental-models-2026.md
│       ├── high-output-management.md
│       ├── management-synthesis.md
│       ├── ray-dalio-principles.md
│       └── thinking-in-systems.md
└── ab-test/
    ├── SKILL.md
    └── references/
        ├── PITFALLS_AND_CHECKS.md
        └── STATISTICAL_FRAMEWORKS.md
```
