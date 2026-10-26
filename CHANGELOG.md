# Yomikata changelog

Every change to Yomikata, newest first. Each version lists what was added, changed, fixed or removed. Pending ideas live in `yomikata-roadmap.md`; once an idea ships, it moves here.

Versions before 1.2 weren't numbered when they were released. Their numbers (1.0 and 1.1) were assigned afterwards so the history reads in order.

## 1.30.2 (26 October 2026)

### Removed
- The experimental “play with the silent switch on” setting and its code. On iPhone, web apps can’t play speech in silent mode. Sound speed now explains this and suggests turning the ringer on or using headphones.

## 1.30.1 (26 October 2026)

### Fixed
- Sound stopped working after 1.29. The experimental “play with the silent switch on” setting is now off by default, which restores the sound as it was before. You can still try it in Sound speed on the Kana tab.

## 1.30 (26 October 2026)

### Added
- **Verb pairs (自動詞 and 他動詞)** in the Grammar tab: a panel explaining in plain words that many actions have two verbs, one for something that happens by itself (with が) and one for someone doing it (with を), with why it matters (choosing が or を, and sounding less blaming) and the sound patterns that help (-aru and -eru, -eru and -su, -iru and -osu).
- **16 common pairs** (開く and 開ける, 閉まる and 閉める, 始まる and 始める, つく and つける, 消える and 消す, 壊れる and 壊す, 割れる and 割る, 起きる and 起こす and more), each side colour-coded, with audio and linked English.
- **Verb pairs quiz:** see an English sentence and pick the right particle and verb from four combinations, with the same progress dots as the other quizzes.
- A Grammar card for week 6, a “Verb pair” entry in Words used in grammar, a week 6 Plan task, and a Today suggestion from week 6.

## 1.29 (26 October 2026)

### Added
- **Sound with the silent switch on (experimental).** Yomikata now asks Safari to treat its sound as media playback, like a music app, and keeps a silent clip playing while it speaks, which on many iPhones lets speech through even when the ringer is off. You can turn this off in Sound speed on the Kana tab. While Yomikata speaks, it may pause music or podcasts, and it may not work on every iPhone or iOS version.

## 1.28 (25 October 2026)

### Added
- **Linked Japanese and English** in the Particle map: every example’s English translation is underlined in the same colours as the Japanese chunks, so you can see which Japanese part means which English words, even though the word order is different. A faded (私は) or (I) marks a subject Japanese leaves out.
- **Particle quiz** in the Particle map: 10 sentences with a gap, choose the right particle from four. Wrong answers that would also be grammatical are never offered. After each answer the sentence is shown fully colour-coded with its English and the use it illustrates. Each particle tile shows its progress with the same green, gold and red dots as the other quizzes, and particles you get wrong come back first.
- **Plan, week 4:** a task to explore を, に and で in the Particle map and take the Particle quiz. **Today** suggests the Particle quiz from week 4.

### Changed
- Example sentences with の, か and が meaning “but” are coloured by hand so they show the right job.

## 1.27 (25 October 2026)

### Changed
- **One colour scheme for particle jobs, used everywhere:** blue for topic (は), red for subject (が), coral for object (を), green for time and target (に, へ), amber for where and how (で), teal for from and until (から, まで), pink for “and” and “with” (と, や), purple for also (も, and の in the map) and gray for the verb or ending. The Particle map, the colour-coded sentences in Grammar and Phrases, and Words used in grammar now all use these same colours, and the legends list all nine.
- **Words used in grammar is now colour-coded:** every example sentence is coloured like the rest of the Grammar tab, the hidden subject example shows the missing (私は) faded, and verb endings, stems and the copula are marked in the verb colour.
- **Particle map examples are colour-coded** too.
- Colour coding now recognises や, double particles (には, にも, では), and particles after quotes (「はい」と).
- The Start page notes that its colours show the three scripts, while Grammar and Phrases use colours for jobs.

## 1.26 (25 October 2026)

### Added
- **Particle map** in the Grammar tab: all 13 common particles plus double particles on one screen, each tile coloured by the job it does (topic, subject, object, a point or direction, where or how, from or until, lists, of or also, questions). Tap a tile to see every use with a spoken example, romaji and meaning, a Chinese comparison, and a link that jumps to its lesson card.
- **Uses that were missing before:** に for where something is, who receives or gives, purpose and passive; で for language, cause and totals; と for quoting words and thoughts; の for turning a verb into a noun and softening a question; が meaning “but”; も with question words (何も); か meaning “some-” (何か); and double particles (には, にも, では, とは, でも).

## 1.25 (25 October 2026)

### Added
- **Words used in grammar** at the top of the Grammar tab: 15 terms explained in plain words, each with a tappable example, its romaji and meaning, and the key part highlighted. It covers particle, chunk, topic (は), subject (が), object (を), verb, noun, い and な adjectives, copula (です and だ), hidden subject, double particle, polite and plain form, conjugation, stem and て form. Where it helps, it compares with Chinese. The card opens by itself the first time you visit the Grammar tab, then stays folded.
- The Particles type description points to the new card.

## 1.24 (24 October 2026)

### Added
- **Beyond the app: real Japanese** on the Plan page, with six foldaway groups of links and tips:
  - **Natural listening:** Nihongo con Teppei for Beginners, Nihongo no Jikan, Natural Input Japanese (formerly Comprehensible Japanese) and NHK World’s Easy Japanese.
  - **Regular speaking practice:** italki, Preply, HelloTalk and Tandem.
  - **Casual Japanese:** a link to the casual speech cards and Language Reactor for watching with Japanese subtitles.
  - **Keep it in Japanese:** four phrases to keep a conversation in Japanese, with audio.
  - **Reading:** Tadoku free graded readers, NHK News Web Easy and Satori Reader.
  - **Writing:** LangCorrect.
- Small talk in the phrasebook now has 日本語で話してもいいですか and 日本語を練習しています.

### Changed
- The Plan page’s “Where to go for what the app doesn’t teach” points to the new section for listening and speaking.

## 1.23 (24 October 2026)

### Changed
- **The Start page is rewritten to be shorter and example-led,** in five numbered sections with jump links at the top: The three scripts, Which script?, Kanji readings, Borrowed words, and a new Quick reference on sounds. Every example now shows its kana and romaji, and you can tap any of them to hear it.
- **The three scripts** breaks the example sentence into its six parts, showing each part’s script and job (including that は is said wa).
- **Which script?** now says hiragana is a fallback while learning, not always correct, and that you should learn each word’s normal spelling.
- **Kanji readings** adds 水曜日, 来年, 今年 (as an exception to the rule), the same-sounding はし trio (橋, 箸 and 端) and a study tip: learn whole words, not every reading on its own.
- **Borrowed words** adds a Japanese and Chinese comparison (including 咖啡, where both borrowed the sound), work words with romaji, and クレーム in the false-friends warning.
- **Quick reference: sounds** covers the long-vowel mark ー, ō and ū in romaji, small ゃ, ゅ and ょ, small っ, and は and へ as particles.
- **Your path** is shorter and points to the newer features (the Challenge test, the Top 100 kanji, Most common words). “Which part of the app should I use?” now folds away at the bottom.

## 1.22.1 (23 October 2026)

### Fixed
- The Practice tab showed a red “0” badge when no reviews were due. It now disappears when there’s nothing to review.

## 1.22 (23 October 2026)

### Added
- **Learn more phrases elsewhere** in the Phrases tab’s phrasebook: links to Irodori (textbooks and online course), NHK World’s Easy Japanese, Erin’s Challenge!, JF Japanese e-Learning Minato, Tofugu and Learn Japanese Pod, each with a short description, plus a shortcut to add what you find to My words.
- Irodori added to the Plan page’s list of outside resources.

## 1.21 (23 October 2026)

### Changed
- **Plan, week 1:** the greetings task now names the basic apologies (すみません and ごめんなさい) and explains that すみません covers sorry, excuse me and thanks.
- **Plan, week 4:** the apologies task is now about the formal levels (申し訳ございません, ご迷惑をおかけしました), building on that week’s ます forms, and a new task covers What staff say, alongside the restaurant and café phrases.

## 1.20 (23 October 2026)

### Added
- **Add your own word or phrase** in My words: type the Japanese, an optional kana reading, the meaning and where you found it, and it becomes a review card with audio, marked “Your own”. If the word is in the dictionary, the app suggests its reading and meaning. The source you type is kept for the next card, so you can add several from the same podcast quickly.

### Changed
- **Start:** “Which part should I use?” now covers apologies and other set phrases, Most common words, Core words by topic, the kanji used most in daily life, and adding your own phrases. It also has a tip about tapping words to look them up. The hiragana step mentions gold dots and the Challenge test.
- **Plan:** new tasks for the Challenge test, reading real hiragana and katakana words, set phrases (week 2); the kanji quiz and common kanji words (week 3); apologies (week 4); replies, reactions and phone phrases (week 7); occasions and adding your own phrases (week 8). The week 1 goal now refers to gold dots.
- **Today:** quick practice now suggests the kana Challenge test and the hiragana words quiz in weeks 2–4, and the common words quiz from week 5.

### Fixed
- Two pairs of plan tasks shared the same ID, so ticking one also ticked the other (the week 3 Core words task, and the week 8 casual speech task). Each now has its own ID.

## 1.19 (23 October 2026)

### Added
- **Apologies** in the phrasebook: 17 phrases from casual to most formal (ごめん, ごめんね, ごめんなさい, すみません and its spoken form すいません, 失礼しました, 申し訳ありません, 申し訳ございません, 大変申し訳ございません, ご迷惑をおかけしました), what you’ll see and hear from staff and on signs (ご迷惑をおかけしております, お詫び申し上げます, 満席です, 満室です) and the replies (大丈夫ですよ, 気にしないでください).
- **Occasions and seasons**: New Year greetings, 良いお年を, birthdays, weddings, お久しぶりです, お世話になりました, 乾杯 and condolences.
- **What staff say**: かしこまりました, 少々お待ちください, お待たせいたしました, ordering questions, totals and change (〜円になります, 〜円お預かりします), and goodbyes.
- **On the phone**: もしもし, how businesses answer, asking for someone, being called back, a bad line, and ending a call politely.
- **Replies and reactions**: そうですね, なるほど, 本当ですか, 分かりました, 承知しました, and polite refusals (ちょっと…, 結構です).
- Greetings now include casual goodbyes (またね, また明日) and replies to thanks (いえいえ, どういたしまして).

### Changed
- The café phrase 店内でお召し上がりですか now notes that it’s technically double-polite, though universal.

## 1.18 (22 October 2026)

### Added
- **Set phrases** (決まり文句) in the phrasebook, right after Greetings: 21 fixed expressions with their usual replies, such as 行ってきます and 行ってらっしゃい, ただいま and おかえりなさい, お邪魔します, お先に失礼します and お疲れ様でした, よろしくお願いします and こちらこそ, お世話になっております, お大事に and おめでとうございます. Replies are tagged “You’ll hear”.

## 1.17 (22 October 2026)

### Changed
- **The Words tab is split into three views** with a switch pinned under the search box: **Dictionary** (search only), **Most common** (the ranked word lists) and **By topic** (Core words). Typing in the search box always switches to Dictionary. Each view remembers how far down you’d scrolled, and the app remembers which view you used last.
- The Plan’s “Open Core words” link opens the By topic view directly.

## 1.16 (22 October 2026)

### Added
- **Most common words** on the Words tab, above Core words: four ranked lists built by splitting the 26,000 example sentences into words and counting them.
  - **Kanji**, **Hiragana** and **Katakana** words, each in groups of Top 50, 51–150 and 151–300.
  - **Grammar**: the 60 most common particles and grammar endings (は, を, に, です, という…), kept apart so they don’t crowd the other lists.
- A **Read it quiz** for each group (see the word, pick its meaning), with the same rules as the other quizzes: 5 correct answers to learn a word, red dots for repeated mistakes, and in-progress words brought back first.
- **Save all** for each group, and a learned count. Lists fold away under “Show the words” to keep the page short.

## 1.15 (22 October 2026)

### Changed
- **The “Most used in daily life” ranking now covers more kinds of Japanese, with modern sources counted most.** It blends five sources by weight: everyday speech from film and TV subtitles (45%), modern news from Wikinews (25%), newspaper counts from KANJIDIC2 (15%), Japanese Wikipedia (10%) and older books from Aozora Bunko, mostly pre-1950 (5%). Song lyrics aren’t included because there’s no open source for them.
- Kanji like 駅, 曜 and 電 moved up; old character forms like 國 and 來 stay near the bottom.

## 1.14 (21 October 2026)

### Added
- **Most used in daily life**: a second row of kanji groups that ignores school grades and ranks kanji by how often they actually appear, combining newspaper frequency (KANJIDIC2) with everyday spoken Japanese from film and TV subtitles (FrequencyWords). Groups: Top 100, 101–300, 301–600, 601–1,000, 1,001–1,500 and 1,501–2,000. Each works with the kanji quiz.

### Changed
- The kanji group chips are split into two labelled rows: By school grade, and Most used in daily life.
- Switching group closes any open kanji quiz.

## 1.13 (21 October 2026)

### Added
- **Challenge test** on the Kana tab: 20 questions mixing hiragana and katakana, with three kinds of question (see a character and pick its reading; hear a sound and pick the character; see the romaji and pick the character) and look-alike wrong answers (さ and ち, ね, れ and わ, シ and ツ, ソ and ン, voiced and unvoiced pairs). When you pick the wrong character it tells you which one you chose. Your best score is saved, and answers count towards each character’s dots.

### Changed
- **The normal kana quiz is more random.** Only 4 of its 10 questions focus on characters you’re working on; the other 6 come from anywhere in the chart, learned ones included.
- Answer options are now shuffled fairly in every quiz; before, the correct answer tended to appear in the same positions.

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
