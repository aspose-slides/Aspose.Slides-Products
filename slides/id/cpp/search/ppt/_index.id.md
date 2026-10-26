---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Cari Teks dalam Presentasi PPT menggunakan C++
url: /id/cpp/search/ppt/
description: Cari teks dalam presentasi PPT di C++. Gunakan Aspose.Slides for C++ untuk menemukan teks dalam file presentasi.
keywords: cari kata di PPT, temukan teks di PPT, cari teks presentasi PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Cari Teks dalam PPT menggunakan C++" h2="Gunakan Aspose.Slides for C++ untuk menemukan teks dalam file presentasi tanpa Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cari Teks dalam Presentasi PPT melalui C++" variant="code" %}}

Aspose.Slides for C++ memungkinkan Anda mencari teks dalam presentasi PPT. Gunakan `SlideUtil::GetAllTextBoxes` untuk mengumpulkan bingkai teks sebuah slide, lalu periksa apakah teksnya berisi frasa yang diperlukan.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cari Teks dalam Sebuah Presentasi PPT menggunakan C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

auto slide = presentation->get_Slides()->idx_get(0);
auto textFrames = SlideUtil::GetAllTextBoxes(slide);

for (auto&& textFrame : textFrames)
{
    auto text = textFrame->get_Text();
    if (text.Contains(u"PowerPoint"))
    {
        Console::WriteLine(text);
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Mencari Teks dalam PPT melalui C++" intro="Ikuti langkah-langkah berikut untuk mencari teks dalam presentasi PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file PPT dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ambil slide yang diperlukan dengan `Presentation::get_Slides` dan ambil bingkai teksnya dengan [`SlideUtil::GetAllTextBoxes`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/getalltextboxes/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Periksa apakah teks setiap bingkai berisi frasa yang diperlukan.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Dibuat dengan Aspose.Slides" title="Cari Teks dalam File PPT Secara Online" description="Aplikasi Aspose.Slides Search gratis dibuat dengan [Aspose.Slides for C++](https://products.aspose.com/slides/id/cpp/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file PPT Anda sendiri." button="Buka Aspose.Slides Search" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menemukan teks sebelum Anda menulis kode.
- Cari teks biasa atau ekspresi reguler di file PPT Anda.
- Unduh hasil pencarian sebagai file teks.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Pencarian" subTitle="Dengan C++, Anda juga dapat mencari teks dalam format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
