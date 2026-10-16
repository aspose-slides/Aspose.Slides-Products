---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversikan Image ke PDF di Java
url: /id/java/conversion/image-to-pdf/
keywords: Image ke PDF, Konversikan Image ke PDF, Java API, Perpustakaan Java, Image, PDF
description: Konversikan Image ke PDF di Java. Gunakan Java library API untuk mengonversi file Image ke PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversikan Image ke PDF di Java" h2="Pustaka Java berkecepatan tinggi dan lintas platform yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan Image ke PDF menggunakan Java" variant="code" %}}

Untuk mengonversi Image ke PDF, Anda perlu membuat Presentasi dari file Image dan menyimpannya sebagai PDF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode Java untuk mengonversi Image menjadi PDF" >}}
```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan Image ke PDF di Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/id/java/) adalah library Java yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi Image ke PDF. Menggunakan **Aspose.Slides untuk Java**, pengembang atau aplikasi apa pun dapat mengonversi file Image ke PDF hanya dengan beberapa baris kode Java.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk Java mengekspor file Image ke format file PDF dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi Image ke PDF dan banyak format file lainnya

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara mengonversi Image ke PDF menggunakan Aspose.Slides untuk Java API" intro="Ini adalah langkah-langkah untuk mengonversi Image ke PDF di Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal [**Aspose.Slides for Java**](https://products.aspose.com/slides/id/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Java Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file sumber Image di Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan hasilnya sebagai file PDF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Konverter Daring Gratis"
  description="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversikan Image Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi Image dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
