# Yomikata changelog

Every change to Yomikata, newest first. Each version lists what was added, changed, fixed or removed. Pending ideas live in `yomikata-roadmap.md`; once an idea ships, it moves here.

Versions before 1.2 weren't numbered when they were released. Their numbers (1.0 and 1.1) were assigned afterwards so the history reads in order.

## 1.12 (21 October 2026)

### Added
- **Share progress** on the Plan page opens the iPhone share sheet with your progress, ready to send by AirDrop, Messages or Notes.
- **Paste and restore** on the other device reads what you copied and restores it in one tap. The confirmation shows when the progress was saved and from which version.
- The panel shows when progress was last shared from or restored on this device.

### Changed
- The manual backup code box is still there, folded under “Copy or paste the code by hand”.

## 1.11 (20 October 2026)

### Added
- **Red dots for repeated mistakes**, in both the kana and kanji quizzes. A wrong answer still clears a character’s green dots. If you get it wrong again while it has no green dots, a red dot appears on the left of its cell, up to 5. Each correct answer then removes one red dot, and green progress only starts again once the red dots are gone.
- Characters with red dots come back first in the next quiz (up to 4 per quiz).

### Changed
- The “learned” dot for a character with 5 correct answers is now **gold**, so it stands out from the green progress dots.

## 1.10 (20 October 2026)

### Added
- **Kanji quiz** on the Kanji tab, working like the kana quiz. “Quiz me on these” quizzes whichever group is selected (a school grade, Secondary school, Name kanji, Other, or the new **All kanji** chip) or your current search results. Choose whether it asks for the **Readings** (on’yomi in katakana, kun’yomi in hiragana) or the **Meaning**.
- Each kanji needs 5 correct answers for a green dot; one wrong answer resets it to zero. Each quiz brings back the kanji closest to their dot first, adds new ones in order of how common they are, and includes one already-learned kanji as a refresher.
- Progress pips on the kanji grid, and a “learned” count for the selected group. After each answer the quiz shows the meaning, Mandarin reading and all readings, with a link to open the kanji’s card.
- “Kanji quiz” in the Today page’s quick practice from week 3.

## 1.9.2 (20 October 2026)

### Fixed
- The 🔍 Search button for selected text could be hidden behind the iPhone’s own Copy / Look Up / Translate bar. It now sits in a fixed spot at the bottom of the screen, above the home indicator, where that bar never appears.

## 1.9.1 (20 October 2026)

### Fixed
- Search results for selected text opened near the top of the screen, partly behind the status bar. They now open right under the text you selected (or above it if there isn’t room), and both look-up popups always stay clear of the status bar and the home indicator.

## 1.9 (20 October 2026)

### Added
- **Tap a word to look it up.** Tap any character in Japanese text (example sentences, the phrasebook, grammar examples, the listening quiz and My words cards) to see the dictionary words that start there, longest first. It recognises common verb and adjective endings, so tapping 食 in 食べました finds 食べる, and casual forms like 行かなきゃ and 忘れちゃった. Tap a result to open it as a card; Back returns you to where you were.
- **Select text, then search.** Select any Japanese text and a 🔍 Search button appears beneath it. It shows the matching words, plus a link to search for the text in the Words tab.

### Changed
- Tapping the Japanese text of an example sentence now looks up a word instead of playing the sentence. Tap the speaker or the English line to hear it.

## 1.8.2 (20 October 2026)

### Changed
- Core words topics now open right under the card you tap, with the other topics staying in place. Tap the card again, or Close, to fold it away. Only one topic is open at a time.

## 1.8.1 (20 October 2026)

### Fixed
- The first Core words topic, People and family, wouldn’t open.

## 1.8 (20 October 2026)

### Added
- **Core words** on the Words tab: 1,163 hand-picked everyday words in 27 topics (people and family, food, places in town, getting around, time, feelings, everyday actions, question words, greetings and more). Each topic shows how many words you’ve saved and mastered, opens as a list you can step through with ‹ and ›, and has a Save all button.
- **Pictures for words**: about 400 concrete words show an emoji (🐕 犬, 🚃 電車, 🍜 ラーメン) in word lists, search results and word cards.
- Plan week 3 task for Core words.

### Changed
- **Better search ranking.** Everyday words now come first: searching “station” finds 駅, “dog” finds 犬 and “rain” finds 雨 before rarer words or romaji look-alikes. Meanings with nested brackets are also matched properly.

## 1.7 (19 October 2026)

### Changed
- Kana progress pips now run vertically along the right edge of each chart cell, filling from the bottom up, instead of in a row underneath. The green “learned” dot sits in the same place. Cells are shorter, so less scrolling is needed to get through the chart.

## 1.6 (19 October 2026)

### Changed
- **Kana green dots are harder to earn.** A character now needs 5 correct answers (in any quizzes, not necessarily in a row) instead of 2. One wrong answer still resets it to zero, so a character you’ve forgotten loses its dot and has to be relearned.
- Each quiz brings back the characters closest to their dot first (up to 7), adds a few new ones, and includes one already-learned character as a refresher.

### Added
- Small progress pips under each kana on the chart showing how many of the 5 correct answers it has so far.

## 1.5 (18 October 2026)

### Fixed
- **Kana quiz green dots.** The quiz always picked the characters you’d answered least, so a character you got right once didn’t come back until every other character had been asked, which took about eight quizzes before any dot appeared. Each quiz now brings back up to five characters you’ve got right once, so they can earn their dot in the next round.

### Changed
- The “learned” count next to the quiz now includes the ゛ and ゜ characters, matching the dots on the chart (for example, “5 of 71 learned”).

## 1.4 (18 October 2026)

### Added
- **Gestures on kanji and word cards.** Swipe down to close (the card follows your finger and springs back if you don’t go far enough; only starts when the card is scrolled to the top). Swipe right to go back to the previous card, or close if there’s nothing to go back to. A grab bar at the top of the card shows it can be dragged.
- **‹ and › on kanji cards** to step through the kanji in the grid you came from, with a position counter.
- **‹ and › on word cards** opened from a list, to step through that list (for example, all にち words, or your search results).
- **Words grouped by reading** on every kanji card: chips for each reading (katakana for on’yomi), Special readings (like 明日, あした) and Dates and numbers, with counts. Each group shows its 5 most common words, with Show all. Lists now draw on every common word using the kanji, not just the top 15.
- **Mini header** that pins to the top of a card once you scroll: the kanji or word (tap to return to the top) and jump links such as Card, Words, Meaning, Examples and Kanji.

### Changed
- Example sentences for single-kanji words prefer sentences where the kanji is the word itself. Sentences where it’s part of a longer word (本日, 明日) appear separately under “Other words using 日”.
- The card covers a little less of the screen, so the dimmed area above it is easier to tap to close.

## 1.3 (18 October 2026)

### Changed
- “Chinese traps” and “English traps” are now **Chinese faux amis** and **English faux amis**, the linguistic term (French for “false friends”). Word tags, warning boxes, Practice sections, quiz buttons, Plan tasks and the Today page all use the new names.
- The Chinese faux amis section explains the term the first time it appears.

## 1.2 (18 October 2026)

Yomikata becomes the only app. It takes every feature first released in the separate Yomikata 2 app (versions 2.0 to 2.2, listed below) and keeps its own progress. Yomikata 2 is retired.

### Added
- **Kana card navigation.** ‹ and › buttons and left or right swipes move through all 104 kana in chart order, with a position counter. Tapping a chart cell scrolls the card into view.
- **Combined sounds** (きゃ, シュ and so on) get a play button, stroke order for both characters, and an example word where a common one exists.

### Removed
- The “Copy my progress from version 1” panel, no longer needed with a single app.

### First released in Yomikata 2, now part of 1.2

**From 2.0**
- **Animated stroke order** for all 3,100 kanji and every kana, from KanjiVG. Plays automatically on kanji and kana cards, with Play, Next stroke and Slow controls.
- **Sliding verb endings.** A “Watch it change” panel on every verb cycles through its forms with the changing ending in red. U-verbs show a row of tiles (か き く け こ) with the sound in use lit up. The verb tables mark the changing part in red, and the Practice tab demonstrates it with 書く.
- **Colour-coded sentences** in grammar examples, the phrasebook, the self-introduction and the order builder: topic, subject, object, where/when, with/and, and verb, with particles highlighted. A legend and on/off switch sit on the Grammar and Phrases tabs. Limited to hand-checked sentences.
- **Study calendar**: an 18-week heatmap of study days on the Today page.
- **Kanji map**: the 240 Grade 1 and 2 kanji shaded from “not yet” to “mastered” on the Today page, with the same shading on the Kanji tab grid.
- **+ Save on kanji cards**, so kanji can be reviewed in My words.
- **Version number** shown next to the title and in the footer.

**From 2.1**
- Fixed audio being cut off: a silent warm-up on first touch, a short pause before each sound, and an ending added to every phrase.
- Single kana play slowly.
- “In a word” example for every kana (か, then かさ), with hand-picked words.
- The best installed Japanese voice (Enhanced or Premium) is chosen automatically.

**From 2.1.1 to 2.1.3**
- Single kana play once instead of twice.
- Removed the voice picker; only a Sound speed slider remains, in a panel on the Kana tab.
- Removed the note “Only the kanji’s sound was kept…” from the kana card.

## 1.1 (18 October 2026)

A long series of updates after the first release, in the order they were made.

### Added
- **How Japanese works** on the Start tab: word order, which script to use, and why one kanji has several readings.
- **Practice tab** with 48 Chinese false friends (list and quiz) and verb forms (explanation and drill).
- **Chinese forms** (simplified and traditional) on every kanji card, and searching with Chinese characters (气 finds 気).
- **Verb and adjective tables** (“How it changes”) on every verb and adjective.
- **Phrases tab** with shortcut buttons to Google Translate, DeepL and Jisho, and 26,000 Tatoeba example sentences searchable offline.
- **Example sentences** in word details.
- **Borrowed words** section on the Start tab, and 24 English false friends (list and quiz) with tags in the Words tab.
- **Home-screen app** (installable from GitHub Pages, works offline).
- **8-week Plan page** with weekly checklists, a daily routine, and links to outside resources where the app doesn’t cover something.
- **Grammar tab**: 34 beginner patterns with Chinese comparisons, types of rules, week filters and “I’ve learned this” ticks, linked from the Plan.
- **Kana origins**: tap a kana to see the kanji it came from; “Show kanji origins” on the whole chart.
- **Keigo cards**: polite, respectful and humble お and ご.
- **Numbers tab**: numbers and a converter (with 円), 12 counters, time, days of the week, months and dates, and a numbers quiz.
- **Phrasebook**: about 75 phrases in 9 situations, “You’ll hear” phrases with replies, an order builder, and a self-introduction builder with automatic katakana names.
- **My words**: save words, phrases, sentences and kanji, and review them with spaced repetition. Practice tab badge for due cards.
- **Backup codes** on the Plan page to save and restore progress.
- **Listening quiz** with three levels from the example sentences.
- **Casual speech**: 12 patterns showing how friends actually talk.
- **The rest of the beginner grammar**: 21 more patterns, 69 in total.
- **Today page**: date in Japanese, streak, words due, the next plan tasks and quick practice. Opens on the first launch of each day.
- **Daily reminder** at 10 p.m. in the Reminders app (set up outside the app).

### Changed
- Numbers tab moved after the Words tab.
- Search bars on the Kanji, Words and Phrases tabs stay pinned at the top.
- Kanji tab: the grade chips and grid sit right under the search; kanji cards open as a sheet with Back navigation between kanji and words.
- Grammar progress tied to pattern names instead of list positions, so new cards can’t shift your ticks. Existing ticks were migrated.

### Fixed
- Each tab remembers its scroll position instead of jumping to the top.
- Romaji search for words like “konnichiwa”.
- Quiz options that showed impossible spellings.

## 1.0 (18 October 2026)

### Added
- **Start**, **Kana**, **Kanji** and **Words** tabs.
- Hiragana and katakana charts with sounds and a quiz.
- Kanji cards in the style of the reference spreadsheet: English meaning, Mandarin pinyin, on’yomi, kun’yomi, name readings and words using the kanji; browsing by school grade.
- A dictionary of 22,000 common words searchable in English, romaji, kana or kanji, with readings, meanings and audio.
- Data from JMdict and KANJIDIC2 (Electronic Dictionary Research and Development Group, CC BY-SA 4.0).
