# EzraLopez (GitHub profile repo)

The README here shows on github.com/EzraLopez.

- `.github/workflows/skyline.yml` redraws `skyline.svg` nightly (neon theme, 26 weeks) and force-pushes it to the `output` branch. The README links the raw file there.
- skyline and setup-go are pinned to reviewed commit SHAs because the job can write to the repo. To upgrade, read the new skyline source first, then bump `SKYLINE_REF`. Never use `@latest`.
- To change the look, edit `-theme`/`-weeks` in the run line. Themes: neon, synthwave, matrix, amber, ice, sunset, toxic, vapor, crimson, mono, prism, rainbow.
