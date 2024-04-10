---
title: Konversikan POTM ke BMP dalam JavaScript
url: /id/nodejs-net/conversion/potm-to-bmp/
keywords: POTM ke BMP, Konversi POTM ke BMP, API Node.js, Pustaka JavaScript, POTM, BMP
description: Konversikan POTM ke BMP dalam JavaScript. Gunakan API perpustakaan Node.js untuk mengonversi file POTM ke BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan POTM ke BMP dalam JavaScript" h2="Aspose.Slides untuk Node.js melalui .NET adalah pustaka yang kuat dan mudah digunakan yang memungkinkan Anda mengonversi presentasi PowerPoint ke berbagai format dalam JavaScript. Ini mendukung semua elemen dan format presentasi dan menyediakan API yang kaya untuk mengakses dan memodifikasinya. Ini juga memungkinkan Anda mengekspor slide Anda ke berbagai format untuk diproses atau dibagikan lebih lanjut." >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan POTM ke BMP di Node.js" %}}

[**Aspose.Slides untuk Node.js melalui .NET**](https://products.aspose.com/slides/id/nodejs-net/) adalah pustaka Node.js yang canggih untuk membuat dan memanipulasi file presentasi. Selain itu, ini menyediakan cara yang fleksibel untuk mengonversi POTM ke BMP. Menggunakan **Aspose.Slides untuk Node.js melalui .NET**, pengembang atau aplikasi mana pun dapat mengonversi file POTM ke BMP hanya dengan beberapa baris kode.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk Node.js melalui .NET mengekspor file POTM ke format file BMP dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi POTM ke BMP dan banyak format file lainnya

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan POTM ke BMP menggunakan JavaScript" %}}
Untuk mengonversi POTM ke BMP, Anda perlu membuat Presentasi dari file POTM dan menyimpannya sebagai BMP.

{{% blocks/products/pf/agp/code-block title="Kode JavaScript untuk mengubah POTM menjadi BMP" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.potm");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".bmp", ImageFormat.Bmp); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara mengonversi POTM ke BMP menggunakan Aspose.Slides untuk Node.js melalui .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Untuk mengonversi POTM ke BMP menggunakan Aspose.Slides untuk Node.js melalui .NET, Anda perlu mengimpor paket dalam file JavaScript Anda dan membuat instance kelas Presentation. Kelas Presentation mewakili dokumen PowerPoint dan menyediakan metode untuk mengakses dan memanipulasi elemen-elemennya." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides untuk Node.js melalui .NET**](https://products.aspose.com/slides/id/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Node.js Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file sumber POTM di Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasil sebagai file BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversikan POTM Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi POTM dan menyimpannya ke format file lain. Lihat semua format yang didukung di bawah" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-pptx/" name="POTM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-ppt/" name="POTM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-pdf/" name="POTM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-html/" name="POTM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-png/" name="POTM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-jpg/" name="POTM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-fodp/" name="POTM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-gif/" name="POTM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-odp/" name="POTM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-otp/" name="POTM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-pot/" name="POTM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-potx/" name="POTM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-pps/" name="POTM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-ppsm/" name="POTM TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-ppsx/" name="POTM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-pptm/" name="POTM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-svg/" name="POTM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/nodejs-net/conversion/potm-to-tiff/" name="POTM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}