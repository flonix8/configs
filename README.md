# configs
My personal notes around user-level Linux config.

## Convenient SSH key encryption
(Source: https://stackoverflow.com/a/24902046)
- Install `keychain`
- Add to `~/.bashrc`:\
  `eval $(keychain -q --timeout 60)`
- Add to `~/.ssh/config`:\
  `AddKeysToAgent yes`