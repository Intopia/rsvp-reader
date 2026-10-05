# RSVP reader

A simple tool for reading text one word at a time.

Some people find reading one word at a time easier, others find it harder. It depends on the person and the text. Try it and see if it works for you.

Text you paste here is not sent anywhere. The reader runs entirely in your browser.

## What it is

RSVP stands for Rapid Serial Visual Presentation. Instead of your eyes moving along a line of text, each word appears in the same spot on screen, one after another.

Each word has one highlighted letter, called the Optimal Recognition Position (ORP). It sits slightly left of the middle of the word, and the whole word shifts so that this letter always lands in exactly the same place, marked by small ticks above and below. The highlighted letter isn't there to be read. It's a fixation point, something for your eyes to rest on, so they don't need to move.

## How it could be useful

- **Reading without tracking lines.** There's no line to follow, no jump back to the start of the next line, and no neighbouring words competing for attention. Some people whose eyes jump around a line of text find this makes sentences much easier to put together.
- **One sentence at a time.** With "Pause after each sentence" ticked, the reader stops at the end of each sentence and waits until you're ready for the next one. This works well for emails and other everyday text.
- **Reading at your own pace.** You can step through word by word with the arrow keys, slowing down, speeding up, or going back whenever you need to.
- **Proofreading.** When we skim text, our brains quietly fix mistakes before we notice them. Seeing one word at a time breaks that habit, so errors like missing spaces ("messageis") or run-on sentences ("fine.It") stand out immediately. This is similar to how screen reader users often notice errors, as mistakes are announced oddly.

Faster word recognition doesn't always mean better understanding or memory. RSVP tends to work better for straightforward text than for material you need to study closely.

## How to use it

1. Paste text into the "Text to read" box.
2. Choose a speed between 200 and 700 words per minute.
3. Optionally tick "Pause after each sentence".
4. Press Play, or use the keyboard shortcuts below.

## Keyboard shortcuts

These work anywhere on the page except inside the text box and the speed slider.

| Key | Action |
| --- | --- |
| Space | Play or pause |
| Left arrow | Back one word |
| Right arrow | Forward one word |
| Shift + Left arrow | Back to the start of the sentence (press again to go back another sentence) |
| Home | Restart from the beginning |

Using the arrow keys while the reader is playing moves to the new word and keeps playing.

## Accessibility features

- **Full keyboard support.** All controls are native buttons, a slider and a checkbox, so they can be reached and used with a keyboard, with a clear visible focus indicator.
- **Nothing plays automatically.** Reading only starts when you press Play, and it can be paused at any time.
- **Screen reader friendly status messages.** Changes such as playing, paused, end of sentence and finished are announced. The word display is deliberately not announced as it changes, as a screen reader reading up to 12 words a second would be overwhelming. The pasted text remains available as the readable version.
- **Not reliant on colour.** The highlighted letter is marked by colour and also by its fixed position between the tick marks.
- **Good contrast.** Word text is 15.65:1 against the background, and the highlighted letter is 5.39:1.
- **A legible reading font.** The word display uses Atkinson Hyperlegible, a typeface designed for clear letter recognition.
- **Long words fit.** Very long words are scaled down so they fit on either side of the highlighted letter, including on phones.
- **Light and dark mode.** The page follows your system setting.
- **Remembers your settings.** Speed and the "Pause after each sentence" setting are stored in your browser only, so they're there next time.

## How timing works

The speed sets the base time for each word. Some words get extra time:

- Words ending a clause (comma, semicolon, colon or dash): 1.5 times as long
- Words ending a sentence (full stop, question mark, exclamation mark or ellipsis): 2 times as long
- The last word of a paragraph: at least 2.5 times as long
- Long words (9 or more characters, and again at 13 or more): a little extra time

Because of these pauses, your actual reading speed will be a little below the number shown.

Common abbreviations such as Mr., Mrs., Ms., Dr., St., e.g. and i.e., and single initials such as J., are not treated as the end of a sentence.

## Known limitations

- Words are split on spaces only, so hyphenated words such as "three-and-twenty" are shown as one word.
- Only blank lines count as paragraph breaks. Single line breaks, common in emails, are treated as part of the same paragraph.
- At the top speed, the word changes around 12 times a second. If fast changing text is uncomfortable, start slow and pause at any time.
