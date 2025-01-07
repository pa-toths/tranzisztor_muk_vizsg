# Tranzisztor működésének vizsgálata
---  
- Mérést végezte: Tóth Sándor
- Mérés helye: Villamos 3 labor
- Időpont: 2025.01.07.

---
## Méréshez használt eszközök / berendezések:
- NI Mydaq: 304591A SN
- Metex M-3800: 736015
---

## A mérés folyamata:
>   Az NI myDAQ műszer segítségével vizsgáltam a tranzisztor működését. A mérési áramkörben elhelyezett tranzisztor bázisához egy ellenálláson keresztül vezérlőjelet adtam. A vizsgálat során az emitter- és kollektoráramokat elemeztem, majd a kollektor-ellenálláson mért feszültség alapján következtettem a tranzisztor működésének állapotára és a vezérlőáram hatására. A mérések eredményeiből meghatároztam a tranzisztor erősítési tényezőjét és kapcsolási karakterisztikáját.

---

Kapcsolasi rajz:
https://tinyurl.com/256r4w2w
Megvalósítása :
![download](https://github.com/user-attachments/assets/01204c80-86e5-4baf-88ac-4cfb4f18fa27)


---

Ube=5V

| Ube (V) | URc (V)  | I (mA)   |
|---------|----------|----------|
| 0       | 0        | 0.000    |
| 0.5     | 0.003    | 0.014    |
| 0.6     | 0.113    | 0.514    |
| 0.7     | 0.9      | 4.091    |
| 0.8     | 2.3      | 10.455   |
| 0.9     | 2.63     | 11.955   |
| 1       | 2.65     | 12.045   |
| 1.5     | 2.73     | 12.409   |


A mérés során azt tapasztaltam hogy 1V felett az értékek szemmel láthatólag nem változnak.


