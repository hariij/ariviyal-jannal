# அறிவியல் ஜன்னல் (Window on Science)

Hari Pravin's Tamil YouTube science series. Each episode takes one idea about how science works and teaches it with everyday Indian examples, to build scientific temper in students and families. Every topic becomes a long episode, a Short, and an interactive web page, so the series can also stand as a website (in Hari's portal hariprav.in or on its own).

**This folder is the source of truth.** Production happens here, in Claude Code. The claude.ai Project "அறிவியல் ஜன்னல்" is for consultation and planning only; decisions made there are carried into this folder by Hari or by Claude in the next session here.

## Start of every session

0. **First run only:** if `.claude/skills/ariviyal-jannal/SKILL.md` is missing and `setup/ariviyal-jannal-SKILL.md` exists, move it there (create the folders), then delete `setup/`.
1. Read this file, then `HANDOFF.md` (status, open decisions, the next step, lessons since the last wrap-up). If `HANDOFF.md` and the skill disagree, `HANDOFF.md` is newer; follow it.
2. For any production request, use the series skill in `.claude/skills/ariviyal-jannal/SKILL.md` and read the part the request names.
3. Check what already exists for the episode (`episodes/EN/`, its `notes.md` first) before making anything. Nothing that cost credits is ever made twice.

## End of every session

Update `HANDOFF.md`: the episode's status row, open decisions, the exact next thing Hari should say, and any lesson learned (one dated line each). Commit with a clear message if the folder is a git repo.

## Source material and copyright

- The series starts from Mr. C Shanmugham's WhatsApp "Window on Science" posts, compiled in `source/ElevenGotIt.pdf` (48 posts, 16 Sep to 8 Nov 2026, numbered by him as WS1 to WS48 in `plan/seasons.md`).
- Those posts reproduce the "Window on Science" boxes from Michael A. Seeds' astronomy textbooks (Cengage). The text belongs to the publisher.
- **Never read out, quote at length, or show the book's text** in a script, video, page or post. Every script is Hari's own, written fresh in Tamil, teaching the same idea with Indian and Chennai examples in place of the book's American ones (chili and Texans, Steinbeck, pounds per square inch).
- `source/` and `reference/` are listed in `.gitignore` and are never committed or published.

## Credits (every episode, page and description)

- Mr. C Shanmugham, for curating and sharing the series. For now he is credited only; he may appear or show demos in later episodes.
- Inspired by the "Window on Science" boxes in Michael A. Seeds' astronomy textbooks.

## Format

- **Language:** Tamil narration. English only for terms that are easier to understand in English (model, theory, evidence, pseudoscience), said once in Tamil where a natural Tamil word exists.
- **Every topic:** a long episode (16:9), a Short (9:16), and a web page.
- **Interactive pattern** in every episode: a hook question the viewer pauses and guesses at; one clear idea; a demo or visual; a quiz or try-at-home challenge at the end (with a YouTube poll or comment prompt). The web page carries the same quiz and challenge as something to play.
- **Numbering:** episodes E01, E02 and so on, in the order of `plan/seasons.md`.

## Rules that hold everywhere

1. **Hari decides at every creative step.** Nothing moves to the next function until he approves the current one.
2. **His wording is final**, in every script, title and post. A correction is also a rule for the lines that follow.
3. **Credits only with his yes**, with the cost shown first. Never repeat a generation call to retry. Do the free work first, then ask once with the price.
4. **Claude cannot hear.** Voice, music and whether a Tamil line sounds native are Hari's calls; say plainly what was checked only by numbers.
5. **No em dashes**, anywhere, including replies.
6. **One clear recommendation, then proceed.** Keep things simple.
7. **Science is checked.** Every fact, figure and example is verified against a current, reliable source before it goes in a script (the textbook boxes are decades old in places: update what has moved on). List the sources in the episode's `notes.md`.
8. **Question claims, never mock people.** Pseudoscience episodes test the claim with evidence and stay kind to the people who believe it; no religion, community or tradition is ridiculed.
9. **Demos are home-safe.** Kitchen and household materials only; nothing with fire, sharp tools, electricity from the mains or chemicals beyond the kitchen. Say so on screen when an adult should help.
10. **Never overwrite an approved file.** A change makes the next version beside it (`E01-v2.mp4`).
11. **A rule is written at the strength of the note it came from.** Do not add "never" or "every" Hari did not use.
12. **When a note can be read two ways, ask before changing anything.** When an open point is put to Hari, quote the exact line and give the options as lines.
13. **Write every decision and lesson down the moment it happens**, in `HANDOFF.md`. Wrap-up folds lessons into the skill.

## Where everything lives

```
CLAUDE.md                          this file: the rules
HANDOFF.md                         status, open decisions, next step, lessons
plan/seasons.md                    the 48 topics in seasons, with episode numbers
.claude/skills/ariviyal-jannal/    the series skill (the functions)
episodes/EN-<slug>/                one folder per episode (see the skill)
series/                            series look, sound kit, end card, credits text
site/                              the website, built from episodes/
source/      (gitignored)          ElevenGotIt.pdf, Mr. Shanmugham's posts
reference/   (gitignored)          copies of Hari's other series skills, to borrow from
```
