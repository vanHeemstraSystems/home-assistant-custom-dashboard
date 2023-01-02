# 100 - Project Setup

## 100 - Getting Started

Based on "Getting Started" at https://github.com/shannonhochkins/ha-dashboard

Add the following to your ```configuration.yaml``` file in Home Assistant:

```
panel_custom:
  - name: react-panel-dev
    sidebar_title: React Panel
    sidebar_icon: mdi:react
    url_path: react-panel-dev
    js_url: http://0.0.0.0:8080/main.js
    embed_iframe: true
    config:
      name: World
```

Restart Home Assistant.

More ...
