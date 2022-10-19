# 10219050
Alif K.M Akbar Wibowo


## materi sebelumnya
- Persamaan Predator-Prey: persamaan yg menggambarkan hubungan populasi predator dan mangsa
- Metode Euler: metode numerik dengan metode Euler
- Metode Runge Kutta: metode numerik utk integrasi dengan aproksimasi runge kutta
- persamaan gaya lorentz terkopel: partikel yang terkopel antara kecepatan pada sumbu y dan x
- Osilasi harmonik sederhana dan terkopel: menurunkan persamaan untuk kasus overdamped, critically damped, dan underdamped
- Monte Carlo: merode range rejection untuk sampling method
- Transformasi Fourier: mengubah domain waktu menjadi domain frekuensi


## materi paling menarik
+ Tuliskan materi yang paling menarik yang telah diberikan dan jelaskan mengapa menarik.
- Menurut saya pribadi, materi paling menarik adalah transformasi Fourier karena terdapat pattern seeking, mengisolasi batas fungsi, 
  dan mengubah persamaan yang basisnya waktu menjadi frekuensi

## materi paling membosankan
+ Tuliskan materi yang telah diberikan yang paling membosankan dan jelaskan alasannya.
- yang paling membosankan adalah persamaan predator prey, karena ya begitu aja sih

## materi yang sudah dipami
+ Tuliskan materi-materi yang telah dipahami.
- yang paling saya pahami adalah Monte Carlo dan heat diffusion

## materi yang belum dipahami
+ Tuliskan materi-materi yang masih belum dipahami dan bagian mana yang belum serta ingin dipahami.
- untuk yang osilasi, masih belum memahami array-array yang digunakan

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





## cara perkuliahan
+ Tuliskan pendapat Anda mengenai cara perkuliahan selama ini dan cantumkan usulan untuk perkuliahan setelah UTS.
- Menurut saya jujur kurang efektif karena kurangnya mencoba coba di kelas karena kendala kurangnya koneksi, saran saya adalah kalau bisa memperbanyak waktu di comlabs

## topik sistem fisis
+ Tuliskan sistem fisis yang menarik bagi Anda untuk dikaji lebih dalam dan jelaskan alasannya mengapa.
- Saya pribadi ingin melihat sistem mesin mobil, seperti sequence untuk nozzle, piston, dan camshaft

## simulasi dan visualisasi
+ Apakah Anda tertarik dengan simulasi dan visualisasi? Jelaskan topik yang ingin Anda simulasikan / visualisasikan serta cantumkan alasannya dan perkiraan pusataka Python yang perlu digunakan.
- saya ingin menyimulasikan quantum entanglement yang terganggu dalam noise. Mungkin memerlukan qutip karena melibatkan mekanika quantum
