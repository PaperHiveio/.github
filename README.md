# .github

The Paperhive organisation profile. `profile/README.md` is what github.com/paperhiveio shows.

The banner is `profile/banner.html`, exported to `profile/banner.png` (1280x640 at 2x) with headless Chrome:

```sh
cd profile
chrome --headless=new --hide-scrollbars --force-device-scale-factor=2 --window-size=1280,640 \
  --virtual-time-budget=8000 --screenshot=banner.png banner.html
```
