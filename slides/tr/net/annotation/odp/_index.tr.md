---
title: .NET kullanarak ODP Ek Açıklamasını kaldırın
weight: 4380
url: /tr/net/annotation/odp/ 
description: .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında ODP biçimi ek açıklamalarını silmek için C# kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C#'ta ODP'den Yorumları ve Yorum Yazarlarını Kaldırma" h2="Sunucu tarafı API'lerini kullanarak belge dosyalarındaki yorumları ve yazarları işlemek için kendi .NET uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Yorumları ODP'den C# ile Kaldır" %}}
Ek açıklamaları ODP dosyasından kaldırmak için zengin özelliklere sahip, güçlü ve kullanımı kolay [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net) API'sini kullanacağız. C# platformu için belge işleme API'si.
{{% blocks/products/pf/agp/code-block title="Ek Açıklamaları ODP'den Silme - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.odp"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Yorumları ODP'den C# aracılığıyla Kaldırma" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET**'i kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP'yi bir Presentation sınıfı örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Yüklenen ODP'nin tüm Yazarlarını yineleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bir yazarın tüm Yorumlarını kaldır
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonunda tüm Yazarları kaldır
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Ek Açıklama Biçimleri" subTitle="C# kullanarak, aşağıdakiler de dahil olmak üzere diğer biçimlere kolayca açıklama eklenebilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}