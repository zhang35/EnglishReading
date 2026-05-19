# Task

Everyday I'll read 1 or 2 English articles for learning purpose.

There will be 1 or 2 new audio recordings and images in `new/`.

The goal is to process them to be prepared for a blog post in 微信公众号.

## Steps

1. Get titles from images
2. Rename each image and audio recording pair with the title
3. Move all renamed files from `new/` to `archive/`
4. Summarize the content from the image(s), create learning notes for Chinese English learners with IELTS score of 6.5, and save to one plain-text document in `learning_notes/` (filename: `YYYY-MM-DD 学习笔记.txt`)

## Learning notes format

Plain text only — no Markdown (`#`, `**`, `---`, etc.), so content can be copied into 微信公众号 as-is.

Layout should be compact: minimal blank lines, no section dividers like `---`, no prefixes like `【文章一】`.

If there are 2 articles, separate them with one blank line.
If there is only 1 article, output that article only (do not add empty placeholders).

For each article:

```
🕶️ English Title
👓 Chinese Subtitle (from the app; pick a fun, topic-matching emoji for each line)

✨ 概述
(narrative summary in Chinese; use bullet points when the article is list-based — e.g. “7 foods”, “6 ways”, tips roundups)
• item 1：brief point in Chinese
• item 2：...
(optional one-line intro before bullets and/or one-line takeaway after)

💎 词汇
word /AmE IPA/ pos. Chinese definition
...

🎤 地道表达
phrase — Chinese meaning
例：English example.（Chinese translation.）

(next expression group, preceded by a blank line)
...
```

Emoji guide — use vivid, topic-relevant emojis (not generic placeholders every time):

| Emoji | Section | Notes |
|-------|---------|-------|
| (topic) | 英文标题 | Match the article, e.g. 🕶️ tech, ☕ life, 🐕 animals |
| (topic) | 中文副标题 | Complement the English line, e.g. 👓 🧊 🌿 |
| ✨ | 概述 | |
| 💎 | 词汇 | |
| 🎤 | 地道表达 | |

Section labels use emoji, not numbered headings (no `3.1`, `3.2`, etc.).

Vocabulary entries: `word /phonetic/ pos. 中文释义` — American English IPA in slashes after the headword. No blank lines between vocabulary items.

Overview: default to a short paragraph. If the article enumerates items (numbered list, “X ways/foods/tips”), write the 概述 as `•` bullet points — one line per item, compact Chinese, no blank lines between bullets unless clarity needs it.

Idiomatic expressions: each group is two lines (phrase + meaning, then `例：...（...）`), followed by one blank line before the next group.
