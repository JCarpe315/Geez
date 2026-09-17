# Ge'ez Translation Starter Kit
### A working kit for the solo English-speaking translator — companion to Part 8.10 of the compendium

---

## 0. How to Use This Kit

This kit assumes you speak and write English only, and that you are starting from zero Ge'ez. It gives you: a verified practice text with a word-by-word model parse, blank worksheets, a paradigm cheat sheet, a pitfalls card, and a twelve-week schedule. Everything else you need (grammar book, dictionary, the full alphabet charts) is listed in section 8.

The one rule above all others: **transliterate before you translate.** Never work directly from the Ethiopic script into English. Symbol by symbol, then word by word — the script hides things (gemination, vowel length) that your transliteration must restore before you open the dictionary.

**Your practice text:** the opening of **1 Enoch, chapter 1, verses 1–3** — chosen because (a) it is the most famous opening in all of Ge'ez literature, (b) its Ge'ez text below is verified against the Beta Maṣāḥǝft project's digital transcription, carried in the open-source repository `LPettay/ethiopian-bible` (CC BY-SA 4.0), and (c) a public-domain check-translation exists (R.H. Charles, 1917) so you can audit yourself.

---

## 1. The Working Method in One Page

1. **Symbol → syllable.** Each Ge'ez character is one consonant+vowel. Split the verse at every ፡ (word divider). Write each word in transliteration, restoring doubled consonants and long vowels the script hides (e.g., the difference between bet "house" and bett — context and the dictionary tell you).
2. **Syllable → root.** Strip each word to its bare consonants. Ge'ez dictionaries are organized by root, not by spelling.
3. **Root → word.** Look the root up in Leslau's *Concise Dictionary*, then identify the pattern (vowels, prefixes, suffixes) that turns root into this word. The pattern carries the grammar.
4. **Word → morphemes.** Cut off pronoun suffixes (bet-hu = "his house"), the fused prepositions (ba-, la-, ʾəm-), the construct ending -ä ("house-of"), the accusative -ä (direct object).
5. **Morphemes → clause.** Ge'ez runs VSO — verb first. Watch the conjunction wä- ("and") chaining clauses; watch zä/ʾəntä/ʾəlla introducing relatives; watch -sə, a clitic meaning "but/however/indeed" glued to the previous word.
6. **Clause → English, twice.** Produce a wooden-literal column and a smooth column. Never let the smooth version hide a choice the wooden one made.
7. **Audit.** Compare against the check-translation. Every divergence is either a discovery or a mistake — find out which, in writing, before moving on.

---

## 2. Practice Text: 1 Enoch 1:1–3

Ge'ez text and transliteration from the `LPettay/ethiopian-bible` repository (Ge'ez source: Beta Maṣāḥǝft, CC BY-SA 4.0). Note: this transliteration writes final sixth-order vowels as **-ə**; construct-state nouns appear with **-ä**. Where it and Lambdin's grammar differ on conventions, Lambdin wins.

**Verse 1**
> ቃለ፡ በረከት፡ ዘሄኖክ፡ በከመ፡ ባረከ፡ ኅሩያነ፡ ወጻድቃነ፡ እለ፡ ሀለዉ፡ ይኩኑ፡ በዕለተ፡ ምንዳቤ፡ ለአሰስሎ፡ ኵሉ፡ እኩያን፡ ወረሲዓን።

> qalä | bäräkätə | zähenokə | bäkämä | baräkä | ḫəruyanä | wäṣadəqanä | ʾəlä | häläwu | yəkunu | bäʿəlätä | mənədabe | läʾäsäsəlo | kwəlu | ʾəkuyanə | wäräsiʿanə

**Verse 2**
> ወአውሥአ፡ ሄኖክ፡ ወይቤ፡ ብእሲ፡ ጻድቅ፡ ዘእምኀበ፡ እግዚአብሔር፡ እንዘ፡ አዕይንቲሁ፡ ክሡታት፡ ወይሬኢ፡ ራእየ፡ ቅዱስ፡ ዘበሰማያት፡ ዘአርአዩኒ፡ መላእክት፡ ወሰማዕኩ፡ ዘእምኀቤሆሙ፡ ኵሎ፡ ወአእመርኩ፡ አነ፡ ዘእሬኢ፡ ወአኮ፡ ለዝ፡ ትውልድ፡ አላ፡ ለዘይመጽኡ፡ ትውልድ፡ ርሑቃን።

**Verse 3**
> በእንተ፡ ኅሩያን፡ እቤ፡ ወአውሣእኩ፡ በእንቲኣሆሙ፡ ምስለ፡ ዘይወፅእ፡ ቅዱስ፡ ወዐቢይ፡ እማኅደሩ።

---

## 3. Model Parse — Verse 1, Fully Worked

This is what a finished line looks like. Columns: word (Ge'ez + transliteration) · root · pattern/affixes · grammar · literal gloss.

| Word | Root | Pattern / affixes | Grammar | Literal gloss |
|---|---|---|---|---|
| ቃለ qalä | q-l "word" | qal + -ä | noun "word" + **construct state** | word-of |
| በረከት bäräkätə | b-r-k "bless" | bäräkät | noun, abstract | blessing |
| ዘሄኖክ zähenokə | (proper name) | zä- + Henok | **zä- relative/genitive linker** | of-Enoch |
| በከመ bäkämä | — (particle) | bä- + kämä | fused prep + "as" | according-as / wherewith |
| ባረከ baräkä | b-r-k | baräkä | **perfect, 3rd person singular** "he blessed" | he-blessed |
| ኅሩያነ ḫəruyanä | ḫ-r-y "choose" | ḫəruy (passive part. "chosen/elect") + -an (pl.) + **-ä accusative** | direct object | the-elect (obj.) |
| ወጻድቃነ wäṣadəqanä | ṣ-d-q "be righteous" | wä- + ṣadəq + -an + -ä | conjunction + adj. pl. + accusative | and-the-righteous (obj.) |
| እለ ʾəlä | (pronoun) | ʾəlä | **plural relative pronoun** "who" | who |
| ሀለዉ häläwu | h-l-w "be, exist" | häläw + -u | perfect, 3rd plural | they-were |
| ይኩኑ yəkunu | k-w-n/kona "become" | y-…-u | imperfect/jussive, 3rd plural | they-will-be |
| በዕለተ bäʿəlätä | — (noun ʿəlät, "day") | bä- + ʿəlät + -ä | fused prep + noun + construct | on-day-of |
| ምንዳቤ mənədabe | n-d-b/nədäba "be distressed" | mə-nə-dab-e | noun, "distress, tribulation" | tribulation |
| ለአሰስሎ läʾäsäsəlo | s-s-l (säsäla, "remove") | lä- + ʾa-säsəl-o | fused prep + **causative stem** + infinitive/gerund | for-the-removing-of |
| ኵሉ kwəlu | k-w-l "all" | kwəl + -u | adjective, masc. | all |
| እኩያን ʾəkuyanə | ʾ-k-y "be bad" | ʾəkuy + -an | adjective plural | the-wicked |
| ወረሲዓን wäräsiʿanə | r-s-ʿ "be godless/apostatize" | wä- + räsiʿ + -an | conjunction + noun/adj. plural | and-the-godless |

**Wooden literal:** "Word-of blessing of-Enoch, wherewith he-blessed the-elect (obj.) and-the-righteous (obj.), who they-were [and] they-will-be, on-day-of tribulation, for-the-removing-of all the-wicked and-the-godless."

**Smooth:** "The words of the blessing of Enoch, with which he blessed the elect and righteous, who will be living in the day of tribulation, when all the wicked and godless are to be removed."

*(Check against Charles 1917: near-identical. Note how Ge'ez's lack of articles means every "the" above is an interpretive addition — own each one.)*

---

## 4. Blank Worksheets

Fill every column before looking anything up in English. Words are given Ge'ez + transliteration; you supply root, pattern, grammar, gloss.

### Worksheet A — 1 Enoch 1:2 (29 words)

| # | Word | Root | Pattern/affixes | Grammar | Your gloss |
|---|---|---|---|---|---|
| 1 | ወአውሥአ wäʾäwəśəʾä | | | | |
| 2 | ሄኖክ henokə | | | | |
| 3 | ወይቤ wäyəbe | | | | |
| 4 | ብእሲ bəʾəsi | | | | |
| 5 | ጻድቅ ṣadəqə | | | | |
| 6 | ዘእምኀበ zäʾəməḫäbä | | | | |
| 7 | እግዚአብሔር ʾəgəziʾäbəḥerə | | | | |
| 8 | እንዘ ʾənəzä | | | | |
| 9 | አዕይንቲሁ ʾäʿəyənətihu | | | | |
| 10 | ክሡታት kəśutatə | | | | |
| 11 | ወይሬኢ wäyəreʾi | | | | |
| 12 | ራእየ raʾəyä | | | | |
| 13 | ቅዱስ qədusə | | | | |
| 14 | ዘበሰማያት zäbäsämayatə | | | | |
| 15 | ዘአርአዩኒ zäʾärəʾäyuni | | | | |
| 16 | መላእክት mälaʾəkətə | | | | |
| 17 | ወሰማዕኩ wäsämaʿəku | | | | |
| 18 | ዘእምኀቤሆሙ zäʾəməḫäbehomu | | | | |
| 19 | ኵሎ kwəlo | | | | |
| 20 | ወአእመርኩ wäʾäʾəmärəku | | | | |
| 21 | አነ ʾänä | | | | |
| 22 | ዘእሬኢ zäʾəreʾi | | | | |
| 23 | ወአኮ wäʾäko | | | | |
| 24 | ለዝ läzə | | | | |
| 25 | ትውልድ təwələdə | | | | |
| 26 | አላ ʾäla | | | | |
| 27 | ለዘይመጽኡ läzäyəmäṣəʾu | | | | |
| 28 | ትውልድ təwələdə | | | | |
| 29 | ርሑቃን rəḥuqanə | | | | |

**Your wooden literal (one clause per line):**

**Your smooth translation:**

**Divergences from Charles 1917 (list each, and resolve it):**

### Worksheet B — 1 Enoch 1:3 (10 words)

| # | Word | Root | Pattern/affixes | Grammar | Your gloss |
|---|---|---|---|---|---|
| 1 | በእንተ bäʾənətä | | | | |
| 2 | ኅሩያን ḫəruyanə | | | | |
| 3 | እቤ ʾəbe | | | | |
| 4 | ወአውሣእኩ wäʾäwəśaʾəku | | | | |
| 5 | በእንቲኣሆሙ bäʾənətiʾahomu | | | | |
| 6 | ምስለ məsəlä | | | | |
| 7 | ዘይወፅእ zäyəwäṣ́əʾə | | | | |
| 8 | ቅዱስ qədusə | | | | |
| 9 | ወዐቢይ wäʿäbiyə | | | | |
| 10 | እማኅደሩ ʾəmaḫədäru | | | | |

**Your wooden literal:**

**Your smooth translation:**

**Divergences from Charles 1917:**

---

## 5. Paradigm Cheat Sheet

Tape this beside you. Simplified where safe (full paradigms in Lambdin); gemination shown by doubled consonants.

**Independent pronouns:** ʾänä (I) · ʾantä (you-m) · ʾanti (you-f) · wəʾətu (he) · wəʾəti (she) · nəḥna (we) · ʾantəmu (you-pl) · wəʾətomu (they-m) · wəʾəton (they-f)

**Perfect** (past; suffixes): qatalku (I) · qatlka (you-m) · qatlki (you-f) · qatala (he) · qatalat (she) · qatlna (we) · qatalu (they)

**Imperfect** (present/future; prefixes): əqattəl (I) · təqattəl (you-m/she) · təqattəli (you-f) · yəqattəl (he) · nəqattəl (we) · yəqattəlu (they)

**Jussive** (wish/command 3rd person; bare middle): yəqətəl "let him kill" · yəqətlu "let them kill"

**Imperative:** qətəl! (you-m) · qətəli! (you-f) · qətəlu! (you-pl)

**Gerundive** ("having done," takes object suffixes): qatli (m) · qatlo (f)

**Object suffixes on verbs** (ከ? no — just suffixes): -ni (me) · -ka (you-m) · -ki (you-f) · -o (him) · -a (her) · -na (us) · -kəmu/-kən (you-pl) · -omu/-on (them)

**Possessive suffixes on nouns:** -ya (my) · -ka (your-m) · -ki (your-f) · -u (his) · -a (her) · -na (our) · -omu/-on (their)

**Noun markers:** construct **-ä** on the *possessed* noun (betä nəguś = house-of king) · accusative **-ä** on the direct object · **no articles** — definiteness is context or demonstratives (zəntu/zənti "this," ʾəntu/ʾənti "that") · "to have" = bə- + noun ("there-is-to-me")

**Derived stems:** ta- (passive/reflexive: ta-qatala "he was killed") · ʾa- (causative) · ʾasta- (causative-reflexive) · doubled middle consonant (intensive)

**Relatives:** zä- (masc.) · ʾəntä- (fem.) · ʾəlla- (plural) — "the king **who** built…" and general "of" linkers

**Prepositions:** fused — ba- (in/with), la- (to/for), ʾəm- (from); free — wəstä (in), dibä (on), laʿəlä (upon), ḥabä (toward), məslä (with), kämä (as/like), ʾənəzä (while/as)

**Negation:** ʾi-…-əm (perfect: ʾi-qatalku-m "I did not kill") · al-…-əm (imperfect: al-əqattəl-əm "I do not kill")

**Particles:** wä- "and" (chains clauses) · -sə clitic "but/however/indeed" (glued to the word before) · kämä "that/as" (introduces clauses) · hallo "there is/are" (existential particle).

---

## 6. Pitfalls Quick Card

1. **The script hides gemination and vowel length.** Restore them in transliteration from grammar/dictionary before translating.
2. **No articles.** Every "the/a" is your choice — mark it.
3. **Cut at morphemes, not spaces.** Suffixes and fused prepositions hide inside words.
4. **፡ is the word boundary** — but fused forms cross it invisibly.
5. **Know your recension.** Printed Ge'ez Bibles are a 13th–14th-century revision layered over the ancient translation. For the oldest layer, use critical editions (Zuurmond for the Gospels) or the Beta Maṣāḥǝft transcriptions.
6. **Homographs kill.** The Ge'ez words for "he brought" and "it did not come" look nearly identical (Jubilees 4:24) — when a translation hinges on one letter's shape, check the apparatus, never guess.
7. **Parataxis is normal.** "And… and… and…" chains are the style, not the sloppiness. Keep two columns (wooden / smooth) so literalness and readability never corrupt each other.
8. **Never emend silently.** If you change the text, footnote it. (Charles's "This is the Son of Man" at 1 Enoch 71:14 — rejected by everyone since — is the eternal cautionary tale.)

---

## 7. The Twelve-Week Schedule

| Weeks | Work |
|---|---|
| 1–2 | Learn the fidäl from the compendium's Appendix D. Write all 26 series from memory, forwards and shuffled. |
| 3–4 | Lambdin lessons 1–5. Transliterate 1 Enoch 1:1 from the script alone, then check against the kit. |
| 5–6 | Work through the model parse of 1:1 until every step is automatic. Drill root-stripping: 50 roots through Leslau's Concise Dictionary. Memorize pronouns + perfect paradigm. |
| 7–8 | Worksheet A (1:2) solo, dictionary open. Audit against Charles 1917; log every divergence and its resolution. Memorize imperfect + jussive. |
| 9–10 | Worksheet B (1:3). Then pull Psalm 1's Ge'ez text from mezmuredawit.net (Ethiopian Psalter in Ge'ez, verse-aligned) and transliterate its first verse. |
| 11–12 | Translate 1 Enoch 1:4–9 (text in the repository, same JSON files) with the two-column method. Self-audit the whole chapter. Choose your next text: 4 Baruch or Tobit (short chapters, same repository), or a Psalm cycle. |

**Months 4–6:** a full text with a declared base manuscript/edition and an apparatus habit (see compendium 8.10). **Months 9–18:** readable biblical-Ge'ez fluency; after that, the untranslated frontier (Ser'ata Seyon, Covenant I, Ethiopic Clement 1/3–7, the Ethiopian Josippon, the Rest of the Words of Baruch) is genuinely open to you — fewer than 200 people on Earth can do this work, and those five books have no complete public English translation at all.

---

## 8. Resources

- **Leslau, *Concise Dictionary of Ge'ez*** (1989) — the working dictionary, organized by root, entries in Ethiopic script.
- **Lambdin, *Introduction to Classical Ethiopic*** (1978) — the starter grammar (transliteration only; bridge to script yourself).
- **Tropper, *Classical Ethiopic* (2021)** or **Wright, *Basics of Ancient Ethiopic* (2022)** — the upgrades.
- **Charles, *The Book of Enoch* (1917 edition)** — public domain; your check-translation for the practice text.
- **github.com/LPettay/ethiopian-bible** — the open-source Ge'ez canon reader (36 books: Ge'ez + transliteration + English; Ge'ez text from Beta Maṣāḥǝft, CC BY-SA 4.0).
- **Beta Maṣāḥǝft** (betamasaheft.eu) — the Hamburg digital encyclopedia of Ge'ez manuscripts.
- **mezmuredawit.net** — the Ethiopian Psalter (Dawit) in Ge'ez, Amharic, and English, verse-aligned — your Psalm source for weeks 9–12.
- **ertale.com/ethiopiancanon** and **Wikisource** — canon texts and public-domain translations.
- **The compendium itself** — Appendix D for the alphabet; Part 8 for the translation wars and what to avoid; the ledger (Part Ten) for which scholarly claims are solid and which are open.

---

*Kit compiled September 2026. Practice text verified against the LPettay/ethiopian-bible repository (Beta Maṣāḥǝft transcription, CC BY-SA 4.0). Model parse by the compendium's author; disagreements with it are welcome — check them against Leslau and Lambdin, not against this file.*
