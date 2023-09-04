[quickscss]:    https://github.com/Saltssaumure/QuickSCSS
[generate]:     https://github.com/Saltssaumure/QuickCSS/generate

# QuickCSS

A [QuickSCSS][quickscss] usage template, for compiling SCSS and synchronising Custom/Quick CSS across multiple Discord client mods.

## Usage
1. [Create a copy of this template][generate].
2. Clone your copy to your computer.
3. Install dependencies with `pnpm i`.
4. Edit the contents of `scss/` to your liking.
5. Run `pnpm build` to compile once, or `pnpm watch` to compile on file changes.

## Notes
- File structure inside `scss/` is a suggestion only, only `main.scss` is required.
- This will overwrite your existing custom/quick CSS, so make sure to back it up first.