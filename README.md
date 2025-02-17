# bash-scripts

This repository contains useful Bash scripts.  

## About  

The **`copyvid`** script is a modified version of the excellent [fzf-preview](https://github.com/gmou3/fzf-preview) script. Huge respect to the original developer!  

⚠️ **Both scripts require a Wayland environment.** ⚠️  

---

## 📜 Requirements  

### **`copyvid`**
This script allows quick video selection with preview support.  

#### **Dependencies:**  
- `fzf`
- `fd` _(optional but recommended for better file searching)_
- `wl-clipboard`
- `realpath`
- The `fzf-file2preview.sh` script (must be in your `$PATH`) from [fzf-preview](https://github.com/gmou3/fzf-preview)  

#### **At least one of the following is required for image previews:**  
- `ueberzug` or `ueberzugpp`  
- `kitty` _(if running inside a `kitty` terminal)_  
- `chafa`  
- `catimg`  

---

### **`ytcopy`**
This script downloads videos using `yt-dlp` and copies the file path to the clipboard.  

#### **Dependencies:**  
- `yt-dlp`
- `wl-clipboard`
- `sed`
- `realpath`  

---

## ⚙️ Possible Changes You May Need  

If you're using a browser **other than Firefox**, update **lines 36 and 38** in `ytcopy` to match your browser, such as:
`--cookies-from-browser chrome` or `--cookies-from-browser vivaldi`.  
