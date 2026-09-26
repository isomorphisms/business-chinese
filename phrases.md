# Seed phrases

This file establishes the phrase-record format before the full conversation
sweep.

Default target: **Yemeni Arabic**. Existing remembered forms are preserved with
their actual dialect status instead of being silently rewritten.

## 1. What's broken?

- Intent: ask what is broken at a workstation.
- Yemeni target: `إيش الخربان؟`
- Transliteration: `ēsh al-kharbān?`
- Existing remembered variant: `شو الخربان؟` — `shū l-kharbān?`
- Variant label: Levantine.
- Literal shape: "what [is] the broken thing?"
- Natural English: "What's broken?"
- Social effect: short, practical, worksite-casual.
- Status: Yemeni wording is a first-pass target; retain regional corrections
  rather than forcing one national form.

## 2. Let me look.

- Arabic: `خلّيني أشوف.`
- Transliteration: `khallīni ashūf.`
- Natural English: "Let me look."
- Social effect: ordinary spoken offer to inspect the problem; not a command.
- Dialect note: broadly colloquial wording, but regional pronunciation and
  preferred verb forms should be recorded during the full sweep.

## 3. I'll fix it.

- Existing remembered Arabic: `رح أصلّحه.`
- Transliteration: `raḥ aṣalliḥo.`
- Natural English: "I'll fix it."
- Variant label: Levantine because `رح` is doing the future-marking work here.
- Yemeni target: TODO — do not manufacture a Yemeni equivalent merely by
  swapping one word.

## 4. Go rest; let me fix this.

- Existing remembered Arabic: `روح ارتاح، خلّيني أصلّح هاد.`
- Transliteration: `rūḥ irtāḥ, khallīni aṣalliḥ hād.`
- Natural English: "Go take a break; let me fix this."
- Variant label: Levantine.
- Intended social effect: permission to stop hovering or standing while the
  technician works; friendly rather than supervisory.
- Important contrast: a mechanically literal imperative can sound boss-like if
  the relationship or tone is wrong. Preserve variants that instead sound like
  an invitation or reassurance.
- Yemeni target: TODO.

## 5. Sit down; rest a little.

- Arabic: `اقعد، ارتاح شوي.`
- Transliteration: `uqʿud, irtāḥ shway.`
- Natural English: "Sit down; rest a little."
- Intended social effect: friendly permission to take it easy while the repair
  is happening.
- Note: this replaces the earlier English gloss "enjoy it a little" when the
  real intent is simply to rest.
- Regional status: needs Yemeni-region checking during the full sweep.

## 6. Did you eat well?

- Existing remembered Arabic: `أكلت منيح؟`
- Transliteration: `akalt mnīḥ?`
- Natural English: "Did you eat well?"
- Variant label: Levantine because `منيح` is a strong regional signal.
- Social effect: casual, familiar small talk.
- Yemeni target: TODO.

## 7. Where are you from?

- Yemeni target: `من وين أنت؟`
- Transliteration: `min wayn anta?`
- Natural English: "Where are you from?"
- Social effect: normal conversational question; not inherently ceremonious.
- Variation note: gender and local pronunciation matter. Some Yemeni material
  also records `أين`/local pronunciations, so preserve the speaker's actual
  regional form rather than treating one spelling as the only Yemeni answer.

## 8. Come on, the day's almost over.

- Existing remembered Arabic: `يلّا، قرّب يخلص النهار!`
- Transliteration: `yalla, qarrab yikhlaṣ in-nahār!`
- Natural English: "Come on, the day's almost over!"
- Variant status: Levantine/Mashreqi first-pass wording.
- Social effect: encouraging, lightly playful end-of-shift talk.
- Yemeni target: TODO.

## Representation rule for later variants

Do not overwrite one phrase with another as if translation were a function.
Keep alternatives as separate records or subrecords, with the conditions that
make each one natural. In particular, distinguish:

- words a learner can safely use almost anywhere;
- words that identify a region;
- wording that is polite because it creates respectful distance;
- wording that is polite because it creates warmth or solidarity;
- wording that is technically grammatical but sounds bookish;
- wording that is dictionary-correct yet evokes the wrong association in a
  native listener.
