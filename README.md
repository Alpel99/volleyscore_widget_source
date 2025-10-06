# Volleyscore Live Widget

A lightweight, dependency-free embeddable widget that displays live volleyball match scores from **volleystation.com**.  
Built using plain **HTML + JavaScript**, and easy to embed into **any website, OBS overlay, or scoreboard view**.

Made in one (now two) evening with a bunch of ai, might not work as expected sometimes.

## Features

- ✅ Auto-fetches **live match data** from a selected league  
- ✅ Supports **team and league filtering** via URL parameters  
- ✅ Works with **real team logos** *or* falls back to **initial-based placeholders**  
- ✅ Auto-refreshes in the background  
- ✅ Designed for **easy iframe embedding** or direct HTML hosting  

## Usage

### This is hosted on github pages as
`https://alpel99.github.io/volleyscore_widget_source/`

## Example

### some past game (mainly for testing purposes)
[`https://alpel99.github.io/volleyscore_widget_source?leagueId=20&team=Favoriten&notLive=1`](https://alpel99.github.io/volleyscore_widget_source?leagueId=20&team=Favoriten&notLive=1)


### next game
[`https://alpel99.github.io/volleyscore_widget_source?leagueId=20&team=Favoriten`](https://alpel99.github.io/volleyscore_widget_source?leagueId=20&team=Favoriten)

## Usage/Parameters

You can customize behavior using URL parameters:

| Parameter        | Description                         | Example        |
|------------------|-------------------------------------|----------------|
| `leagueId`       | Select league ID (required)         | `?leagueId=20` |
| `team`           | Team name (also matches parts)      | `?team=VC Sim` |
| `league`         | Filter by league name (optional)    | `?league=HLL`  |
| `refresh`        | Auto-refresh interval in seconds    | `?refresh=15`  |
| `showHeader=1`   | Standard: table header hidden       | `?showHeader=1`|
| `noLogo=1`       | Standard: show team logo/inital     | `?noLogo=1`    |
| `notLive=1`      | Testing only: scrape finished game  | `?onlyLive=1`  |


## Game query structure:
* check for any live game with the teamname
* check for any upcoming game with the teamname


* if notLive is activated (should only be used for testing)
    * show some previously played game

## League ID
This is from volleyscore, important league IDs for austria:
* 20 WVV - Wiener Landesliga
* 18 OVV - Austrian Volley League (1, 2, Men&Women)



## How to use on mobile stream
* install PRISM live
* setup normal stuff
* in main view: swipe right for studio/settings
    * tap on widget
    * tap on web
    * add the according url & give title
    * click on save
* icon with title appears in studio
    * click on this icon to add to scene
    * position whereever you want

* to add a space " " to the teamname add "%20" instead
    * your browser replaces this automatically, the prism source does not


## Attribution Requirement

If you use this score widget in a livestream or public broadcast, you must provide visible credit by mentioning or linking to the original GitHub repository (e.g. in the stream description, overlay, or credits section).
Example: "Score widget provided by https://github.com/Alpel99/volleyscore_widget_source"