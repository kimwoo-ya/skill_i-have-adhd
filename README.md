# plain-language

한국어 문서를 쉬운 말로, 읽는 사람이 이미 쓰는 용어 그대로 쓰게 하는 Claude Code 스킬.
[ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd)에서 착안.

- 새 글이나 전체를 고치는 글은 결론이나 독자가 할 일을 먼저 씁니다. 중요한 조건을 남기고, 확인된 사실과 아직 모르는 점을 구분합니다.
- 일부만 고쳐 달라고 하면 요청한 부분만 고칩니다.
- 기존 기술 용어와 코드 이름을 그대로 씁니다. 새로 배우는 독자에게는 용어가 무엇을 가리키는지 설명하고, 낯선 티켓 번호나 단계 이름은 처음 나올 때 풀이합니다.

## 사용 예

Claude Code가 한국어 문서를 작성하거나 고칠 때 이 스킬을 적용할 수 있습니다. 직접 부르려면 `/plain-language`와 요청을 함께 입력하세요.

```text
/plain-language 아래 안내문의 첫 문장만 쉽게 고쳐 주세요.
```

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
