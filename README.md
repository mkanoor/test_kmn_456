# test_kmn_456
# Example Package

This is a simple example package. You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.

- Need pre-commit to run
  commitlint which is written in node.js

  commitlint can be installed using
  https://github.com/conventional-changelog/commitlint/blob/master/docs/guides-local-setup.md

  Configure commit lint to use conventional config

  npm install --save-dev @commitlint/{cli,config-conventional}
  echo "module.exports = { extends: ['@commitlint/config-conventional'] };" > commitlint.config.js

- pip install pre-commit
- pre-commit install-hooks
- pre-commit install --install-hooks --hook-type commit-msg
OR
- pre-commit install --install-hooks -t pre-commit -t commit-msg
