# Day 9/30: Audio + Video Elements - Theory Day

### What I Learned
Day 8: Built HTML bones for pages ✅  
Day 9: Studied how to give bones a voice + eyes 🎬🔊

No code pushed today. Pure theory session:
- `<audio>` element: role = embed sound files natively in HTML
- `<video>` element: role = embed video files natively  
- `controls` attribute: adds play/pause/seek bar. No controls = dead media
- `src` attribute: tells browser where the media file lives, like `href` for links
- `autoplay` attribute: technically exists, but browsers block it. UX > dev ego 😂

Lesson: HTML ships with media players. We just have to learn the rules.

### The Concept That Clicked
Browsers already know how to play sound + video.  
My job as a dev is not to build a player from scratch. It is to ask the browser nicely using the right tags.



### Key Takeaways
1. **`controls` is mandatory**: Users need a way to interact. No controls = no user power
2. **`src` is the address**: Wrong path = no media loads. Same pain as broken links
3. **Browsers protect users**: `autoplay` gets blocked.

