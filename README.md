# Quran 16 Lines — Indo-Pak Mushaf

**Format:** 16 Lines per page  
**Total Pages:** 554  
**Total Paras (Juz):** 30  
**Image:** Original color JPEG (RGB, ~856×1303 px)  

---

## 📦 Repository Structure

30 zip files — one per Para (Juz).

| File | Para | Pages | Page Range |
|------|------|-------|------------|
| `parah_01.zip` | Para 1 — اَلٓمٓ | 18 | 001–018 |
| `parah_02.zip` | Para 2 — سَيَقُوۡلُ | 18 | 019–036 |
| `parah_03.zip` | Para 3 — تِلۡكَ الرُّسُلُ | 19 | 037–055 |
| `parah_04.zip` | Para 4 — لَنۡ تَنَالُوا | 18 | 056–073 |
| `parah_05.zip` | Para 5 — وَالۡمُحۡصَنَاتُ | 18 | 074–091 |
| `parah_06.zip` | Para 6 — لَا يُحِبُّ اللّٰهُ | 18 | 092–109 |
| `parah_07.zip` | Para 7 — وَاِذَا سَمِعُوۡا | 19 | 110–128 |
| `parah_08.zip` | Para 8 — وَلَوۡ اَنَّنَا | 18 | 129–146 |
| `parah_09.zip` | Para 9 — قَالَ الۡمَلَاُ | 18 | 147–164 |
| `parah_10.zip` | Para 10 — وَاعۡلَمُوۡۤا | 19 | 165–183 |
| `parah_11.zip` | Para 11 — يَعۡتَذِرُوۡنَ | 18 | 184–201 |
| `parah_12.zip` | Para 12 — وَمَا مِنۡ دَآبَّةٍ | 18 | 202–219 |
| `parah_13.zip` | Para 13 — وَمَاۤ اُبَرِّئُ | 19 | 220–238 |
| `parah_14.zip` | Para 14 — رُبَمَا | 18 | 239–256 |
| `parah_15.zip` | Para 15 — سُبۡحٰنَ الَّذِىۡۤ | 18 | 257–274 |
| `parah_16.zip` | Para 16 — قَالَ اَلَمۡ | 18 | 275–292 |
| `parah_17.zip` | Para 17 — اِقۡتَرَبَتۡ | 18 | 293–310 |
| `parah_18.zip` | Para 18 — قَدۡ اَفۡلَحَ | 19 | 311–329 |
| `parah_19.zip` | Para 19 — وَقَالَ الَّذِيۡنَ | 18 | 330–347 |
| `parah_20.zip` | Para 20 — اَمَّنۡ خَلَقَ | 18 | 348–365 |
| `parah_21.zip` | Para 21 — اُتۡلُ مَاۤ اُوۡحِىَ | 19 | 366–384 |
| `parah_22.zip` | Para 22 — وَمَنۡ يَّقۡنُتۡ | 18 | 385–402 |
| `parah_23.zip` | Para 23 — وَمَالِىَ | 18 | 403–420 |
| `parah_24.zip` | Para 24 — فَمَنۡ اَظۡلَمُ | 18 | 421–438 |
| `parah_25.zip` | Para 25 — اِلَيۡهِ يُرَدُّ | 19 | 439–457 |
| `parah_26.zip` | Para 26 — حٰمٓ | 18 | 458–475 |
| `parah_27.zip` | Para 27 — قَالَ فَمَا خَطۡبُكُمۡ | 18 | 476–493 |
| `parah_28.zip` | Para 28 — قَدۡ سَمِعَ اللّٰهُ | 18 | 494–511 |
| `parah_29.zip` | Para 29 — تَبٰرَكَ الَّذِىۡ | 19 | 512–530 |
| `parah_30.zip` | Para 30 — عَمَّ | 24 | 531–554 |

---

## 🖼️ Image Format Inside Each Zip

Images use **global page numbers** as filenames (same as 15-line repo):

```
parah_01.zip
  ├── 001.jpg   ← Page 1  of the Quran
  ├── 002.jpg   ← Page 2
  ├── ...
  └── 018.jpg   ← Page 18

parah_02.zip
  ├── 019.jpg   ← Page 19
  └── ...

parah_30.zip
  ├── 531.jpg
  └── 554.jpg   ← Last page
```

- **Color:** Original RGB (full color, no grayscale)
- **Resolution:** Original scan (~856×1303 px)
- **Format:** JPEG (extracted directly from source PDF)
- **Size per zip:** 4.3 MB – 5.1 MB

---

## 📱 Android App Integration (NoorAlHuda)

### Raw Download URL Pattern
```
https://raw.githubusercontent.com/YOUR_USERNAME/quran_16_lines/main/parah_01.zip
https://raw.githubusercontent.com/YOUR_USERNAME/quran_16_lines/main/parah_02.zip
```

### Update QuranType.java — LINES_16

```java
LINES_16(
    "16 Lines",
    "Indo-Pak Mushaf",
    "ہندو-پاک مصحف",
    "١٦ سطریں",
    "#3D1A5C",
    "#AA00FF",
    "https://raw.githubusercontent.com/YOUR_USERNAME/quran_16_lines/main/",
    "quran_16",
    554,      // ← actual page count from PDF
    new int[]{
          1, 19, 37, 56, 74, 92,110,129,147,165,
        184,202,220,239,257,275,293,311,330,348,
        366,385,403,421,439,458,476,494,512,531
    }
),
```

---

## ⬆️ How to Upload to GitHub

### Option A — GitHub Web (Easiest)
1. Go to: `https://github.com/new`
2. Repository name: `quran_16_lines`
3. Visibility: **Public** ✅
4. Click **Create repository**
5. Click **Add file → Upload files**
6. Drag all 30 `parah_XX.zip` files + `README.md`
7. Click **Commit changes**

### Option B — Git CLI
```bash
git init quran_16_lines
cd quran_16_lines
cp /path/to/parah_*.zip .
cp /path/to/README.md .
git add .
git commit -m "Add 16-line Quran (Indo-Pak) - 554 pages, 30 Para zips, full color"
git remote add origin https://github.com/YOUR_USERNAME/quran_16_lines.git
git push -u origin main
```

### Option C — GitHub CLI
```bash
gh repo create quran_16_lines --public --clone
cd quran_16_lines
cp /path/to/parah_*.zip .
cp /path/to/README.md .
git add . && git commit -m "Initial upload"
git push
```

> ⚠️ **Note:** Each zip is ~4.5 MB. Total repo ≈ 138 MB.
> GitHub allows up to 100 MB per **file** and 1 GB per **repo** — you are well within limits.

---

## ✅ Verified
- Source: `Quran_16_Lines.pdf` (554 pages, Adobe Acrobat)
- All 554 pages extracted as original color JPEG
- All 30 zips created — same structure as `quran_15_lines` repo
- Para boundaries scaled from verified 13-line Taj Company Quran data
- Image naming: global page numbers `001.jpg` … `554.jpg`
