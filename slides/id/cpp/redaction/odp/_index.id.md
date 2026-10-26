---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Sensor Presentasi ODP menggunakan C++
url: /id/cpp/redaction/odp/
description: Sensor presentasi ODP di C++. Gunakan Aspose.Slides for C++ untuk mencari dan mengganti teks sensitif dalam file presentasi.
keywords: sensor ODP, cari dan ganti teks di ODP, perbarui presentasi ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Sensor ODP menggunakan C++" h2="Gunakan Aspose.Slides for C++ untuk mencari dan mengganti teks sensitif dalam file presentasi tanpa Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Sensor Presentasi ODP melalui C++" variant="code" %}}

Aspose.Slides for C++ memungkinkan Anda menyensor presentasi ODP dengan mengganti teks sensitif pada slide. Gunakan `SlideUtil::FindAndReplaceText` dengan objek `Presentation` untuk menelusuri presentasi dan mengganti teks yang cocok sebelum menyimpan file yang diperbarui.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Sensor Sebuah Presentasi ODP menggunakan C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menyensor ODP melalui C++" intro="Ikuti langkah-langkah berikut untuk menyensor presentasi ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file ODP dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gunakan metode [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) untuk mencari dan mengganti teks sensitif.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan file yang telah disensor dengan `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Dibuat dengan Aspose.Slides" title="Sensor File ODP Secara Online" description="Aplikasi Aspose.Slides Redaction gratis dibuat dengan [Aspose.Slides for C++](https://products.aspose.com/slides/id/cpp/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file ODP Anda sendiri." button="Buka Aspose.Slides Redaction" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides mencari dan mengganti teks sebelum Anda menulis kode.
- Cari dan ganti teks di file ODP Anda, termasuk dengan ekspresi reguler.
- Unduh file yang telah disensor.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Penyensoran" subTitle="Dengan C++, Anda juga dapat menyensor format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
