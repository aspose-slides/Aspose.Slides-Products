---
title: C++ kullanarak PPT Ek Açıklamasını kaldırın
weight: 4380
url: /tr/cpp/annotation/ppt/ 
description: PPT'den açıklamaları silmek için C++ kaynak kodu
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++'da PPT'den Yorumları ve Yorum Yazarlarını Kaldırma" h2="Sunucu tarafı API'lerini kullanarak belge dosyalarındaki yorumları ve yazarları işlemek için kendi C++ uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Yorumları C++ aracılığıyla PPT'den kaldırın" %}}
Ek açıklamaları PPT dosyasından kaldırmak için zengin özelliklere sahip, güçlü ve kullanımı kolay [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/) API'sini kullanacağız. C++ platformu için belge işleme API'si.
{{% blocks/products/pf/agp/code-block title="Açıklamaları PPT'den Sil - C++" offSpacer="true" %}}

```cpp

using namespace Aspose::Slides;
using namespace Aspose::Slides::Export;
using namespace System::Drawing;

auto presentation = System::MakeObject<Presentation>(u"example.ppt");

// Deletes all comments from the presentation
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}
        
// Deletes all authors
presentation->get_CommentAuthors()->Clear();
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="C++ aracılığıyla PPT'den Yorumlar Nasıl Kaldırılır" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for C++** yükleyin. Bakınız [**Kurulum**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT'yi bir Presentation sınıfı örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Yüklenen PPT'nin tüm Yazarları üzerinde yineleme yapın
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

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Ek Açıklama Biçimleri" subTitle="C++ kullanılarak, aşağıdakiler de dahil olmak üzere diğer biçimlere kolayca açıklama eklenebilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}