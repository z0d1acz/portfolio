# z0diacz — HTB Writeups & Labs

Hi — I'm **z0diacz**. This repository collects my HackTheBox writeups, sanitized exploit scripts, and notes from labs I completed.

---

## 🔗 Quick Links
- **LinkedIn:** https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE  
- **HackTheBox:** https://www.hackthebox.com/profile/YOUR-HTB-USERNAME  
- **GitHub:** https://github.com/YOUR-GITHUB-USERNAME

---

## 📚 Featured writeups
- **Hacknet** — SSTI → file-based cache poisoning (pickle RCE) → GPG key recovery → DB decryption → root. (See `_posts/2025-10-02-hacknet.md`)
- *(More posts will appear here as I publish them.)*

---

## 🎯 About this repo
This site is built with [Jekyll](https://jekyllrb.com/) and GitHub Pages. My goal is to:
- publish clear, *sanitized* walkthroughs,
- explain the root cause and remediation,
- provide minimal PoC code that’s safe to reuse for learning (no live credentials or flags included).

---

## 🛠 Deploy (quick)
If you're maintaining this repo and want it live on GitHub Pages:

```bash
# locally
git clone git@github.com:YOUR-GITHUB-USERNAME/YOUR-REPO.git
cd YOUR-REPO
# add the files (index.md and README.md or post files)
git add index.md README.md _posts/2025-10-02-hacknet.md
git commit -m "Add homepage, README, and Hacknet post"
git push origin main
