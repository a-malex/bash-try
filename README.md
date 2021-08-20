# dws-dev-006-bash

This script use to run every commands by retry multiple times in failure in differnt intervals that you set.

You can set number of retries by pass `-n` option and also set wait time between each try by passing `-i` value.

This program support **environment values**. You can pass `TRY_NUMBER` and `TRY_INTERVAL` in your environment and this program use them.

If no options pass to this script or no envirinment variable set for it, this script use its default values that listed in below.

## Default Values
```
DEFAULT_INTERVAL=5
DEFAULT_NUMBER=12
```

## Environment Values
```
TRY_NUMBER
TRY_INTERVAL
```

## Requirements
- bash or sh in terminal environment

## Installation
- `git clone git@github.com:a-malex/dws-dev-006-bash.git`
- `cd dws-dev-006-bash`
- `chmod +x try`

## Example
- `./try flask app test`
- `./try -n 5 -i 2 flask app test`

[@dwsclass](https://github.com/dwsclass) dws-dev-006-bash
