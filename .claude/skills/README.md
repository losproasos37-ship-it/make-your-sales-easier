# Project skills

Claude Code skills vendored into this project. Each subdirectory with a
`SKILL.md` is auto-discovered and usable by name in Claude Code.

## Installed

### Design / taste (from [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill), MIT)
- `taste-skill` (`design-taste-frontend`) — anti-slop frontend art direction for landing/marketing pages.
- `taste-skill-v1`, `taste-skill-v2-experimental` — older variants, kept for compatibility.
- `image-to-code-skill` (`image-to-code`) — generate a design image, analyze it, then build the page to match.
- `redesign-skill` (`redesign-existing-projects`) — upgrade an existing site to premium quality.
- `brandkit` — brand-guidelines / logo-system image generation.
- `imagegen-frontend-web`, `imagegen-frontend-mobile` — design-reference image generation (web / mobile).
- `soft-skill` (`high-end-visual-design`), `minimalist-skill`, `brutalist-skill`, `gpt-tasteskill`, `stitch-skill` — style systems.
- `output-skill` (`full-output-enforcement`) — enforce complete, non-truncated code output.

### Front-end design checklist (from [thedaviddias/Front-End-Design-Checklist](https://github.com/thedaviddias/Front-End-Design-Checklist), CC0)
- `front-end-design-checklist` — exhaustive design/front-end review checklist (see `checklist.md`).

### Brand design systems (from [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md), MIT)
- `awesome-design-md` — 84 real-world brand design systems as `DESIGN.md` references (see `SKILL.md` for the index).

## Not vendored: gstack

[garrytan/gstack](https://github.com/garrytan/gstack) (the "find bugs / review / `/qa` / `/cso`"
toolkit) is a ~76 MB Bun/TypeScript framework whose skills depend on its own CLI
(`bun run gstack ...`) and a global install, so it is intentionally **not** copied
into this repo. Install it the way its author intends, on your own machine:

```sh
git clone --single-branch --depth 1 https://github.com/garrytan/gstack.git ~/.claude/skills/gstack \
  && cd ~/.claude/skills/gstack && ./setup
```

Requires Git, [Bun](https://bun.sh/) v1.4.2+, and Claude Code. After setup, its
skills (`/review`, `/qa`, `/investigate`, `/cso`, `/ship`, etc.) are available
globally in Claude Code. See the gstack README for options.
