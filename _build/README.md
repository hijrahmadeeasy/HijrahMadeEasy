# How this copy was made (Web project)

Free static copy of hijrahmadeeasy.org (WordPress), address https://hijrahmadeeasy.github.io/HijrahMadeEasy/. Hidden from search (noindex, canonical = the real site) until the name is moved here.

`smallsite.sh` mirrors the site; then `HIDDEN=1 python3 -I wpstatic.py mirror OUT hijrahmadeeasy.org https://hijrahmadeeasy.github.io/HijrahMadeEasy/ posts.json pages.json` (on move day drop HIDDEN=1 and use https://hijrahmadeeasy.org/ as the address). Check with linkcheck.py and shoot.js.
