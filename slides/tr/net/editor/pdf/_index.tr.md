---
title: PDF'yi C# ile düzenleyin
url: /tr/net/editor/pdf/
keywords: PDF, PDF, C# API, .NET Kitaplığını Düzenle
description: PDF'yi C# ile düzenleyin. PDF belgesini düzenlemek için .NET kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PDF'yi C# ile düzenleyin" h2="NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında C# kodu kullanarak PDF'yi düzenlemek için güçlü platformlar arası .NET API'si" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak PDF'yi düzenleyin" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/), sunumları, PDF belgelerini ve diğer dosyaları işlemek ve düzenlemek için kullanılan güçlü bir .NET kitaplığıdır. Yeni bir metin satırı ekleyerek bir PDF belgesini düzenleyebilirsiniz. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PDF'yi C# ile düzenleyin" %}}
[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/) kullanarak, yalnızca birkaç satır kodla bir PDF belgesine yeni bir metin satırı ekleyebilirsiniz.

{{% blocks/products/pf/agp/code-block title="PDF'yi düzenlemek için C# kodu" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // remove default empty slide
    pres.Slides.AddFromPdf("doc.pdf");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("doc.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C#'ta PDF nasıl düzenlenir" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET**'i kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kütüphaneyi projenize referans olarak ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation sınıfının bir örneğini oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Düzenlemek istediğiniz PDF belgesini yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Yeni bir metin satırı ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Değiştirilen PDF dosyasını kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Diğer dosyaları düzenle" subTitle="Diğer formatlardaki dosyaları da düzenleyebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}