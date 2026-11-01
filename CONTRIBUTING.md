# Contributing

Thank you for taking a look. Before you write code, please open an issue so we can agree on the
change first: it saves both of us time.

## Pull requests

- Keep each pull request to one change, with a short description of what and why.
- Run the project's checks before you open it. For PEEPWICK Browser:

  ```bash
  npm ci
  npm run typecheck
  npm test
  cargo test --manifest-path src-tauri/Cargo.toml
  ```

- Match the style of the code around your change.
- Interface text exists in Turkish and English. If you add a string, add it to both, without
  exclamation marks, in a calm and plain voice.

By contributing you agree that your work is released under the project's license (GPL-3.0 for
PEEPWICK Browser). The PEEPWICK name and logo are not covered by that license.
