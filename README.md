# Learning extra a11y stuff

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Based off of a [Zeitspace A11y Workshop](https://github.com/zeitspace/web-accessibility-session)

These are just select notes for my own idiosyncrasies/situation.

Ontario: AODA: company > 50:
  - -> 2014: must have WCAG 2.0 Level A
  - -> 2021: must have WCAG 2.0 Level AA

WCAG **_"quick ref"_**: <https://www.w3.org/WAI/WCAG21/quickref>

My other notes: <https://github.com/hchiam/web-accessibility-course-notes>

## To practice/research later

Example: <https://github.com/hchiam/learning-extra-a11y-stuff/blob/master/src/index.html> (`yarn; yarn start;`). Or live demo: <https://hchiam-a11y-test.surge.sh/>

- Perceivable
  - -> web video add text: <https://www.w3schools.com/tags/tag_track.asp>
- Operable
  - -> skip links
- Understandable
  - -> "Read more" link with screenreader-only audible extra "Read more about (...)"
- Robust
  - -> research lighthouse compatibility IE checks (I don't think so. Just use an actual IE browser. If you're for some reason really stuck with a Mac, try [IE Tab](https://chrome.google.com/webstore/detail/ie-tab/hehijbfgiekmjfkfjpbkbammjbdenadd?hl=en-US) to simulate IE in Chrome, but requires extra installation and sign-up.)

Write down: Don't just sketch! Sketch _semantic_ blocks! At the start!

Try out [a11y-friendly drag and drop](https://www.smashingmagazine.com/2018/01/dragon-drop-accessible-list-reordering/): use [Dragon Drop](https://schne324.github.io/dragon-drop/demo/) with `yarn add drag-on-drop` or `https://unpkg.com/drag-on-drop`.

---

## Other notes

[![generator-hchiam-learning](https://img.shields.io/badge/built%20with-generator--hchiam--learning-brightgreen.svg)](https://github.com/hchiam/generator-hchiam-learning) 

You can generate a [dependency graph](https://github.com/hchiam/learning-dependency-cruiser) with `npm run deps` (which runs `bash show_dep_graph.sh`).

You can publish a live site to [surge](https://github.com/hchiam/learning-surge) with `bash publish_live_site.sh` (Just go into the relevant enclosing `src` or `public` folder of your site files - a CNAME file is there for convenience).

You can zip the current folder with `npm run zip`.

This file was first created using the Yeoman generator [`generator-hchiam-learning`](https://www.npmjs.com/package/generator-hchiam-learning).
