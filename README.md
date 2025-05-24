### 📚 Pertemuan ke-11 mata kuliah Topik Khusus

# Docker Compose

## 1. Build Element

```bash
cd build_element/
```

### Build

```bash
docker compose build
```

![ss](./screenshot/1.png)

### Jalankan compose

```bash
docker compose up
```

![ss](./screenshot/2.png)

### Lihat compose yg berjalan

```bash
docker compose ps
```

![ss](./screenshot/3.png)

### Cek Hasilnya

Berdasarkan Dockerfile di `build_element`, semua hile .html dimasukkan, sehingga kita bisa cek, disini `/about.html` dari port `8080` (berdasarkan pengaturan di `docker-compose.yml`)

![ss](./screenshot/4.png)

---

## 2. Build Element

```bash
cd nginx/
```

### Buat compose
```bash
docker compose create
```

![ss](./screenshot/5.png)

### Jalankan compose
```bash
docker compose create
```
`-d` untuk menjalankan di background

![ss](./screenshot/6.png)

### Lihat container yg aktif
```bash
docker compose ps
```

![ss](./screenshot/7.png)


### Lihat di browser

![ss](./screenshot/8.png)

### Matikan dan hapus

![ss](./screenshot/9.png)

---

## 3. Node App

```bash
cd node_app/
```