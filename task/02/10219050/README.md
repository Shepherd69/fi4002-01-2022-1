# 10219050
Alif K.M Akbar Wibowo


## materi sebelumnya
+ Tuliskan materi-materi sebelumnya yang telah diberikan dalam kuliah ini.
- predator prey
- euler
- runge kutta
- lorentz terkopel
- osilasi harmonik sederhana dan terkopel
- transformasi fourier
- monte carlo
- heat diffusion

## materi paling menarik
+ Tuliskan materi yang paling menarik yang telah diberikan dan jelaskan mengapa menarik.
 yang menarik adalah transformasi fourier karena melibatkan perubahan domain waktu jadi frekuensi

## materi paling membosankan
+ Tuliskan materi yang telah diberikan yang paling membosankan dan jelaskan alasannya.
- predator prey karrna ya gitj aja sih

## materi yang sudah dipami
+ Tuliskan materi-materi yang telah dipahami.
- monte carlo, heat diffusion

## materi yang belum dipahami
+ Tuliskan materi-materi yang masih belum dipahami dan bagian mana yang belum serta ingin dipahami.
- osilasi harmonik, belum paham array nya

## contoh program
+ Buat suatu contoh program dalam Python dan sertakan di sini dengan hasil keluarnnya.

```python
# contoh program python

import matplotlib.pyplot as plt
import random

inside = 0
n = 100
i = 0

x_ins = []
y_ins =[]
x_out = []
y_out = []
 
for inside in range (n):
  x = random.uniform [-10.0,10.0]
  y = random.uniform [-10.0,10.0]
  if x**2 + y**2 <= 100:
   inside += 1
   x_ins.append(x)
   y_ins.append(y)
  else:
   x_out.append(x)
   y_out.append(y)

fig, ax = plt.subplots()
ax.set_aspect('equal')
ax.scatter(x_ins, y_ins, color='g', marker='s')
ax.scatter(x_out, y_out, color='r', marker='s')

plt.draw()

Hasilnya adalah

```
```


## cara perkuliahan
+ Tuliskan pendapat Anda mengenai cara perkuliahan selama ini dan cantumkan usulan untuk perkuliahan setelah UTS.
- mungkin kurang efektif karena kurangnya nyoba nyoba karena kendala perangkat dan koneksi, harapannya bisa di comlabs terus

## topik sistem fisis
+ Tuliskan sistem fisis yang menarik bagi Anda untuk dikaji lebih dalam dan jelaskan alasannya mengapa.
- sistem mesin mobil seperti sequence untuk nozzle, piston, dan camshaft

## simulasi dan visualisasi
+ Apakah Anda tertarik dengan simulasi dan visualisasi? Jelaskan topik yang ingin Anda simulasikan / visualisasikan serta cantumkan alasannya dan perkiraan pusataka Python yang perlu digunakan.
- quantum entanglement dalam noise, mungkin perku 
