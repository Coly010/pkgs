---
"@swc/cli": major
---

Update chokidar to v5

This update resolves peer dependency conflicts in repositories that use both @swc/cli and Angular, as Angular now uses chokidar v5.

BREAKING CHANGE: Minimum Node.js version bumped from 16.14.0 to 20.19.0 to match chokidar v5's requirements.
