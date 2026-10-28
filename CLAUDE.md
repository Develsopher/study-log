# study-log — rules for writing TIL entries

Triggered when the user asks "TIL 올려줘" (or similar) after a study session.

1. Draft from the session's discussion using `_template.md`. Place at `<category>/<keyword>.md` (Korean) + `<category>/<keyword>.en.md` (English, `lang: en`, same structure).
2. Categories (flat, top-level only): javascript, typescript, react, nextjs, browser, performance, architecture, testing, debugging, network, cs, devops. Create the folder only when its first entry is written. No portfolio content.
3. Filename: English kebab-case keyword. One keyword = one file; if it exists, extend it and bump `updated`.
4. Leave "면접 질문 > 내 답변" and "내 말로 정리" for the user to fill in their own words — show the draft and ask for those before committing. Do not commit text the user hasn't reviewed.
5. Add a link under the matching category in README.md (Korean file only).
6. Commit message: `til(<category>): <keyword>`.
