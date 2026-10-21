HOW TO ADD A CAR REVVING SOUND
================================

The game already works great with synthesized Web Audio API sounds.
But if you want a real car engine rev sound for the driving, follow these steps:

1. Find a short car engine rev / idle loop MP3 file (1-5 seconds, loopable).
   Good sources: freesound.org, zapsplat.com, pixabay.com (all free)

2. Name the file exactly:
      rev.mp3

3. Place it in this folder:
      E:\Sangu_College\Fun\assets\rev.mp3

4. Open index.html on your phone or browser — the engine sound will
   automatically play when you press the DRIVE button!

TIPS:
- The file should loop cleanly (no pop at start/end).
- Keep file size small — under 200KB for best mobile performance.
- The game gracefully falls back to synthesized audio if the file is missing
  or cannot be loaded, so it's completely optional.
