# bash-scripts

The 'copyvid' script is basically a modified version of this wonderful [fzf-preview](https://github.com/gmou3/fzf-preview) script, huge respect for the original dev.

## Requirements
⚠️ For both scripts to work, you ought to be using Wayland. ⚠️

---

### copyvid
- `fzf`
- `fd` _(optional but recommended)_
- `wl-clipboard`
- `fzf-file2preview.sh` file in your $PATH from [fzf-preview](https://github.com/gmou3/fzf-preview)

Only one of the following is needed:
- `ueberzug` or `ueberzugpp`
- `kitty` (If you're running inside a `kitty` terminal)
- `chafa`
- `catimg`
- `realpath`

---

### ytcopy
- `yt-dlp`
- `wl-clipboard`
- `sed`
- `realpath`

## Slight chances you may need to do
If you're using a different browser other than Firefox, you should change lines 36 and 38 from the `ytcopy` file after the `--cookies-from-browser` flag accordingly, such as `chrome`, `brave`, `vivaldi`, etc.
