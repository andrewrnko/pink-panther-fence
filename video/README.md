# Hero video

`hero-loop.mp4` (720x1280, 12.9s, muted, no audio track) is a montage cut from the
crew's own Instagram reels in `public/ig/` (DdjvmLCNV0x, DdE-zpuPnyR, DdmaEesPNKJ).
Clips with a readable old-brand shirt (Elite Yard) were left out on purpose. Real Elite / Pink Panther Fencing crew only. No stock, no AI.
`hero-poster.jpg` is its first frame.

TODO (Andrew): replace with native footage shot for the site. Wanted: crew on a
job, posts going in, a panel going up, the vans pulling out. 16:9, 1080p or 4K,
10 to 15s, no audio needed. Export H.264 under ~4MB and keep the same file names
so `src/components/Hero.tsx` needs no change. The Instagram source is 720 wide,
so on desktop it is upscaled 2x behind the gradient; native footage fixes that.
