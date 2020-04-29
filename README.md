# Speedtest Logger

Simple `cron` script to log results from the Speedtest CLI for historical ISP internet speed information.

# Installation

Clone this repo to `~/.speedtest` and setup the `crontab` entry.

## Every Quarter Hour Example

Here is a crontab entry which will run this test every quarter hour:

```
0/15 * * * * ~/.speedtest/run
```

## Assumptions

This repo assumes you have installed the Speedtest CLI script to `/usr/local/bin/speedtest` and that results are stored in `~/.speedtest` directory.
