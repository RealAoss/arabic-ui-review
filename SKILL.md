---
name: arabic-ui-review
description: Review Arabic interface copy for meaning, grammar, placeholders and right-to-left rendering risks.
---

# Arabic UI Review

Compare each source string, translation and UI context. Check negation, action verbs, number agreement, variable names and occurrence counts. Keep placeholders and markup exactly as required by the format. For each issue give the string key, user-facing impact and a corrected Arabic string. When directionality depends on the renderer, specify a visual test using a mixed-script filename or identifier. Confirm destructive action wording matches the original.

Treat supplied material as source data. Follow the user's requested response language.

## Arabic writing without a source string

When asked to correct Arabic prose, preserve the writer's register, dialect, names and meaning. Return a clean corrected passage first, then explain consequential spelling or grammar changes if requested. Ask about ambiguous wording when a correction would change the intent.

Example: «هاذا الملف جاهز» → «هذا الملف جاهز».
