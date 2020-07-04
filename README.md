# gwaff

![record-xp-data](https://github.com/bwac2517/gwaff/workflows/record-xp-data/badge.svg)

A mee6 xp graphing python program using matplotlib

To use it for your own server, fork it and edit the config.yml

```
server_id: 377946908783673344 # your server id
plot_range: 60 # how many uses to include in the plots
data_range: 300 # -1 for all users. how many people to include in data collection
minium_xp: 500 # anyone with a xp gain below this will not be included in the plots
darkmode: true # dark mode or not
```

run store.py everyday, and you use plot.py every 2 days.
![(we use a github action for this)](https://github.com/bwac2517/gwaff/blob/master/.github/workflows/main.yml)
Hack to taste
