---
title: PPT'yi C# ile düzenleyin
url: /tr/net/editor/ppt/
keywords: PPT'yi Düzenle, PowerPoint'i Düzenle, PPT, PowerPoint, C# API, .NET Kitaplığı
description: PPT'yi C# ile düzenleyin. PowerPoint sunumunu düzenlemek için .NET kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PPT'yi C# ile düzenleyin" h2="NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında C# kodu kullanarak PPT'yi düzenlemek için güçlü platformlar arası .NET API'si" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak PPT'yi düzenleyin" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/), sunumları işlemek ve düzenlemek için kullanılan güçlü bir .NET kitaplığıdır. Yeni bir metin satırı ekleyerek bir PPT sunumunu düzenleyebilirsiniz. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PPT'yi C# ile düzenleyin" %}}
[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/) kullanarak, yalnızca birkaç satır kodla bir PPT belgesine yeni bir metin satırı ekleyebilirsiniz.

{{% blocks/products/pf/agp/code-block title="PPT'yi düzenlemek için C# kodu" offSpacer="true" %}}
```cs
using (Presentation presentation = new Presentation("pres.ppt"))
{
    AutoShape shape = (AutoShape)presentation.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";
    presentation.Save("pres.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C#'ta PPT nasıl düzenlenir?" >}}


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
Düzenlemek istediğiniz PPT sunumunu yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Yeni bir metin satırı ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Değiştirilen PowerPoint dosyasını kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Diğer dosyaları düzenle" subTitle="Diğer formatlardaki dosyaları da düzenleyebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}