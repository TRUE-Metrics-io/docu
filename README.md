# truemetrics Docs

Source of https://docu.truemetrics.cloud/, built with [Mintlify](https://mintlify.com/) from the
`main` branch. The navigation and redirects are in `docs.json`.

## Style

- The product is **truemetrics**, always lowercase, also at the start of a sentence.
- Plain English, second person ("your app"), no jokes or filler.
- One definition per term: use the words in [glossary.mdx](glossary.mdx) and link it on first use.
- Code samples compile as shown: imports, the coroutine scope, and the current SDK API. Kotlin
  first, Java where the API differs.
- Times in examples are ISO 8601 with an offset or `Z`. Example addresses and coordinates match
  each other.
- Support address: info@truemetrics.io.
- Facts about the SDK or backend come from the code of the released version, not from memory.
