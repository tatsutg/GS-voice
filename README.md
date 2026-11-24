# GS-voice

Unit voice clips for the Grand Summoners fan database (Unit Info > Voice tab).

- `<base>/<slug>.m4a`: one clip per voice line (AAC mono 48 kHz, 96 kbps), taken from the game's JP voice banks (GL bank for GL-only units).
- `voices.json`: the button list per unit (`units`) and the subtitles (`subs`). `tl: 1` marks a JP-only unit whose English is the site's own translation.
- `_report.txt`: how every cue was matched and labelled.

Built by `tools/build_all_voices.py` in the GS repo. Units with a hand-made entry in the site's `js/voices.js` are not here.

Voices and game data belong to their owners. This is a free fan project, not affiliated with the official Grand Summoners team.
