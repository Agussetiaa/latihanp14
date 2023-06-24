## Latihan pertemuan 14
## Sub Query

<img width="681" alt="image" src="https://github.com/Agussetiaa/latihanp14/assets/115542822/f00f2fb8-b743-487b-a63c-c893bf6e2cc5">

### • Tampilkan data karyawan yang bekerja pada departemen yang sama dengan karyawan yang bernama Dika =
```
SELECT *
```
```
FROM karyawan
```
```
WHERE id_dept = (
```
```
SELECT id_dept FROM karyawan
```
```
WHERE nama = 'dika');
```


![image](https://github.com/Agussetiaa/latihanp14/assets/115542822/e59ee4eb-be46-49e6-a330-64a1c1029f72)


### • Tampilkan data karyawan yang gajinya lebih besar dari rata-rata gaji semua karyawan. urutkan menurun berdasarkan besaran gaji =


![image](https://github.com/Agussetiaa/latihanp14/assets/115542822/dfda8331-b09f-440d-a82c-829b94e6a430)


### • Tampilkan nik dan nama karyawan untuk semua karyawan yang bekerja didepartment yang sama dengan karyawan dengan nama yang mengandung huruf 'K' =


![image](https://github.com/Agussetiaa/latihanp14/assets/115542822/5d8dcefa-efa1-437c-8ac0-13b500e5179a)


### • Tampilkan data karyawan yang bekerja pada departemen yang ada di kantor pusat. = 


![image](https://github.com/Agussetiaa/latihanp14/assets/115542822/431d8364-ba7e-41bf-bc6e-df23f00071c5)


### • Tampilkan nik dan nama karyawan untuk semua karyawan yang bekerja di department yang sama dengan karyawan dengan nama yang mengandung huruf 'K' dan yang gajinya lebih besar dari rata-rata gaji semua karyawan =


<img width="398" alt="image" src="https://github.com/Agussetiaa/latihanp14/assets/115542822/7f79565c-eaa8-48bd-85d0-79d81d10deea">

