---
title: PPT'yi C++ ile düzenleyin
url: /tr/cpp/editor/ppt/
keywords: PPT'yi Düzenle, PowerPoint'i Düzenle, PPT, PowerPoint, C++ API, C++ Kitaplığı
description: PPT'yi C++ ile düzenleyin. PowerPoint sunumunu düzenlemek için C++ kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PPT'yi C++ ile düzenleyin" h2="C++ kodunu kullanarak PPT'yi düzenlemek için yüksek hızlı ve platformlar arası C++ kitaplığı" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak PPT'yi düzenleyin" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/), sunumları işlemek ve düzenlemek için kullanılan güçlü bir C++ kitaplığıdır. Yeni bir metin satırı ekleyerek bir PPT sunumunu düzenleyebilirsiniz. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PPT'yi C++ ile düzenleyin" %}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/) kullanarak, yalnızca birkaç satır kodla bir PPT belgesine yeni bir metin satırı ekleyebilirsiniz.

{{% blocks/products/pf/agp/code-block title="PPT'yi düzenlemek için C++ kodu" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C++'da PPT nasıl düzenlenir?" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for C++** yükleyin. Bakınız [**Kurulum**](https://docs.aspose.com/slides/cpp/installation/).
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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}