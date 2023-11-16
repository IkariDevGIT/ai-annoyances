# ai-annoyances

Idea by https://github.com/AlpinDale/gptslop

# Contributing
Capitalization doesn't matter!
* means anythign can be between it.

The format should be like this:
```json
{
  "shiver down * spine": {
    "importance": "high",
    "type": "annoyance",
    "alternatives": [
      "quiver through *'s body"
    ]
  },
...
}
```

alternatives is optional!

importance: high, medium, low
types: annoyance(things like "shiver down * spine", or "just above a whisper"), rp-annoyance(words/sentences like "member", "shaft" or stuff like that that can destroy rp experience), refusal(pretty obvious what this means, something like "im sorry, but", or "as an AI" and so on)

if [word1/word2/word3/...] is placed somewhere in the entry, it means it can be one of those words

empty template:

```json
"": {
        "importance": "high",
        "type": "annoyance",
        "alternatives": [
          "null"
        ]
    },
```
