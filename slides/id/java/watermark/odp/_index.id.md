---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Tambahkan Watermark ke File Presentasi ODP menggunakan Java
url: /id/java/watermark/odp/
description: Tambahkan watermark teks dan gambar ke presentasi ODP di Java menggunakan Aspose.Slides for Java.
keywords: tambahkan watermark ke ODP, tambahkan watermark teks ke ODP, tambahkan watermark gambar ke ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Tambahkan Watermark ke Presentasi ODP dengan Java" h2="Bangun aplikasi Java yang menyisipkan watermark teks atau gambar ke dalam file presentasi dengan API sisi server." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Tambahkan Watermark ke Presentasi ODP melalui Java" variant="code" %}}

Dengan [Aspose.Slides for Java](/slides/id/java/), Anda dapat menambahkan watermark teks dan gambar ke presentasi ODP. Tambahkan bentuk watermark ke slide master agar watermark muncul pada slide yang menggunakan master tersebut.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Tambahkan Watermark Teks ke ODP menggunakan Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Tambahkan Watermark Gambar ke Presentasi ODP menggunakan Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara Menambahkan Watermark ke ODP melalui Java" intro="Ikuti langkah-langkah berikut untuk menambahkan watermark teks atau gambar ke file ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Muat file `ODP` dengan kelas `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Pilih slide master melalui metode `getMasters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `addAutoShape` untuk menambahkan bentuk watermark.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Panggil metode `addTextFrame` untuk menambahkan teks watermark atau gunakan `addImage` untuk watermark gambar.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan presentasi yang diberi watermark dalam format ODP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Dibuat dengan Aspose.Slides" title="Tambahkan Watermark ke File ODP Secara Online" description="Aplikasi Aspose.Slides Watermark gratis dibuat dengan [Aspose.Slides for Java](https://products.aspose.com/slides/id/java/), API yang sama dengan kode di atas. Buka aplikasinya dan lihat apa yang dapat dilakukan API dengan file ODP Anda sendiri." button="Buka Aspose.Slides Watermark" note="[Semua aplikasi gratis](https://products.aspose.app/slides/family)" >}}
- Berjalan di browser Anda, tanpa perlu menginstal apa pun.
- Lihat cara Aspose.Slides menambahkan watermark sebelum menulis kode.
- Tambahkan watermark teks atau gambar ke file ODP Anda.
- Unduh file yang diberi watermark.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Format Lain yang Mendukung Watermark" subTitle="Dengan Java, Anda juga dapat menambahkan watermark ke format berikut." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/id/java/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
