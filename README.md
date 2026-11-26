# plain-language

한국어 문서를 쉬운 말로, 읽는 사람이 이미 쓰는 용어 그대로 쓰게 하는 Claude Code 스킬.
[ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)에서 착안.

- 빼도 뜻이 같은 문장은 뺌
- 대화·문서·코드에 이미 있는 용어를 다른 말로 바꾸지 않음
- 넘기기 전 용어를 하나씩 찾아보고, 없는 말은 "새로 쓴 말"로 따로 보고

## 설치

Claude Code에 이 저장소 링크를 주고 "이 스킬 설치해줘"라고 하면 됨.

### For agents

Run:

```sh
mkdir -p ~/.claude/skills/plain-language
curl -fsSL https://raw.githubusercontent.com/kimwoo-ya/skill_i-have-adhd/main/plain-language/SKILL.md \
  -o ~/.claude/skills/plain-language/SKILL.md
```

If `/plain-language` does not show up, tell the user to start a new Claude Code session.
