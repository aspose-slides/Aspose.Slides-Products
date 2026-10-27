---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 460
title: Ekstrak Teks dari Presentasi ODP menggunakan C++
url: /id/cpp/parser/odp/ 
description: Ekstrak teks dari presentasi ODP di C++. Gunakan Aspose.Slides for C++ untuk melakukan parsing slide, bingkai teks, paragraf, dan bagian teks.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Parsing Presentasi ODP di C++" h2="Gunakan Aspose.Slides for C++ untuk mengekstrak teks dari slide presentasi tanpa Microsoft PowerPoint."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Parsing File ODP dengan C++" %}}

Gunakan Aspose.Slides for C++ untuk melakukan parsing file presentasi ODP dan mengekstrak teks dari slide. API menyediakan teks slide melalui `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph`, dan `IPortion`, sehingga Anda dapat membaca konten teks tanpa mengotomatiskan Microsoft PowerPoint. Instal paket [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) dari NuGet atau gunakan perintah Package Manager Console di bawah ini.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Perintah" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Parsing File ODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Parsing File ODP di C++" intro="Ekstrak teks dari file ODP dengan Aspose.Slides for C++." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file ODP dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ambil objek `ITextFrame` dari slide pertama dengan `SlideUtil::GetAllTextBoxes`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telusuri objek `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telusuri objek `IParagraph` di setiap `ITextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Telusuri objek `IPortion` di setiap `IParagraph`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Baca teks dengan `get_Text`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Persyaratan Sistem" intro="Aspose.Slides for C++ mendukung platform desktop dan server utama. Pastikan proyek Anda memenuhi prasyarat berikut." %}}

-  Microsoft Windows, Linux, macOS, atau sistem operasi lain yang kompatibel dengan runtime C++ yang didukung.
-  Pustaka Aspose.Slides for C++ yang dirujuk dalam proyek Anda.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Dibuat dengan Aspose.Slides" title="Ekstrak Teks dan Gambar Secara Online" description="Aplikasi Aspose.Slides Parser gratis dibuat dengan [Aspose.Slides for C++](https://products.aspose.com/slides/id/cpp/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file ODP Anda sendiri." button="Buka Aspose.Slides Parser" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides membaca file Anda sebelum menulis kode.
- Unggah file ODP dan dapatkan teks serta gambarnya.
- Unduh semuanya sebagai satu arsip ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

File ODP adalah file presentasi OpenDocument yang digunakan oleh aplikasi seperti OpenOffice Impress dan LibreOffice Impress. File ini menyimpan slide, teks, gambar, pemformatan, animasi, dan konten presentasi lainnya dalam paket terbuka berbasis XML.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Parsing Lain yang Didukung" subTitle="Dengan C++, Anda juga dapat melakukan parsing format presentasi lain." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/parser/ppt/" name="PPT" description="Presentasi PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/cpp/parser/pptx/" name="PPTX" description="Presentasi PowerPoint Open XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
