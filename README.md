Addition game files for (fallout1-ce/kiosk)[https://github.com/byfanforfun/fallout1-ce/tree/kiosk]

```
cat msg/KIOSK.MSG | iconv -t CP1251 | sed "s/$/`echo -e \\\r`/" -- > text/english/game/KIOSK.MSG
```

