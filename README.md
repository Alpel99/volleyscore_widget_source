# Volleyscore Live Widget

A lightweight, dependency-free embeddable widget that displays live volleyball match scores from **volleystation.com**.  
Built using plain **HTML + JavaScript**, and easy to embed into **any website, OBS overlay, or scoreboard view**.

Made in one evening with a bunch of ai, might not work sometimes.

## Features

- ✅ Auto-fetches **live match data** from a selected league  
- ✅ Supports **team and league filtering** via URL parameters  
- ✅ Works with **real team logos** *or* falls back to **initial-based placeholders**  
- ✅ Auto-refreshes in the background  
- ✅ Designed for **easy iframe embedding** or direct HTML hosting  
---

## Usage

### This is hosted on github pages as
`https://alpel99.github.io/volleyscore_widget_source/`

## Example

[`https://alpel99.github.io/volleyscore_widget_source?leagueId=20&team=Favoriten&notLive=1`](https://alpel99.github.io/volleyscore_widget_source?leagueId=20&team=Favoriten&notLive=1)

## Usage/Parameters

You can customize behavior using URL parameters:

| Parameter        | Description                         | Example        |
|------------------|-------------------------------------|----------------|
| `leagueId`       | Select league ID (required)         | `?leagueId=20` |
| `team`           | Team name (also matches parts)      | `?team=VC Sim` |
| `league`         | Filter by league name (optional)    | `?league=HLL`  |
| `refresh`        | Auto-refresh interval in seconds    | `?refresh=15`  |
| `showHeader=1`   | Standard: table header hidden       | `?showHeader=1`|
| `notLive=1`      | Standard: only scrapes live games   | `?onlyLive=1` |

## League ID
This is from volleyscore, important league IDs for austria:
* 20 WVV - Wiener Landesliga
* 18 OVV - Austrian Volley League (1, 2, Men&Women)


