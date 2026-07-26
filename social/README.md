# social/

MP4 drop zone for the autoposter (`ryaano/deodorant-man-social`).

GitHub Pages serves everything here at `https://deodorantmangame.com/social/<file>.mp4`,
which is the URL each platform poster downloads from. Push a clip here
BEFORE the queue file that references it goes live, or the post 404s —
`node scripts/validate.mjs` in the autoposter repo HEAD-checks every URL
to catch exactly that.

Naming: `stink-check-<nnn>.mp4`, matching the queue file slug.

Keep clips 8-10s, vertical 9:16, under ~10MB. Fully-posted clips can be
deleted here once all four platform flags are true — the platforms hold
their own copies.
