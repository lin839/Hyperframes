# Travel on the sky

Short travel videos for Redbook (Xiaohongshu), YouTube, TikTok, and similar platforms.

This folder is the production home for the **Travel on the sky** series — briefs, scripts, assets, HyperFrames compositions, captions, and platform exports.

## Layout

| Path | Use |
|------|-----|
| `templates/` | Blank starters for a new short |
| `briefs/` | Creative brief per short (`slug-brief.md`) |
| `scripts/` | Voiceover / on-screen copy |
| `storyboards/` | Shot lists / beat timing |
| `assets/footage/` | Raw video clips |
| `assets/audio/` | BGM, VO, SFX |
| `assets/stills/` | Photos, thumbnails, overlays |
| `compositions/` | HyperFrames project / edit files |
| `captions/` | Subtitles (SRT/VTT) and burned-in notes |
| `renders/` | Master renders (pre-platform) |
| `exports/tiktok/` | TikTok-ready cuts |
| `exports/youtube/` | YouTube Shorts cuts |
| `exports/redbook/` | 小红书-ready cuts |

## Start a new short

1. Pick a kebab-case slug, e.g. `sunrise-over-lhasa`.
2. Copy templates and rename:
   - `templates/brief.md` → `briefs/<slug>-brief.md`
   - `templates/script.md` → `scripts/<slug>-script.md`
   - `templates/storyboard.md` → `storyboards/<slug>-storyboard.md`
   - `templates/captions.srt` → `captions/<slug>.srt` (fill after picture lock)
3. Drop source media into `assets/` (footage / audio / stills), preferably under a matching `<slug>/` subfolder when you have more than a few files.
4. Build the edit in `compositions/` (HyperFrames or your editor of choice).
5. Export a master to `renders/<slug>.mp4`, then platform variants into `exports/{tiktok,youtube,redbook}/`.

Keep filenames consistent with the slug so briefs, scripts, and exports stay easy to find.
