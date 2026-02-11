# ❄️ TRMNL Bergfex Snow Report

Show your favouring ski resorts status on your [TRMNL](https://usetrmnl.com/)

<img src=docs/trmnl_obertauern.png  />

## Installation

**This plugin requires Home Assistant to work.**

- Install [Bergfex Snow Report Integration](https://github.com/timmaurice/bergfex).
- Get Webhook URL from plugin page on your TRMNL website.
- Add new resort using Home Assistant integration. On last step, you can also put Webhook URL from TRML


## FAQ

### Why Home Assistant?

AFAIK Bergfex does not expose any public API, so we can ony scrape data manually.

### Data field is missing for my resort

Please check if Bergfex website provide this data for given resort. Various resorts have different data available. It is on my TODO list to make data fetching more flexible.
