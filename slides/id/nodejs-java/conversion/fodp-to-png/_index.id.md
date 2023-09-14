---
title: Konversikan FODP ke PNG di Node.js
url: /id/nodejs-java/conversion/fodp-to-png/
keywords: FODP ke PNG, Konversi FODP ke PNG, API Node.js, Pustaka Node.js, FODP, PNG
description: Konversikan FODP ke PNG di Node.js. Gunakan API perpustakaan Node.js untuk mengonversi file FODP menjadi PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan FODP ke PNG di Node.js" h2="Aspose.Slides untuk Node.js melalui Java adalah pustaka yang kuat dan mudah digunakan yang memungkinkan Anda mengonversi presentasi PowerPoint ke berbagai format di Node.js. Ini mendukung semua elemen dan format presentasi dan menyediakan API yang kaya untuk mengakses dan memodifikasinya. Ini juga memungkinkan Anda mengekspor slide Anda ke berbagai format untuk diproses atau dibagikan lebih lanjut." >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan FODP ke PNG di Node.js" %}}

[**Aspose.Slides untuk Node.js melalui Java**](https://products.aspose.com/slides/id/nodejs-java/) adalah pustaka Node.js yang canggih untuk membuat dan memanipulasi file presentasi. Selain itu, ini menyediakan cara yang fleksibel untuk mengonversi FODP ke PNG. Menggunakan **Aspose.Slides untuk Node.js melalui Java**, pengembang atau aplikasi mana pun dapat mengonversi file FODP ke PNG hanya dengan beberapa baris kode.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk Node.js mengekspor file FODP ke format file PNG dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi FODP ke PNG dan banyak format file lainnya

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan FODP ke PNG menggunakan Node.js" %}}
Untuk mengonversi FODP ke PNG, Anda perlu membuat Presentasi dari file FODP dan menyimpannya sebagai PNG.

{{% blocks/products/pf/agp/code-block title="Kode Node.js untuk mengubah FODP menjadi PNG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.fodp");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".png");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "png", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara mengonversi FODP ke PNG menggunakan Aspose.Slides untuk Node.js melalui Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Untuk mengonversi FODP ke PNG menggunakan Aspose.Slides untuk Node.js melalui Java, Anda perlu mengimpor paket dalam file JavaScript Anda dan membuat instance kelas Presentation. Kelas Presentasi mewakili dokumen PowerPoint dan menyediakan metode untuk mengakses dan memanipulasi elemen-elemennya." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides untuk Node.js melalui Java**](https://products.aspose.com/slides/id/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Node.js Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file sumber FODP di Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil sebagai file PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversikan FODP Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi FODP dan menyimpannya ke format file lain. Lihat semua format yang didukung di bawah" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-pptx/" name="FODP TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-ppt/" name="FODP TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-pdf/" name="FODP TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-html/" name="FODP TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-bmp/" name="FODP TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-jpg/" name="FODP TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-gif/" name="FODP TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-odp/" name="FODP TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-otp/" name="FODP TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-pot/" name="FODP TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-potm/" name="FODP TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-potx/" name="FODP TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-pps/" name="FODP TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-ppsm/" name="FODP TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-ppsx/" name="FODP TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-pptm/" name="FODP TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-svg/" name="FODP TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/fodp-to-tiff/" name="FODP TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}