# Electrooculography Dataset for Reading Detection in the Wild

Shoya Ishimaru, Takanori Maruichi, Manuel Landsmann, Koichi Kise and Andreas Dengel. “Electrooculography Dataset for Reading Detection in the Wild”. In Proceedings of the 2019 ACM International Joint Conference on Pervasive and Ubiquitous Computing: Adjunct Publication (UbiComp '19 Adjunct), to appear.

* [Paper PDF](https://shoya.io/preprint/ishimaru2019electrooculography.pdf)
* [Dataset (6.43GB)](https://www.dropbox.com/sh/rkcfr1qnxwpv0iy/AACszVEoX2imTUF7-itiGRora?dl=0)

## Dataset Overview

```
df = pd.read_csv("p1_d1.csv")
print(df.head())

>>    #timestamp                 date_time  left  right  acc_x  acc_y   acc_z  roll  pitch  yaw  label
0  1559781538485   2019-06-06 09:38:58.485   192    -10  -3245   7176  -14602  1657    507  532      0
1  1559781538493   2019-06-06 09:38:58.493   189    -13  -3127   7091  -14485  1556    501  512      0
2  1559781538500   2019-06-06 09:38:58.500   185    -16  -3205   7107  -14545  1502    515  458      0
3  1559781538516   2019-06-06 09:38:58.516   182    -21  -3113   7059  -14653  1448    532  425      0
4  1559781538523   2019-06-06 09:38:58.523   168    -30  -3099   7006  -14673  1381    527  397      0
```

## Label
* 0: Not reading
* 1: Reading English
* 2: Reading Japanese horizontal
* 3: Reading Japanese vertical