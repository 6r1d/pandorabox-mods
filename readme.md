# Pandorabox mods

[![Build Status](https://travis-ci.com/pandorabox-io/pandorabox-mods.svg?branch=master)](https://travis-ci.com/pandorabox-io/pandorabox-mods)

Pandorabox mod repo

## Install


After cloning:
```
git submodule init
git submodule update
```

## Updating

```
git submodule sync
git submodule init
git submodule update
```

## Advisable settings

```
# allow protection
areas.self_protection = true

# lightweight node timer-based interrupts
mesecon.luacontroller_lightweight_interrupts = true

# don't let the unified inventory show *all* slopes/slabs (use the table saw for that)
moreblocks.stairsplus_in_creative_inventory = false

# enable bridger trusses
bridger_enable_trusses = true

# enable telemosaic rightclick teleport
telemosaic_right_click_teleport = true
```