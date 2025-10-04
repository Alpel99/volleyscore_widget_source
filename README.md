# Volleyscore Live Widget

A lightweight, dependency-free embeddable widget that displays live volleyball match scores from **volleystation.com**.  
Built using plain **HTML + JavaScript**, and easy to embed into **any website, OBS overlay, or scoreboard view**.

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

`https://alpel99.github.io/volleyscore_widget_source?leagueId=20&team=Favoriten`

## Usage/Parameters

You can customize behavior using URL parameters:

| Parameter      | Description                         | Example        |
|----------------|-------------------------------------|----------------|
| `leagueId`     | Select league ID (required)         | `?leagueId=20` |
| `team`         | Team name (also matches parts)      | `?team=VC Sim` |
| `league`       | Filter by league name (optional)    | `?league=HLL`  |
| `refresh`      | Auto-refresh interval in seconds    | `?refresh=15`  |
| `hideHeader=1` | Hides table header row              | `?hideHeader=1`|
| `checkLive=0`  | Do not check only for LIVE games    | `?checkLive=0` |

## League ID
This is from volleyscore, important league IDs for austra:
* 20 WVV - Wiener Landesliga
* 18 OVV - Austrian Volley League (1, 2, Men&Women)


