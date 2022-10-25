---
title: Gabungkan PDF, PPT, PPTX dan Banyak Format File Lainnya Menggunakan C#
url: /id/net/merger/
keywords: Gabung, Gabung, PowerPoint, Presentasi, C#, .NET, Aspose
description: Gabungkan banyak file dalam C# PPT, PPTX, ODP, PDF, PNG, JPG, dan banyak lagi.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Gabungkan Powerpoint, PDF, PPT atau dokumen lain bersama-sama dalam C#" h2="Pustaka C# berkecepatan tinggi untuk menggabungkan PPT, PPTX, PDF, PNG, JPEG, dan format lainnya." >}}

{{% blocks/products/pf/feature-page-section h2="Gabungkan PPT, PPTX, PDF menggunakan C#" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/id/net/) adalah library C# yang andal untuk membuat dan memanipulasi file presentasi. Selain itu, ini menyediakan cara yang fleksibel untuk menggabungkan beberapa presentasi PPT/PPTX. Saat Anda menggabungkan satu presentasi ke presentasi lainnya, Anda secara efektif menggabungkan slide mereka dalam satu presentasi untuk mendapatkan satu file. Aspose.Slides memungkinkan Anda menggabungkan dua presentasi dengan cara yang berbeda. Anda dapat menggabungkan presentasi dengan semua bentuk, gaya, teks, pemformatan, komentar, animasi, dll. tanpa harus khawatir kehilangan kualitas atau data.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Gabungkan presentasi PowerPoint dalam C#" %}}
Untuk menggabungkan presentasi PowerPoint, Anda perlu mengkloning slide dari satu presentasi ke presentasi lainnya.

{{% blocks/products/pf/agp/code-block title="Gabungkan file PPTX menggunakan C#" offSpacer="true" %}}

```csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        foreach (ISlide slide in presentation2.Slides)
        {
            // Merge slides from source to target 
            presentation1.Slides.AddClone(slide);
        }
    }
    // Save the presentation
    presentation1.Save("merged-presentation.pptx", Export.SaveFormat.Pptx);
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Gabungkan Presentasi dengan Slide Master menggunakan C#" %}}
Kode C# ini menunjukkan bagaimana menggabungkan beberapa presentasi menjadi satu dan menerapkan gaya dari template presentasi master slide. Jadi, presentasi hasil akan mempertahankan pemformatan sumber yang sama dan akan berisi pemformatan dari slide master presentasi lain.

{{% blocks/products/pf/agp/code-block title="Gabungkan beberapa PPT menjadi satu di C#" offSpacer="true" %}}

``` csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        // Merge first two slides only using slide master
        presentation1.Slides.AddClone(presentation2.Slides[0], presentation1.Masters[0], true);
        presentation1.Slides.AddClone(presentation2.Slides[1], presentation1.Masters[0], true);
    }
    presentation1.Save("merged-presentation-master.pptx", Export.SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cara menggabungkan Presentasi menggunakan Aspose.Slides untuk .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ini adalah langkah-langkah untuk menggabungkan dua file PPTX dan menyimpan hasilnya sebagai PDF di .NET." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instal [**Aspose.Slides untuk .NET**](https://docs.aspose.com/slides/net/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Tambahkan referensi perpustakaan (impor perpustakaan) ke proyek C# Anda.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Buka file PPTX sumber di C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gabungkan file PPTX menggunakan metode **AddClone**.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Simpan presentasi dan dapatkan hasilnya sebagai file PDF tunggal.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Format yang Didukung Lainnya Untuk Digabung" subTitle="Anda juga dapat menggabungkan format file lainnya. Lihat format lain yang didukung di bawah." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/id/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}