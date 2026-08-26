# NLNAM Pitch

A short lightning talk introducing **NLNAM** — the **N**ether**L**ands **N**etwork **A**utomation **M**eetup — and how to get involved.

The goal of the talk is simple: you walk away knowing what NLNAM is, what we talk about, and how to attend, speak, or host.

> NLNAM is a volunteer-run community for network engineers, DevOps folks, automationeers and developers in the Netherlands. Free to attend, open stage, all experience levels welcome.
>
> **https://net-auto.nl/**

## Contents

| Path | What it is |
| --- | --- |
| `NLNAM_a_home_for_network_automation.md` | The deck itself — a [Marp](https://marp.app/) presentation in Markdown |
| `template/` | Logos, meetup photos, QR code and the closing-slide background |
| `Taskfile.yml` | Build tasks ([Task](https://taskfile.dev/)) for exporting and presenting |

Speaker notes live in HTML comments inside the Markdown, with rough timings per slide.

## Building it

Requires [Marp CLI](https://github.com/marp-team/marp-cli) and [Task](https://taskfile.dev/).

```bash
task            # list available tasks
task present    # live preview at http://localhost:8080/
task export:pdf # write export/NLNAM_a_home_for_network_automation.pdf
task export:pptx
```

Exports land in `export/`, which is not tracked.

## Design notes

The deck uses a Dutch flag palette — red `#AE1C28`, white, blue `#21468B` — matching the NLNAM logo. Red is kept as an accent (heading rules, table underline, QR border) rather than large filled areas, so it doesn't overpower the content.

The closing slide uses a tongue-in-cheek "I was in NAM, network automation" cartoon as its background, under a dark overlay. It's a joke about the acronym.

## Credits

Talk by Bart Dorlandt — freelance network automation solution architect, co-organizer of NLNAM.

NLNAM was started with Dan Peachey, after an idea over breakfast at AutoCon 3 in Prague, 2025.
