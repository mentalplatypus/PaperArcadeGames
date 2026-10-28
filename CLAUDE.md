# Paper Arcade

Small browser games in a shared graph-paper style. Each game is one self-contained `index.html` in its own folder (`snake/`, `tictactoe/`, `minesweeper/`, `ruler/`, `sudoku/`, `dots/`). The root `index.html` is the collection page, with one card per game.

- Repository: https://github.com/mentalplatypus/PaperArcadeGames (public, branch `main`)
- Live site: https://mentalplatypus.github.io/PaperArcadeGames/ (GitHub Pages redeploys on every push to `main`)

## Status

Finished as of October 2026, with six games. The collection page has no "coming soon" placeholder; the games fill two rows of three.

The project is listed under "Finished projects" on the home page (https://mentalplatypus.github.io/, repo `mentalplatypus/mentalplatypus.github.io`, branch `master`), and the collection page's byline links back to it. If a game is ever added or renamed, also update the game tags on the home page's Paper Arcade card.

## Git workflow (required)

Commit and push regularly as you work, so no progress is ever lost and any change can be reverted.

- **Commit each logical change as soon as it works.** One feature or fix per commit; don't batch unrelated changes.
- **Push right after committing.** Work that exists only on this machine isn't saved.
- **Write clean commit messages:** a short imperative subject line (under about 60 characters, e.g. "Add restart option to Sudoku"), plus a body when the reason or behavior isn't obvious from the subject.
- **Check before committing:** run `git status` and `git diff` so only intended files go in.
- **Pushes go live.** Only push finished, working changes to `main`. Put experiments on a separate branch first.
- Never rewrite history that's already pushed (no force-push, no amending pushed commits). Revert with a new commit instead.

## Adding a game

1. Create a folder with an `index.html`, reusing the shared design tokens, fonts, light/dark themes and synthesized sounds from the existing games.
2. Give it a `← All games` link to `../index.html`.
3. Add a card (with a canvas thumbnail) to the root `index.html` and a line to the games list in `README.md`. Keep `README.md` visitor-facing: no build or editing notes.
4. Commit and push.
