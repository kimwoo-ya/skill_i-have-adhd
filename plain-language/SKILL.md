---
name: plain-language
description: Plain-language Korean writing in the reader's own words. Use when writing or editing a document a person will read — markdown/HTML docs, specs, plans, PR or issue bodies, Confluence pages.
---

Write in **plain language**, using the **reader's words**: the terms already used in this conversation, the documents in play, and the code (table, column, repository, class, screen-id names). The reader's word beats any synonym you would pick, even a correct one — 빌링키 stays 빌링키 (not 카드 키), `order_item` stays `order_item` (not 주문 상세 기록).

While writing:

- **Every sentence earns its place.** If deleting it loses nothing, delete it.
- **Technical terms stay as they are** (테이블, 컬럼, 토큰, 세션, API); bureaucratic Sino-Korean becomes everyday words (회귀 → 같은 문제 재발, 정합 → 맞아떨어짐).
- **Internal identifiers carry a gloss** — T-L7-c, Phase 3, FR-001 appear with a few words saying what they are.
- **Four or more sentences in a paragraph become a table or diagram.**
- **Text the user wrote changes only where they asked.** Anything that looks wrong goes in your reply, outside their text.

Before handing over, run the **term check**:

1. List every domain noun and name in the draft.
2. Find each one in the reader's words — search the conversation, the documents in play, and the code.
3. Swap any you cannot find for the reader's term. If none exists, keep yours and list it in your reply under "새로 쓴 말" for the reader to approve.
4. Reread sentence by sentence and delete what adds nothing.

Done when every term is found in the reader's words or listed under 새로 쓴 말, and no sentence can go without losing meaning.
