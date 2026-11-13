---
name: ariviyal-jannal
description: Use in the ariviyal-jannal folder for any episode of the அறிவியல் ஜன்னல் (Window on Science) Tamil science series or the series as a whole: series setup, brief, script, build, short, page, thumbnail, details, socials, notes, status, wrap-up, site. E.g. E01 brief, E02 script, E01 page, Series status.
---

# அறிவியல் ஜன்னல்: every episode, from idea to the posts and the page

Each episode teaches one idea about how science works, in Tamil, with Indian examples, a hook question, a demo or visual, and a quiz or challenge. Every topic becomes a long episode (16:9), a Short (9:16) and an interactive web page. The rules are in `CLAUDE.md`; status, decisions and the next step in `HANDOFF.md`.

This skill works the same way as Hari's other series on purpose: #TiffinPsychology (tiffin-plate), MapSDG Atlas (mapsdg-atlas), My Songs (lyric-video) and Paavam AI (paavam-ai). Copies of those skills are in `reference/skills/` (gitignored). **When a step here is not yet worked out, read the matching step there and borrow it rather than inventing a new one;** tiffin-plate is the most worked-out for narrated, faceless explainer videos, mapsdg-atlas for a repo-based workflow and an interactive player that also renders to video.

**Version 1, 14 November 2026.** Written before E01. The brief, script, Short, page, details and socials are set out; the build (pictures, voice, sound, render) is left to E01 to work out from tiffin-plate once Hari settles the look and the voice (`HANDOFF.md`, open decisions). Expect E01 to rewrite Part 3.

## The functions

**Making an episode** (in this order; each starts only when the one before it is approved)

| Hari says | Read | Makes | Hari decides |
|---|---|---|---|
| **EN brief** | Part 1 | One page: the idea in one Tamil sentence, the hook question, Indian examples, the demo, the quiz and challenge, the facts to check, the sources | The angle, the examples, the demo |
| **EN script** | Part 2 | The long episode's script, with the voice and the on-screen moments written in, reviewed on a player page | The wording |
| **EN build** (resume with "voice", "sound", "render") | Part 3 | The long episode. Stops after the pictures, after the sound, after the render | Pictures, sound, final watch |
| **EN short script** | Part 4 | The Short's own script, one arc, up to 90 seconds; recorded lines reused | The wording |
| **EN short build** | Part 4 | The vertical Short, with the same stops | Pictures, sound, final watch |
| **EN page** | Part 5 | The episode's interactive web page: the idea, the demo, the quiz and the challenge, playable | The page |
| **EN thumbnail** | Part 6 | YouTube thumbnail and a 4:5 still | The words on it |
| **EN details** | Part 6 | Title, description with credits, hashtags, tags, captions, chapters | Edits; his wording is final |
| **EN socials: [video link]** | Part 6 | Launch posts: WhatsApp, Facebook, LinkedIn, Instagram, X | Edits; his wording is final |
| **EN short details** / **EN short socials: [Short link]** | Part 6 | The same for the Short | Edits; his wording is final |

**Looking after the work** (Part 7)

| Hari says | What it does |
|---|---|
| **EN notes: ...** | Fixes anything already made, reusing recorded voice |
| **EN status** | What is done, what is next, where every file is, credits spent |
| **Series status** | The same for all episodes, from `HANDOFF.md` and `plan/seasons.md` |
| **EN wrap-up** | Lessons folded in, `HANDOFF.md` tidied, the skill updated if anything was learned |
| **Update the skill** | Only the skill: lessons from `HANDOFF.md` folded into this file |

**The series** (Part 8): **Series setup**, **Season plan**, **Site**, **Trailer**, **Playlist details**.

If Hari's words do not match a function exactly, pick the nearest one and say which you took. When telling him what to say next, give the function exactly as written in these tables.

## Step 0: before any function

1. Read `CLAUDE.md` and a fresh `HANDOFF.md`. If they disagree with this skill, they are newer; follow them.
2. Check what already exists: the episode's row in `HANDOFF.md`, its folder `episodes/EN-<slug>/` (`notes.md` first), and any published player or page. Nothing that cost credits is made twice.
3. Read the topic's source post in `source/ElevenGotIt.pdf` for the idea only. Never copy its sentences.
4. Reuse before building: read the matching stage in `reference/skills/` before starting a stage this skill has not worked out.

## Rules for every function

The rules in `CLAUDE.md` hold. In addition:

1. **One episode per session for building.** Brief, details, socials, notes and status can run in any session.
2. **At the end of every function:** update the episode's row and the next step in `HANDOFF.md`, and tell Hari exactly what to say next.
3. **Think in Tamil.** Write each line in Tamil from the start; never translate an English sentence. Everyday Chennai Tamil a student and a grandparent both follow; English terms as `CLAUDE.md` allows.
4. **Show, then name.** The idea is shown by the demo or the example before its name is given (the series' own lesson: understanding before naming, WS2).
5. **Nothing preachy.** The viewer reaches the idea by the hook and the demo; the narration does not lecture.
6. **When a creative piece keeps missing, change the approach, not the draft.**

## Part 1: EN brief

1. Read the topic's post and its row in `plan/seasons.md`.
2. Write `episodes/EN-<slug>/brief.md`:
   - **The idea** in one Tamil sentence, and in one English line for the record.
   - **Hook question**: something the viewer can guess at in five seconds and is likely to get wrong or argue about.
   - **Three Indian examples** in place of the book's, from daily life in Tamil Nadu (the kitchen, the bus, the temple festival, the cricket match, the exam hall, the weather report). Recommend one to lead.
   - **The demo or visual**: home-safe (`CLAUDE.md` rule 9), cheap, and filmable on a phone; or, for an abstract idea, a motion-graphics visual described in words.
   - **Quiz** (3 questions, one right answer each) and a **try-at-home challenge**.
   - **Facts to check** and the **sources** that check them; flag anything in the old textbook box that science has since revised.
   - **Short angle**: the one moment of the episode that works on its own.
3. Hari picks the angle, example and demo. Save his choices in the brief.

## Part 2: EN script

1. From the approved brief. Outline at the top: one line per beat (hook, pause-and-guess, the example, the demo, the idea named, a second example, the quiz, the challenge, credits and end card).
2. Write the script as data the player can read (`episodes/EN-<slug>/script/eNN.json` plus a readable `eNN-script.md`), following tiffin-plate Part 1 for the voice written in (`[pause]`, delivery tags) and the on-screen moments per line.
3. **Checks before Hari sees it:** Tamil thought in Tamil; every fact against the brief's sources; no sentence of the book's text (compare against the post); the hook is answered; the quiz matches the script; credits present; no em dashes. Then a fresh-eyes review by a separate agent that has not seen the drafting, against `CLAUDE.md` and these checks.
4. **Length:** from the voice pace (borrow tiffin-plate's estimate), within the long-episode length in `HANDOFF.md`.
5. Review on a player page, never as plain text only. Save versions beside each other (`eNN-script-v2.md`).

## Part 3: EN build

Not yet worked out. Before E01's build, settle the look and the voice (`HANDOFF.md` open decisions 2 and 3), then work it out from tiffin-plate Part 2 (pictures, voice, sound, video) and mapsdg-atlas (a player that plays in a page and renders frame by frame to video), and write the result back here at E01's wrap-up. Keep its stops: after the pictures, after the sound, after the render. Credits only with Hari's yes, priced first. Render on Hari's Mac.

## Part 4: EN short script, EN short build

The Short is its own script, one continuous arc up to 90 seconds: the hook, the demo or the turn, the idea in one line, and a pointer to the full episode and the page. Reuse recorded lines where they fit (free); new lines are priced. Build as in Part 3 in 9:16, borrowing tiffin-plate Part 3.

## Part 5: EN page

1. One self-contained page per episode in `site/episodes/eNN/`, built from the episode's files (the brief's quiz and challenge, the script's idea and examples), bilingual Tamil first with English alongside, like Hari's other pages on hariprav.in.
2. It plays: the hook as a guess the reader commits to before the answer, the demo as an interactive (a slider, a simulation, a sort-the-cards), the quiz scored, the challenge with a place to note what they found (kept in the reader's browser only).
3. Links to the long episode and the Short once published; credits at the foot.
4. The page reads the shared series style from `site/assets/`, so the whole site changes in one place. It must work both inside hariprav.in and on its own domain (relative links only).
5. Check it on a phone width and a desktop width before Hari sees it.

## Part 6: thumbnail, details, socials

Follow tiffin-plate Parts 4 and 5 (the thumbnail and its 4:5 still; the title, description, tags, captions and chapters; the launch posts per platform and their limits), with these series points:
- **Title:** the hook in Tamil, then `| அறிவியல் ஜன்னல் #N`.
- **Description:** one line on the idea; the page link; the credits from `CLAUDE.md`; the playlist link; #அறிவியல்ஜன்னல் #ScientificTemper.
- Every post carries the episode's link; the Short goes out the day after the episode unless `HANDOFF.md` says otherwise.

## Part 7: looking after the work

Notes, status, wrap-up and skill updates work as in tiffin-plate Part 6. A note on one thing is a note on that kind of thing: check the rest of the episode for it. Wrap-up folds `HANDOFF.md`'s lessons into this file and empties the list.

## Part 8: the series

- **Series setup**: settle `HANDOFF.md`'s open decisions with Hari, assign E numbers in `plan/seasons.md`, set up git (`source/` and `reference/` ignored), build the season plan review page, then hand on to **E01 brief**.
- **Season plan**: change the seasons or the order with Hari; renumber only episodes not yet published.
- **Site**: the site shell (`site/index.html`: the series, the seasons, each episode's card linking its page and videos) and where it is deployed.
- **Trailer** and **Playlist details**: as tiffin-plate Part 7.

## Where everything lives

```
episodes/EN-<slug>/
  brief.md          the approved brief
  notes.md          Hari's notes, sources, what changed; read first
  script/           eNN.json, eNN-script.md, versions beside each other
  build/            the player and its art, sound tools
  voice/  sound/    takes and mixes, with their ids
  renders/          eNN.mp4, eNN-short.mp4, versions beside each other
  thumbnail/  details/  socials/
series/             the look, the sound kit, the end card, the credits text
site/               the website's working source (assets/, episodes/eNN/, index.html)
dist/               what is live: copied from site/ when Hari approves; a push that changes it deploys to hariprav.in/ariviyal-jannal
```
