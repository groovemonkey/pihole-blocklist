# Experimental pi-hole blocklist

The goal for this blocklist is to block pesky domains that the most popular blocklists don't catch. I'm building this for my own use, so if it breaks something for you, you'll have to fix it yourself.

## Current State
This is a brand-new, experimental blocklist. As a starting point, I'm using the hosts listed on the [d3ward tools page](https://d3ward.github.io/toolz/adblock.html), but my intent is to grow this list beyond that. I assume that site does a kind of spot-check, and shouldn't be used as a single source of truth for a domain blocklist.

## How to use

1. Log into your pi-hole web frontend.
1. Navigate to the blocklists page (http://PI_HOLE_IP/admin/groups-adlists.php)
1. Add `https://raw.githubusercontent.com/groovemonkey/pihole-blocklist/main/blocklist`

