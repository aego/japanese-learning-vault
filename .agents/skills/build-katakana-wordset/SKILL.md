---
name: build-katakana-wordset
description: Create fresh sets of useful modern Japanese katakana words, validate exact spellings and natural real-world usage on current Japanese websites, avoid vocabulary already present in earlier sets or completed Minna no Nihongo lessons, maximize kana variety, and optionally update the user's Obsidian katakana dictionary. Use when the user asks for more katakana words, a new katakana vocabulary set, modern loanwords used in Japan, katakana practice, or an update to the katakana word list.
---

# Build Katakana Wordset

## Workflow

1. Follow the active vault's `AGENTS.md` reading order. In the Japanese-learning vault, read the main page, progress page, current lesson, and `20 Справочники/Катакана — словарь.md`.
2. Determine the requested size; default to 20 words.
3. Exclude:
   - every word already present in the katakana dictionary;
   - katakana vocabulary from the current and completed Minna no Nihongo lessons;
   - proper names, fictional companies, and Latin-only forms unless requested;
   - awkward fragments that Japanese normally use only as part of a longer compound.
4. Choose words from mixed practical domains such as food, shopping, travel, services, objects, work, leisure, and everyday conversation. Do not organize adjacent words by semantic category; shuffle the final order.
5. Favor contemporary, common, useful forms and maximize variety of katakana signs, including small kana, `ッ`, dakuten/handakuten, and `ー`, without sacrificing naturalness.
6. Browse current Japanese sources before presenting a set:
   - confirm exact spelling on authoritative Japanese sites where possible;
   - confirm ordinary internet usage in Japanese user-written text;
   - distinguish an attested word from a genuinely natural standalone form;
   - replace weak or overly technical candidates.
7. Present a compact Markdown table with:
   - number;
   - katakana word;
   - Russian meaning;
   - short natural Japanese example;
   - Russian translation.
8. Write Japanese examples entirely in kana unless the user asks for kanji. Keep the target word in katakana.
9. Briefly state the validation basis and cite representative sources. Do not bury the list in research commentary.

## Vault updates

- Update `20 Справочники/Катакана — словарь.md` only when the user asks to save or add the set.
- Preserve existing entries and links.
- Add the new set as a dated section or merge it without duplicates, according to the note's current structure.
- Do not mark words as mastered merely because they were added.
- Do not update progress or the error journal unless a genuinely new stable learning fact appeared.

## Quality checks

Before finishing, verify:

- the requested number of unique words is present;
- no word duplicates the dictionary or excluded lessons;
- every example contains no kanji;
- spellings preserve long vowels and small kana;
- category order is mixed;
- cited pages actually contain the claimed forms;
- any requested Obsidian edit is linked and readable.
