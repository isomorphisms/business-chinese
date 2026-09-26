# Arabic: Amazon maintenance conversations

Goal: recover and extend the practical Arabic phrases needed while arriving at
someone's workstation as a maintenance technician.

## Spoken target

Use **Yemeni Arabic as the default spoken target**.

Do not pretend that "Yemeni Arabic" is one completely uniform dialect. When a
phrase is known to be associated with Sana'a, Taiz, Aden, Hadramawt, or another
regional variety, record that. Keep Iraqi, Lebanese, Syrian, Egyptian, and other
variants when they differ in wording or social effect.

Arabic script is primary. Transliteration is a learning aid, not the canonical
text.

## What each phrase record should preserve

A useful entry is more than a translation pair. Record, when known:

- intended meaning in the actual situation;
- Arabic script;
- pronunciation/transliteration;
- dialect or regional provenance;
- literal meaning when that helps;
- natural English meaning;
- who is speaking to whom, including gender/number where relevant;
- likely social effect: warm, deferential, distant, teasing, boss-like,
  worksite-casual, unusually careful, etc.;
- whether it sounds native, bookish, imported from another dialect, or merely
  understandable;
- competing phrasings and the contexts in which each is likely;
- misleading dictionary associations: what a native speaker is actually likely
  to hear first matters more than an etymological or dictionary connection.

Do not reduce these distinctions to a single "formal/informal" or
"polite/impolite" axis. Those labels are useful only when the entry also says
what kind of relationship, distance, deference, warmth, class signal, regional
signal, or conversational stance the wording can imply.

## Diagnostic phrases to drill

- What is broken?
- What happened?
- When did it start?
- Does it happen every time?
- Show me what it is doing.
- What were you doing when it stopped?
- I am going to check it.

## Give-the-worker-a-break phrases

The intended social meaning matters: the technician's arrival is an excuse for
the worker to stop standing and rest, not an attempt to supervise them.

Drill meanings such as:

- Go take a break.
- Sit down and enjoy the break.
- You do not need to keep standing here.
- I am a technician, not a manager.
- I am here to fix this, not make your day harder.
- Rest five minutes.
- `irtāḥ khams daqāyiq` was already used as a remembered drill phrase.

## Small talk worth retaining

- What are you having for lunch?
- Where are you from?
- How long have you been in the United States?
- How are you liking it?
- Do you still talk with your family back home?
- The day is almost over.

## Rendering requirements

Arabic support is part of the software test surface, not an afterthought. Test:

- right-to-left layout and Arabic shaping;
- Arabic mixed with English, Latin transliteration, numbers, and punctuation;
- cursor movement, selection, deletion, and wrapping;
- terminal and Android rendering;
- search/indexing of Arabic text;
- filenames containing Arabic where the underlying toolchain permits them;
- code that accidentally reverses RTL text or assumes one code point equals one
  displayed character.

Keep the Arabic natural and spoken. Record dialect variants instead of
pretending one formal rendering is what everyone at work would say.
