# Mac-Hack

## Kapat kapatıldığında kapanan 2. ekran çözümü
- Bekleme süresi öğrenme
```
pmset -g I grep hibernatemode
```

- Beklemeyi Kapatma
```
sudo pmset -a sleep 0
sudo pmset -a hibernatemode 0
sudo pmset -a disablesleep 1
```



* Sorumluluk sizde 
