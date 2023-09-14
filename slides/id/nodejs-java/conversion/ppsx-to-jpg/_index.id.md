---
title: Konversikan PPSX ke JPG di Node.js
url: /id/nodejs-java/conversion/ppsx-to-jpg/
keywords: PPSX ke JPG, Konversi PPSX ke JPG, API Node.js, Pustaka Node.js, PPSX, JPG
description: Konversikan PPSX ke JPG di Node.js. Gunakan API perpustakaan Node.js untuk mengonversi file PPSX menjadi JPG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan PPSX ke JPG di Node.js" h2="Aspose.Slides untuk Node.js melalui Java adalah pustaka yang kuat dan mudah digunakan yang memungkinkan Anda mengonversi presentasi PowerPoint ke berbagai format di Node.js. Ini mendukung semua elemen dan format presentasi dan menyediakan API yang kaya untuk mengakses dan memodifikasinya. Ini juga memungkinkan Anda mengekspor slide Anda ke berbagai format untuk diproses atau dibagikan lebih lanjut." >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan PPSX ke JPG di Node.js" %}}

[**Aspose.Slides untuk Node.js melalui Java**](https://products.aspose.com/slides/id/nodejs-java/) adalah pustaka Node.js yang canggih untuk membuat dan memanipulasi file presentasi. Selain itu, ini menyediakan cara yang fleksibel untuk mengonversi PPSX ke JPG. Menggunakan **Aspose.Slides untuk Node.js melalui Java**, pengembang atau aplikasi mana pun dapat mengonversi file PPSX ke JPG hanya dengan beberapa baris kode.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk Node.js mengekspor file PPSX ke format file JPG dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi PPSX ke JPG dan banyak format file lainnya

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan PPSX ke JPG menggunakan Node.js" %}}
Untuk mengonversi PPSX ke JPG, Anda perlu membuat Presentasi dari file PPSX dan menyimpannya sebagai JPG.

{{% blocks/products/pf/agp/code-block title="Kode Node.js untuk mengubah PPSX menjadi JPG" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.ppsx");
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


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara mengonversi PPSX ke JPG menggunakan Aspose.Slides untuk Node.js melalui Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Untuk mengonversi PPSX ke JPG menggunakan Aspose.Slides untuk Node.js melalui Java, Anda perlu mengimpor paket dalam file JavaScript Anda dan membuat instance kelas Presentation. Kelas Presentasi mewakili dokumen PowerPoint dan menyediakan metode untuk mengakses dan memanipulasi elemen-elemennya." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides untuk Node.js melalui Java**](https://products.aspose.com/slides/id/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Node.js Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file sumber PPSX di Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil sebagai file JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversikan PPSX Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi PPSX dan menyimpannya ke format file lain. Lihat semua format yang didukung di bawah" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-html/" name="PPSX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-png/" name="PPSX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-fodp/" name="PPSX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-gif/" name="PPSX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-odp/" name="PPSX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-otp/" name="PPSX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-pot/" name="PPSX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-potm/" name="PPSX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-potx/" name="PPSX TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-pps/" name="PPSX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-svg/" name="PPSX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}