# Gaya Video: "Sumbangan Bakul Makanan – Kg Alah Batu"

Rujukan: `VID_20261111_130047_622.mp4` (Google Drive)

## 1. Spesifikasi teknikal

| Perkara | Nilai |
|---|---|
| Nisbah | 9:16 menegak (Reels / TikTok / Shorts) |
| Resolusi | 2144 × 3840 (≈4K menegak); export 1080×1920 pun cukup |
| Frame rate | 60 fps |
| Durasi | ~91 saat |
| Audio | Berterusan sepanjang video (tiada senyap): muzik latar, mungkin bercampur bunyi suasana |

## 2. Struktur cerita (ikut masa)

| Masa | Babak | Apa yang ditunjuk |
|---|---|---|
| 0–7s | **Hook + tajuk** | Wakil rakyat duduk berbual dengan pakcik, beg beras di foreground. Tajuk muncul dengan kesan taip. |
| 7–12s | **Wajah penerima** | Close-up dua orang pakcik warga emas, pandang kamera. |
| 12–23s | **Persiapan / B-roll** | Barisan beg kuning atas meja, dulang telur, beras, orang ramai menunggu di kerusi plastik. |
| 23–31s | **Detail** | Close-up label "Sumbangan Ikhlas" pada beg kuning. |
| 31–42s | **Ucapan + branding** | Wakil rakyat bercakap dengan mikrofon, bunting logo ADUN, banner "Program Ramah Mesra". |
| 42–50s | **Interaksi komuniti** | Penduduk duduk, seorang pakcik bercakap guna mikrofon. |
| 50–79s | **Penyerahan** | Siri shot serahan beg + telur kepada penerima seorang demi seorang (lelaki, wanita, warga emas). |
| 79–91s | **Penutup emosi** | Bersalam, berbual mesra, dipeluk pakcik. Ending yang "warm". |

Corak: **Hook → Manusia → Barang → Majlis → Penyerahan → Kemesraan**.

## 3. Gaya visual

- **Kamera:** handheld telefon, gerakan perlahan (slow push / pan), tiada drone, tiada tripod kaku.
- **Shot:** campur wide (suasana), medium (penyerahan), close-up (wajah & label).
- **Foreground framing:** banyak shot ada objek di depan (beg beras, telur, kerusi) untuk rasa kedalaman.
- **Potongan:** setiap klip ~3–6 saat, cut biasa (tiada transition berlebihan).
- **Warna:** natural, cerah, sedikit saturasi pada kuning/hijau; tiada filter pelik.

## 4. Teks & overlay

- **Tajuk dua baris di atas (bahagian 1/4 atas skrin):**
  - Baris kecil – font *script / tulisan tangan*: `Sumbangan Bakul Makanan`
  - Baris besar – font *serif tebal* putih: `Kg Alah Batu`
  - Animasi: **typewriter** (huruf muncul satu-satu ~1–2 saat), kemudian kekal sepanjang video.
  - Bayang (drop shadow) lembut supaya jelas atas latar.
- **Watermark di bawah (1/5 bawah skrin):** nama `MUIZ MAHYUDDIN` (sans-serif, huruf besar, jarak huruf lebar, putih separa telus) + ikon kecil Facebook / TikTok / Instagram di bawahnya. Kekal sepanjang video.
- Tiada sarikata panjang; teks minimum.

## 5. Mood

Ikhlas, mesra, kampung, "turun padang". Fokus pada **wajah penerima** dan **kemesraan**, bukan pada pemimpin semata-mata.

---

## 6. PROMPT

### A. Prompt untuk aku (Claude) bila hang hantar bahan

```
Edit video ikut gaya dalam video-style/GAYA-VIDEO-SUMBANGAN.md.

Bahan: [link Google Drive folder klip]
Nama program (baris kecil, font script): [cth: Sumbangan Bakul Makanan]
Lokasi (baris besar, font serif): [cth: Kg Alah Batu]
Nama watermark: [cth: MUIZ MAHYUDDIN]
Muzik: [fail muzik / "guna audio asal"]
Durasi sasaran: [cth: 60–90 saat]
Shot wajib masuk: [cth: ucapan, serahan kepada makcik baju merah]

Susun ikut struktur Hook → Manusia → Barang → Majlis → Penyerahan → Kemesraan,
klip 3–6 saat, 9:16, 1080x1920 60fps.
```

### B. Prompt untuk AI video generator (Veo / Sora / Kling / Runway)

Nama gaya: **vertical event recap, documentary style, handheld, no voiceover**
(BM: "video highlight program komuniti" / "video turun padang").

#### B1. Prompt utama

```
Vertical 9:16 event recap video, documentary style, shot handheld on a
smartphone at 60fps. Natural bright daylight in a Malaysian kampung setting
with coconut palms, green grass and a colourful community hall.
[NAMA PROGRAM, cth: a food aid distribution program]. A friendly young
community leader in a [WARNA BAJU] jersey interacts with local villagers:
elderly men in kopiah, women in tudung, families sitting on plastic chairs.
Rows of [BARANG SUMBANGAN, cth: yellow food-aid bags, rice sacks, egg trays]
on folding tables.
Mood: sincere, warm, humble, grassroots. Camera: slow handheld push-ins and
gentle pans, foreground objects framing the subject, shallow depth of field.
Mix of wide shots, medium shots and emotional close-ups of faces.
Realistic natural colours, slightly vibrant, no voiceover, no on-screen text.
```

#### B2. Prompt ikut babak (jana satu klip 5–10s setiap babak, sambung masa edit)

| # | Babak | Prompt |
|---|---|---|
| 1 | Pembuka | `Close-up handheld shot, young leader sitting and chatting warmly with an elderly villager in kopiah, rice sacks blurred in foreground, slow push-in, vertical 9:16` |
| 2 | Wajah | `Emotional close-up portrait of two elderly Malay men sitting on plastic chairs, looking at camera, soft daylight, shallow depth of field, vertical` |
| 3 | Barang | `Slow pan across rows of yellow food-aid bags on a folding table, tropical garden background, bright daylight, vertical` |
| 4 | Suasana | `Wide shot of villagers seated on light-blue plastic chairs under coconut trees waiting for an event, egg trays in foreground, vertical` |
| 5 | Ucapan | `Medium shot, young leader speaking into a microphone to the crowd, banner in background, handheld, vertical` |
| 6 | Penyerahan | `Medium shot, leader handing a yellow food bag and egg tray to an elderly woman in tudung, both smiling, handheld, vertical` |
| 7 | Penutup | `Heartwarming moment, elderly man hugging the young leader and laughing, golden daylight, slow motion, vertical` |

#### B3. Negative prompt (elakkan)

```
Avoid: on-screen text, logos, distorted hands, extra fingers, cinematic
teal-orange grade, drone shots, studio lighting, staged posing.
```

**Tips:**
- Teks tajuk & watermark tambah masa edit — AI generator selalu rosakkan tulisan.
- Untuk muka orang sebenar (wakil rakyat, penduduk), guna footage betul;
  video AI lebih sesuai untuk B-roll (barang, suasana, pemandangan).

### C. Prompt untuk editor (CapCut / ChatGPT plan edit)

```
Buat pelan edit video Reels 9:16, 60–90 saat, gaya dokumentari komuniti
"turun padang". Struktur:
1) 0–7s hook: shot pemimpin berbual dengan warga emas, barang sumbangan di foreground.
2) 7–12s close-up wajah penerima.
3) 12–25s B-roll barang sumbangan (beg, beras, telur) dan orang ramai menunggu.
4) 25–30s close-up label sumbangan.
5) 30–45s ucapan + banner/logo program.
6) 45–80s montaj penyerahan, setiap penerima 3–4s.
7) 80–90s penutup: salam, peluk, senyum.

Teks: tajuk 2 baris di 1/4 atas skrin — baris 1 font script kecil
"[NAMA PROGRAM]", baris 2 font serif tebal putih besar "[LOKASI]",
animasi typewriter 1.5s, kekal sepanjang video, drop shadow lembut.
Watermark: "[NAMA]" sans-serif uppercase letter-spacing lebar, putih 70%
opacity, ikon FB/TikTok/IG di bawahnya, di 1/5 bawah skrin.
Muzik: nasyid / akustik lembut yang menyentuh hati, volume rendah.
Cut terus (tiada transition), warna natural, saturasi kuning/hijau +10.
```

### D. Prompt caption media sosial

```
Tulis caption Facebook/TikTok dalam Bahasa Melayu santai untuk video
sumbangan bakul makanan di [LOKASI] oleh [NAMA/PEJABAT]. Nada ikhlas dan
mesra, 3–5 ayat, ucap terima kasih kepada penduduk & petugas, sertakan
3–5 hashtag (cth: #[DUN] #TurunPadang #SumbanganIkhlas).
```
