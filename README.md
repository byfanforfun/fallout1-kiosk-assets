Addition game files for [fallout1-ce/kiosk](https://github.com/byfanforfun/fallout1-ce/tree/kiosk)

Put files from `game` directory to fallout1-ce root


```
cat msg/KIOSK.MSG | iconv -t CP1251 | sed "s/$/`echo -e \\\r`/" -- > game/text/english/game/KIOSK.MSG
```

