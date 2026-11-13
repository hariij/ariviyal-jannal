# Handoff

Read at the start of every session; update at the end. Newest information wins over the skill.

## Next step

1. **Season plan page:** Hari reorders on https://claude.ai/artifact/SyeA9ysEWLDNgYLWbPtDoX (private) and presses Save if he wants changes. The next session reads it (`ArtifactData` get, collection `plan`, doc `order`); if a saved order exists and differs from `plan/seasons.md`, it updates `seasons.md` and the E numbers before anything else. No saved document means the plan stands as it is.
2. Then Hari says **E01 brief** (WS3, astrology and pseudoscience).

## Decisions

Made 14 Nov 2026 in the claude.ai Project chat:

- Series name: அறிவியல் ஜன்னல் (Window on Science).
- Source: Mr. C Shanmugham's 48 "Window on Science" posts; they come from Michael A. Seeds' astronomy textbooks. Scripts are original; the book's text is never read out or shown.
- Language: Tamil, English terms only where easier in English.
- Every topic: a long episode and a Short, plus an interactive web page.
- Interactive pattern: hook question, one idea, demo or visual, quiz or try-at-home challenge.
- Credits: Mr. Shanmugham credited; no appearance for now.
- Production in Claude Code in this folder; the claude.ai Project is for consultation and planning.

Made 14 Nov 2026 at Series setup (Claude Code):

1. **Opening:** the "Spotting fake science" season moves to the front whole. E01 WS3 astrology and pseudoscience, E02 WS40 UFOs, E03 WS30 checks on fraud; then How science thinks (E04 to E10), and the rest in their order. E01 to E48 are in `plan/seasons.md`.
2. **Narration voice:** Hari's ElevenLabs voice clone, as in #TiffinPsychology. Credits per episode, priced first.
3. **Look:** faceless motion-graphics player, as in #TiffinPsychology, with short phone-filmed demo clips (hands only) so viewers see the home demo is real.
4. **Long episode length:** 4 to 6 minutes.
5. **Short length:** up to 90 seconds.
6. **Site:** built domain-free with relative links. Hari, on the repo: "we will consider it as a subproject of hariprav.in/ariviyal-jannal or something similar", and Hari, 14 Nov 2026: "we will keep it a separate repo". Settled the same day: the site is served at **hariprav.in/ariviyal-jannal** by GitHub Pages from this repo's `dist/` folder (the `deploy.yml` workflow his other hariprav.in projects use; it runs when `dist/` changes). `site/` is the working source; what is ready to go live is copied into `dist/`.
7. **Release rhythm:** fortnightly (one episode every two weeks, its Short the next day).
8. **Repo:** https://github.com/hariij/ariviyal-jannal, branch `main`. Created private on 14 Nov 2026, then made **public** the same day with Hari's yes, because GitHub Free serves Pages only from public repos. Anyone can read it; only Hari (and collaborators he adds) can change it. Commits use his GitHub noreply address (set in this repo's git config; the first three commits were rewritten to it before going public). `source/` and `reference/` are ignored and never pushed.

## Open decisions

| # | Decision | Options | Claude's recommendation |
|---|---|---|---|
| 11 | Release start date for E01 | | Set once E01's script is approved |

## Status

| E | WS | Brief | Script | Build | Short | Page | Thumbnail | Details | Socials | Published |
|---|---|---|---|---|---|---|---|---|---|---|
| E01 | 3 | next | | | | | | | | |

## Series links

- Repo (public): https://github.com/hariij/ariviyal-jannal
- Site: https://hariprav.in/ariviyal-jannal/ (Pages on, from `dist/`; nothing deployed yet)
- Season plan review page: https://claude.ai/artifact/SyeA9ysEWLDNgYLWbPtDoX (source `plan/season-plan.html`; saved order in its database, `plan/order`)

## Credits spent

None.

## Lessons since the last wrap-up

- 14 Nov 2026: GitHub access here is through `gh` (HTTPS, logged in as hariij); the Mac's SSH key is not on GitHub. Check `gh auth status` before promising a push.
- 14 Nov 2026: the repo is public, so anything committed is published, drafts included. Never commit book text, private notes or credentials.
- 14 Nov 2026: a review page Hari edits keeps his choice in the artifact's database so the next session can read it without a paste.
