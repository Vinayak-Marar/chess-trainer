# Chess PGN Trainer

An online tool that opens chess PGN files and lets you drill through the moves — great for practicing tactics, puzzles, and openings. Load a PGN, and the app quizzes you move by move, tracking errors and time as you go.

This is a personal fork of [rodpolako/Chess-PGN-Trainer](https://github.com/rodpolako/Chess-PGN-Trainer), with a few additions:

- **Jump to puzzle** — jump directly to any puzzle number in a set instead of stepping through one by one
- **Mainline only** — option to strip out variations from a PGN and drill only the mainline
- Fixed asset paths for hosting as a GitHub Pages project site

## Features

- Upload or paste a PGN file and practice the moves interactively
- Auto-advance to the next puzzle, or use manual "Next" button mode
- Randomize puzzle order
- Play both sides, or play the opposite side (computer plays the first move)
- Auto-flip board orientation
- Track errors and time per session, export results to CSV
- Analyze any position on Lichess with one click
- Works fully offline in the browser — no account or server needed

## Usage

Just open `index.html` (or visit the hosted GitHub Pages link), load a PGN file, choose your options, and click Start.

## Credits

Built on top of the original [Chess-PGN-Trainer](https://github.com/rodpolako/Chess-PGN-Trainer) by rodpolako, licensed under the MIT License. See [LICENSE](./LICENSE) for details.

## License

MIT — see [LICENSE](./LICENSE).
