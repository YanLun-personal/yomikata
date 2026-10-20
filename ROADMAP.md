# Yomikata roadmap

Pending improvements for Yomikata, as of 18 October 2026. The app is **Yomikata v1.8**. Yomikata 2 has been retired; all updates now go to Yomikata only. Pick any item by its number and ask Claude to build it. Numbers stay fixed, so a finished item keeps its number.

## Next up: recorded audio

| # | Improvement | Why it helps | Notes and open questions |
|---|---|---|---|
| 29 | Recorded native-speaker audio for kana | The biggest possible improvement over device voices. | Only if an openly licensed recording set can be downloaded from Claude's build environment. Not yet confirmed. |

## Visual learning

| # | Improvement | Why it helps | Notes and open questions |
|---|---|---|---|
| 17 | Kana growing from their kanji | A short animation morphs 安 into あ, or trims 阿 down to ア. Turns the kana origins into something you remember by sight. | Uses the origin data already in the app. Smooth morphing between two shapes is hard; a timed fade with the kept part highlighted is the realistic version. |
| 18 | Word order that rearranges itself | On grammar cards, “I eat an apple” animates into 私 は りんご を 食べます, with the verb sliding to the end and particles dropping in as tags. | Builds on the colour coding from v2.0. Best for the Week 3 and 4 grammar cards first. |
| 19 | Kanji built from parts | 休 shown as 亻 (person) plus 木 (tree), each part in its own colour, with a one-line picture story. Many parts mean the same in Chinese. | Part data exists in KanjiVG, which the app already includes. The picture stories must be written by hand, so start with Grades 1 and 2. |
| 20 | Pictures for concrete words (partly done in v1.8: about 400 core words) | An emoji next to words such as 犬 🐕, 雨 🌧, 電車 🚃 and ラーメン 🍜, in word lists, flashcards and the listening quiz. | Emoji need no download. Map by hand for common nouns only; automatic matching gives odd results. |
| 21 | Counter pictures | Each counter shows the shape it counts: a pen and a bottle for 本, a sheet of paper for 枚, a cat for 匹. | Small, uses emoji or simple drawings. |
| 22 | Moving clock and calendar | A clock face whose hands move with the time picker, and a month calendar with the irregular dates highlighted. | Fits the Numbers tab. |
| 23 | Pitch accent drawn as lines | A line rising and falling over each word’s kana. | Depends on item 2 (pitch-accent data). |
| 24 | Week-by-week video picks | Links to beginner YouTube channels or playlists for each plan week’s topic. | Videos can’t be embedded (the Claude version blocks them and they won’t work offline). Individual video links can’t be verified from Claude’s environment, so these would be channel or search links. |
| 25 | Handwriting practice with stroke guides | Trace kana and kanji over the animated stroke order with your finger. | Same as item 5; now easier because stroke data is in the app. |

## Speaking and listening

| # | Improvement | Why it helps | Notes and open questions |
|---|---|---|---|
| 1 | Pronunciation check | You say a phrase and see what your phone’s speech recognition heard, so you know whether you’d be understood. | iPhone Safari supports speech recognition in the browser. Offline behaviour and accuracy for Japanese need testing first. |
| 2 | Pitch accent | Some words differ only by pitch (箸 chopsticks and 橋 bridge are both はし). Marks on words make your speech sound natural. | Needs an open pitch-accent dataset reachable from GitHub. Licence and coverage to be confirmed. Item 23 draws it visually. |
| 3 | Shadowing mode | Plays a phrase, pauses for you to repeat it, then plays the next. Hands-free speaking practice. | Uses the phrasebook and example sentences already in the app. |

## Reading and writing

| # | Improvement | Why it helps | Notes and open questions |
|---|---|---|---|
| 5 | Handwriting practice | Trace kana and kanji on screen with your finger. | Merged with item 25. |
| 6 | Reading helper | Paste any Japanese text, such as a menu or a message, and see readings above the kanji and meanings when you tap a word. | Needs a Japanese word splitter such as kuromoji. Its dictionary may add several MB, so check the size first. |
| 7 | Kanji reading quiz | Shows words from a grade’s kanji and asks for the correct reading. Tests readings, which your Chinese doesn’t give you. | Uses data already in the app. |

## Habits and progress

| # | Improvement | Why it helps | Notes and open questions |
|---|---|---|---|
| 10 | Weekly summary | Cards mastered and listening accuracy over time, next to the study calendar. | The study calendar and kanji map from v2.0 cover part of this. |

## More content

| # | Improvement | Why it helps | Notes and open questions |
|---|---|---|---|
| 11 | More phrasebook situations | Work and business, phone calls, the doctor or pharmacy, visiting someone’s home. | Hand-written content, so worth a native-speaker check (item 16). |
| 12 | Culture notes | Bowing, shoes off indoors, chopstick manners, gift-giving. | A short section on the Start or Phrases tab. |
| 13 | Weeks 9 to 16 (JLPT N4 level) | Grade 3 kanji, the next set of grammar, and the full polite system (keigo). | Large; best split into two or three updates. |

## Quality and maintenance

| # | Improvement | Why it helps | Notes and open questions |
|---|---|---|---|
| 15 | “Update available” notice | Tells you when a new version has downloaded, so the second-launch delay isn’t confusing. | Small change to the service worker. |
| 16 | Native-speaker review | The phrasebook, faux amis, grammar examples and colour coding were checked by hand, not by a native speaker. A short review by a tutor would catch anything unnatural. | Not a code change. |

## Done

Finished work is recorded version by version in `CHANGELOG.md`.

## Parked or decided against

- **JLPT N5 word tags.** Dropped because the goal is talking with locals, not the exam. Revisit if you plan to sit the JLPT or need a certificate for work or a visa.
- **Automatic sync between devices.** Would need an account and a server. Backup codes on the Plan page cover moving to a new phone.
- **Claude-powered sentence translation.** Replaced by shortcut buttons to Google Translate, DeepL and Jisho, which don’t use Claude.
- **Colour coding for the 26,000 example sentences.** Automatic colouring makes mistakes on unchecked sentences, so it stays limited to hand-checked ones.

## Known limitations

- Audio uses the phone’s built-in voices. Quality depends on which Japanese voice is installed (see item 29).
- Automatic katakana for names can be wrong for English names spelled differently from how they sound, such as David. Type the name in katakana instead.
- Searching example sentences in Chinese often finds nothing, because Chinese and Japanese phrase things differently. Search in English instead.
- Kanji cards don’t show Cantonese readings, Middle Chinese reconstructions or the Go-on and Kan-on split. The sources weren’t reachable from Claude’s build environment.

## Updating the app on your phone

1. Unzip the new `yomikata-app.zip` in the Files app.
2. In Safari, open the `yomikata` repository on GitHub, tap **···**, then **Upload file**.
3. Select all six files and tap **Commit changes**.
4. Open the app twice. The second launch shows the new version. Your progress stays.
