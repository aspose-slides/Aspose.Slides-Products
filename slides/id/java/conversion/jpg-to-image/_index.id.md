---
title: Konversikan JPG ke Image di Java
url: /id/java/conversion/jpg-to-image/
keywords: JPG ke Image, Konversikan JPG ke Image, Java API, Perpustakaan Java, JPG, Image
description: Konversikan JPG ke Image di Java. Gunakan Java library API untuk mengonversi file JPG ke Image
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konversikan JPG ke Image di Java" h2="Pustaka Java berkecepatan tinggi dan lintas platform yang membantu dalam mengembangkan aplikasi dengan kemampuan untuk membuat, menggabungkan, memeriksa, atau mengonversi file presentasi Microsoft PowerPoint dan OpenOffice tanpa menggunakan perangkat lunak apa pun seperti Microsoft atau Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan JPG ke Image di Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/id/java/) adalah library Java yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini memberikan cara yang fleksibel untuk mengonversi JPG ke Image. Menggunakan **Aspose.Slides untuk Java**, pengembang atau aplikasi apa pun dapat mengonversi file JPG ke Image hanya dengan beberapa baris kode Java.

Sebagai API pemrosesan dokumen modern, Aspose.Slides untuk Java mengekspor file JPG ke format file Image dengan cepat. Pustaka Aspose PowerPoint memungkinkan Anda mengonversi JPG ke Image dan banyak format file lainnya

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan JPG ke Image menggunakan Java" %}}
Untuk mengonversi JPG ke Image, Anda perlu membuat Presentasi dari file JPG dan menyimpannya sebagai Image.

{{% blocks/products/pf/agp/code-block title="Kode Java untuk mengonversi JPG menjadi Image" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.jpg")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara mengonversi JPG ke Image menggunakan Aspose.Slides untuk Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk mengonversi JPG ke Image di Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides for Java**](https://products.aspose.com/slides/id/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek Java Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file sumber JPG di Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan hasilnya sebagai file Image.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversikan JPG Ke Format Lain yang Didukung" subTitle="Anda juga dapat mengonversi JPG dan menyimpan ke format file lain. Lihat semua format yang didukung di bawah ini" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/jpg-to-png/" name="JPG TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/java/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}