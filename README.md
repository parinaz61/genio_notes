# genio_notes
## Overview
This project provides functionality to resolve differences between two versions of a `Lecture` object, one from a local source and one from a remote source. The resolution logic combines conflicting data and ensures consistency across both versions.

## Features
- Combines conflicting lecture names and note text using a slash (`/`).
- Resolves conflicting timestamps by prioritizing the remote version.
- Handles notes with unique IDs from both local and remote lectures.
- Includes unit tests to verify the resolution logic.
