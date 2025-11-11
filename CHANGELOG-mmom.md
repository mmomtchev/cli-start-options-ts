# Change log for the @mmomtchev fork

Changes in reverse chronological order.

Refer to GitHub [issues](https://github.com/xpack/cli-start-options-js/issues/).

## 2025-11-11

- Replace both path separators on all OS to fix the (harmless) Windows error `ENOENT: no such file or directory, open 'C:\Users\...\.config\timestamps\@mmomtchev\xpm-update-check'`

## 2025-06-17

- Fix `log.warning is not a function` message when running `xpm` without Internet connection

## 2025-06-09

- Use a dynamic import for Node 18 compatibility

## 2025-06-09

- Fix timestamp file creation for scoped packages
