---
name: plain-language
description: Plain-language Korean writing in the reader's own words. Use when writing or editing documents such as Markdown or HTML docs, specs, plans, PR or issue bodies, and Confluence pages.
---

Write Korean documents in plain language within the user's requested scope and format. When the user asks for exactly one line or only the document body, return only that text. Keep unknown labels as written and omit added notes, questions, and placeholders.

## Writing or broadly revising

- Start the first sentence with the conclusion, actual outcome, or action the reader needs. Put background and caveats after that statement. Keep material conditions, exceptions, numbers, and what has been verified or is still uncertain.
- Tie causes, conditions, and deadline start points to what the source establishes. Leave unsupported reasons or details out of reader-facing copy. If the reader needs an inference, label it as an inference.
- Use paragraphs for connected explanations, numbered lists for steps in order, and tables for comparisons. Cut words that add no meaning.

## Editing a specific part

- Change only what the user requested. Preserve the surrounding wording and structure.
- Flag material factual errors or problems that could affect execution separately from the edited text. Mention out-of-scope spelling or wording only on request.

## Terms and identifiers

- Use everyday words for bureaucratic jargon. Keep the technical and domain terms the reader and source use, such as 회귀 테스트, 테이블, 컬럼, 행, and 빌링키. Copy code identifiers exactly.
- For newcomers, explain what the original term or identifier means or does in the supplied context, right after its first use. For example, if the source defines a retry flag, write “`retry_enabled` 컬럼은 재시도할지를 나타냅니다.”
- Limit terminology checks to meaning-sensitive domain terms and identifiers in the conversation, documents, and code provided for the request. Mention a new term only if the reader or team actually needs to decide what to call it.
- For any audience, explain unfamiliar project labels such as decision, ticket, phase, and section IDs at first mention, including in a title, unless the surrounding document already defines them. If the provided material gives no definition, keep the label as written. When the requested format allows a note, flag the missing definition or ask for it separately.
