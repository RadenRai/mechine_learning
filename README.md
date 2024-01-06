# Mental Health Treatment Machine Learning Model

## Pertanyaan

```sh
1. Jika Anda tinggal di Amerika Serikat, di negara bagian atau wilayah mana Anda tinggal?
2. Apakah Anda bekerja mandiri?
3. Apakah ada riwayat penyakit mental dalam keluarga Anda?
4. Apakah Anda mencari pengobatan untuk kondisi kesehatan mental?
5. Jika Anda memiliki kondisi kesehatan mental, apakah Anda merasa itu mengganggu pekerjaan Anda?
6. Berapa banyak karyawan yang bekerja di perusahaan atau organisasi Anda?
7. Apakah Anda bekerja secara remote (di luar kantor) setidaknya 50% dari waktu?
8. Apakah pengusaha Anda terutama merupakan perusahaan/organisasi teknologi?
9. Apakah pengusaha Anda menyediakan manfaat kesehatan mental?
10. Apakah Anda mengetahui opsi perawatan kesehatan mental yang disediakan oleh pengusaha Anda?
11. Apakah pengusaha Anda pernah membahas kesehatan mental sebagai bagian dari program kesejahteraan karyawan?
12. Apakah pengusaha Anda menyediakan sumber daya untuk mempelajari lebih lanjut tentang masalah kesehatan mental dan cara mencari bantuan?
13. Apakah anonimitas Anda dilindungi jika Anda memilih untuk memanfaatkan sumber daya pengobatan kesehatan mental atau penyalahgunaan zat?
14. Seberapa mudah bagi Anda untuk mengambil cuti medis karena kondisi kesehatan mental?
15. Apakah Anda berpikir bahwa membicarakan masalah kesehatan mental dengan pengusaha Anda akan memiliki konsekuensi negatif?
16. Apakah Anda berpikir bahwa membicarakan masalah kesehatan fisik dengan pengusaha Anda akan memiliki konsekuensi negatif?
17. Apakah Anda bersedia membicarakan masalah kesehatan mental dengan rekan kerja Anda?
18. Apakah Anda bersedia membicarakan masalah kesehatan mental dengan atasan langsung Anda?
19. Apakah Anda akan membahas masalah kesehatan mental dengan calon pengusaha dalam wawancara?
20. Apakah Anda akan membahas masalah kesehatan fisik dengan calon pengusaha dalam wawancara?
21. Apakah Anda merasa bahwa pengusaha Anda menganggap serius kesehatan mental sebanyak kesehatan fisik?
22. Apakah Anda pernah mendengar atau menyaksikan konsekuensi negatif bagi rekan kerja dengan kondisi kesehatan mental di tempat kerja Anda?
23. Catatan atau komentar tambahan?
```

## Input

```sh
Dari Seluruh pertanyaan diatas, jawabannya adalah “Yes” dan “No”.
```

## Output

```sh
Hasil prediksi di aplikasi nantinya adalah sebagai berikut :
1. High Probability (Seseorang tersebut memiliki tingkat tinggi kebutuhan atau kecenderungan untuk mencari perawatan kesehatan mental)
Jika hasil mendapat High Probability, dapat ditambahkan pesan atau informasi berikut :
	a.	“Disarankan untuk mencari konsultasi profesional segera”.
	b.	“Pertimbangkan berbicara dengan ahli kesehatan mental untuk mendapatkan dukungan”.
	c.	Tambahkan juga Sumber Daya dan Bantuan (Seperti nomor telepon hotlines, aplikasi kesehatan mental, atau situs web yang menyediakan dukungan).
	d.	Berikan informasi pendek tentang kesehatan mental untuk meningkatkan pemahaman pengguna tentang pentingnya perawatan dan dukungan.
	e.	Ingatkan pengguna tentang pentingnya berbicara dengan teman, keluarga, atau rekan kerja tentang kesehatan mental. Berbagi pengalaman dapat membantu mengurangi stigma.
	f.	Jika relevan, berikan informasi tentang kebijakan cuti atau dukungan karyawan yang mungkin tersedia di tempat kerja pengguna.
2.	Low Probability (Seseorang tersebut memiliki tingkat rendah kebutuhan atau kecenderungan untuk mencari perawatan kesehatan mental)
Jika hasil mendapat High Probability, dapat ditambahkan pesan atau informasi berikut :
	a.	“Tingkat kebutuhan perawatan kesehatan mental dipersepsikan rendah berdasarkan jawaban Anda. Terus pertahankan kesehatan mental Anda dengan melakukan kegiatan yang Anda nikmati”.
	b.	“Sepertinya Anda memiliki dukungan yang baik atau strategi koping yang efektif. Tetap menjaga kesehatan mental Anda”.
	c.	Berikan informasi tentang praktik kesehatan mental dan pencegahan, seperti menjaga keseimbangan hidup, berolahraga, dan menjalin hubungan sosial positif.
	d.	Sediakan informasi tentang sumber daya atau layanan pendukung yang dapat diakses oleh pengguna jika diperlukan di masa depan.
	e.	Ingatkan pengguna untuk tetap memantau kesehatan mental mereka dan mencari bantuan jika mengalami perubahan signifikan atau perasaan yang memprihatinkan.

```
