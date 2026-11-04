# EO1 Remote

Control an Electric Objects EO1 running EO1bian from anywhere, through its GitHub gallery repository.

Open **https://speville.github.io/eo1/** on your phone, add it to the home screen, and sign in with your
gallery repository (`you/eo1-gallery`) and a fine-grained token that may only read and write that repository.
The token stays in your phone's browser and is only sent to GitHub (api.github.com).

Changes are commits to your gallery: `control.json` (screen, brightness, schedule, time per picture, titles),
`gallery.json` (albums, hidden pictures) and pictures in `images/Phone/`. GitHub builds the gallery and the EO1
follows at its next check, within about 5-10 minutes. For live control (next/previous, the live picture) use
the EO1's own control page, at home or through Tailscale.

A single static page, no server, no tracking. Part of the EO1bian project.
