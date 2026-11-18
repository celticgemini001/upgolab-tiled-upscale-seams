# Tiled Upscaling Seams: How Much Context a Tile Actually Needs

Zero-context tiling put 0.45% of pixels more than 2 levels off, 68% of them within 2 px of a tile boundary. Three pixels of context made every tile size bit-identical at 2x; at 2.7x the same tiler is wrong at all six tile sizes and the error has no seam in it.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-tiled-upscale-seams/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
