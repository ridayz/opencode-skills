# opencode-skills

Kumpulan skill OpenCode. Cara pakai di PC baru: copy folder skill ke
`<project>/.opencode/skills/` atau `~/.config/opencode/skills/`.

## Skill buatan sendiri

- `ui-ux-pro-max/` — standar desain lokal (master). Copy aktif juga live di
  `Default Project/.opencode/skills/ui-ux-pro-max/` (digabung dengan upstream).

## Skill pihak ketiga (install sebagai plugin, bukan file di sini)

| Skill | Sumber | Cara install | Status |
|---|---|---|---|
| superpowers (brainstorming, systematic-debugging, TDD, dsb — 16 skill) | `obra/superpowers` | `"plugins": ["superpowers@git+https://github.com/obra/superpowers.git"]` di global `opencode.jsonc` | ✅ aktif |
| understand-* (understand, -chat, -dashboard, -diff, -domain, -explain, -figma, -knowledge, -onboard) | `Egonex-AI/Understand-Anything` | `install.ps1 opencode` → junction di `~/.agents/skills` | ✅ aktif |
| ui-ux-pro-max (+ design, banner-design, ui-styling, design-system, slides, brand) | `nextlevelbuilder/ui-ux-pro-max-skill` | `npx ui-ux-pro-max-cli init --ai opencode --force` di folder project | ✅ aktif |

Catatan: `ui-ux-pro-max` upstream menimpa `SKILL.md` lokal saat `--force`;
aturan lokal disimpan di bagian "Local overrides (ridayz)" di file yang sama
dan master-nya tetap `ui-ux-pro-max/SKILL.md` di repo ini.
