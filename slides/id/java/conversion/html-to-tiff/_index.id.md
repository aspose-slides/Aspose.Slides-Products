---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversikan HTML ke TIFF di Java
url: /id/java/conversion/html-to-tiff/
keywords: HTML ke TIFF, Konversikan HTML ke TIFF, Java API, Perpustakaan Java, HTML, TIFF
description: Konversikan HTML ke TIFF di Java. Gunakan Java library API untuk mengonversi file HTML ke TIFF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversikan HTML ke TIFF di Java" h2="Pustaka Java berkecepatan tinggi dan lintas platform yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan HTML ke TIFF menggunakan Java" variant="code" %}}

Untuk mengonversi HTML ke TIFF, Anda perlu membuat Presentasi dari file HTML dan menyimpannya sebagai TIFF.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode Java untuk mengonversi HTML menjadi TIFF" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream tr = new FileInputStream("file.html");
    pres.getSlides().addFromHtml(tr);
    pres.save("doc.tiff", SaveFormat.Tiff);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan HTML ke TIFF di Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/id/java/) adalah library Java yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi HTML ke TIFF. Menggunakan **Aspose.Slides untuk Java**, pengembang atau aplikasi apa pun dapat mengonversi file HTML ke TIFF hanya dengan beberapa baris kode Java.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk Java mengekspor file HTML ke format file TIFF dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi HTML ke TIFF dan banyak format file lainnya

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara mengonversi HTML ke TIFF menggunakan Aspose.Slides untuk Java API" intro="Ini adalah langkah-langkah untuk mengonversi HTML ke TIFF di Java." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal [**Aspose.Slides for Java**](https://products.aspose.com/slides/id/java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Java Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file sumber HTML di Java.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan hasilnya sebagai file TIFF.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Konverter Daring Gratis"
  description="[Cara Mengonversi PPT ke HTML dengan Python](https://products.aspose.com/slides/id/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversikan HTML Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi HTML dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/java/conversion/html-to-xml/" name="HTML TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
