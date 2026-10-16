---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konversikan POTX ke JPG di Node.js
url: /id/nodejs-java/conversion/potx-to-jpg/
keywords: POTX ke JPG, Konversi POTX ke JPG, API Node.js, Pustaka Node.js, POTX, JPG
description: Konversikan POTX ke JPG di Node.js. Gunakan API perpustakaan Node.js untuk mengonversi file POTX menjadi JPG
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konversikan POTX ke JPG di Node.js" h2="Aspose.Slides untuk Node.js melalui Java adalah pustaka yang kuat dan mudah digunakan yang memungkinkan Anda mengonversi presentasi PowerPoint ke berbagai format di Node.js. Ini mendukung semua elemen dan format presentasi dan menyediakan API yang kaya untuk mengakses dan memodifikasinya. Ini juga memungkinkan Anda mengekspor slide Anda ke berbagai format untuk diproses atau dibagikan lebih lanjut." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan POTX ke JPG menggunakan Node.js" variant="code" %}}

Untuk mengonversi POTX ke JPG, Anda perlu membuat Presentasi dari file POTX dan menyimpannya sebagai JPG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Kode Node.js untuk mengubah POTX menjadi JPG" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.potx");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".jpg");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "jpeg", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konversikan POTX ke JPG di Node.js" %}}

[**Aspose.Slides untuk Node.js melalui Java**](https://products.aspose.com/slides/id/nodejs-java/) adalah pustaka Node.js yang canggih untuk membuat dan memanipulasi file presentasi. Selain itu, ini menyediakan cara yang fleksibel untuk mengonversi POTX ke JPG. Menggunakan **Aspose.Slides untuk Node.js melalui Java**, pengembang atau aplikasi mana pun dapat mengonversi file POTX ke JPG hanya dengan beberapa baris kode.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk Node.js mengekspor file POTX ke format file JPG dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi POTX ke JPG dan banyak format file lainnya

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cara mengonversi POTX ke JPG menggunakan Aspose.Slides untuk Node.js melalui Java API" intro="Untuk mengonversi POTX ke JPG menggunakan Aspose.Slides untuk Node.js melalui Java, Anda perlu mengimpor paket dalam file JavaScript Anda dan membuat instance kelas Presentation. Kelas Presentasi mewakili dokumen PowerPoint dan menyediakan metode untuk mengakses dan memanipulasi elemen-elemennya." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instal [**Aspose.Slides untuk Node.js melalui Java**](https://products.aspose.com/slides/id/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Node.js Anda.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Buka file sumber POTX di Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Simpan hasil sebagai file JPG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Konversikan POTX Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi POTX dan menyimpannya ke format file lain. Lihat semua format yang didukung di bawah" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-png/" name="POTX TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-bmp/" name="POTX TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-pps/" name="POTX TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/id/nodejs-java/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
