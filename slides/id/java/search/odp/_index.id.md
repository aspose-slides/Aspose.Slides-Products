---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Cari Teks dalam File Presentasi ODP menggunakan Java
url: /id/java/search/odp/
description: Cari teks dalam presentasi ODP di Java menggunakan Aspose.Slides for Java.
keywords: cari kata di ODP, cari teks di ODP, cari teks presentasi ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Cari Teks dalam ODP menggunakan Java" h2="Bangun aplikasi Java yang mencari teks dalam file presentasi menggunakan API sisi server." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Cari Teks dalam Presentasi ODP melalui Java" variant="code" %}}

Dengan [Aspose.Slides for Java](/slides/id/java/), Anda dapat mencari teks dalam presentasi ODP. Gunakan metode `SlideUtil.getAllTextBoxes` untuk mengumpulkan bingkai teks, lalu periksa objek `ITextFrame`, `IParagraph`, dan `IPortion`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cari Teks dalam Sebuah Presentasi ODP menggunakan Java" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Mencari Teks dalam ODP melalui Java" intro="Ikuti langkah-langkah berikut untuk mencari teks dalam presentasi ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file ODP dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `SlideUtil.getAllTextBoxes` untuk mengumpulkan bingkai teks dari setiap slide.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Periksa objek `ITextFrame`, `IParagraph`, dan `IPortion` untuk menemukan teks yang cocok.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Dibuat dengan Aspose.Slides" title="Cari Teks dalam File ODP Secara Online" description="Aplikasi Aspose.Slides Search gratis dibuat dengan [Aspose.Slides for Java](https://products.aspose.com/slides/id/java/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file ODP Anda sendiri." button="Buka Aspose.Slides Search" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menemukan teks sebelum Anda menulis kode.
- Cari teks biasa atau ekspresi reguler di file ODP Anda.
- Unduh hasil pencarian sebagai file teks.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Didukung untuk Pencarian" subTitle="Dengan Java, Anda juga dapat mencari teks dalam format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
