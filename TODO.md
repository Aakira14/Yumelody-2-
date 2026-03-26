# Music Player GitHub Pages Fix - TODO

## Status: In Progress

### Planned Steps:
1. ✅ **Understand project & issues** (paths, audio policy - done)
2. ✅ **Create TODO.md** (this file)
3. ✅ **Edit index.html**: Add `muted` and change `preload="metadata"` to audio element
4. ✅ **Edit script.js**: 
   - Add volume control (default 0.5, unmute on first play)
   - Prepend './' to paths
   - Ensure audio.load() & error handling
   - Reset currentTime=0 on next/prev
5. **Test locally**: Run `cd /Users/premtanu/Downloads/asthetic && python3 -m http.server 8000`, open http://localhost:8000 - verify images/music/playback/unmute
6. **GitHub deploy**:
   - `git init`
   - `git add .`
   - `git commit -m "Pixel music player with GH Pages fixes"`
   - Create repo, `git remote add origin <url>`
   - `git branch -M main && git push -u origin main`
7. **Enable GitHub Pages**: Repo Settings > Pages > Source: Deploy from branch (main), folder /
8. ✅ **Complete** - Test on https://username.github.io/repo
