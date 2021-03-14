## Ariyo Atmojo 1184056
## Expert System
Sistem pakar generik untuk menghasilkan aturan dan membuat hubungan antara entri dan basis pengetahuan. Diimplementasikan menggunakan Forward Chaining dan Backward chaining. clauses harus terkait dengan basis Pengetahuan atau tidak akan masuk akal saat dijalankan. Parser dibuat untuk mengurai file json dan membuat objek pada waktu proses.

----------------------------------
### Result
* Backward Chaining
```console
Chankya >>> Tell me some features of this bird?
You >>> high flight, strong legs, yellow legs
[DEBUG] Target :: Falcons, Eagles --->  Matched :: 33.33333333333333

[INFO] I am not sure if this is the bird Falcons, Eagles
[INFO] Hope that you are satisfied with your answers !
```

* Forward Chaining
```console
Chankya >>> Tell me some features of this bird?
You >>> high flight, strong legs, yellow legs
[DEBUG] Target :: Falcons, Eagles --->  Matched :: 33.33333333333333
[DEBUG] Target :: Peacock --->  Matched :: 0.0
[DEBUG] Target :: Hen --->  Matched :: 0.0
[DEBUG] Target :: Albatrosses --->  Matched :: 0.0
[DEBUG] Target :: Paradise birds --->  Matched :: 0.0
[DEBUG] Target :: Crows --->  Matched :: 0.0
[DEBUG] Target :: Cuckoos --->  Matched :: 0.0
[DEBUG] Target :: Ducks, Geese and Swans --->  Matched :: 0.0

[INFO] I am not sure if this is the bird Falcons, Eagles
[INFO] Hope that you are satisfied with your answers !
```
