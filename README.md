# zephyr-boards

Zephyr board definitions for platforms released by CSIRO DSS.

## Module Importing

Add the following values to your `west.yml` and run `west update`:
```
  remotes:
    - name: csiro-wsn
      url-base: https://github.com/csiro-wsn
  projects:
    - name: zephyr-boards
      remote: csiro-wsn
      revision: master
      path: modules/csiro/boards
```
