---
title: C++ kullanarak PPTX Sunum Dosyalarının Kilidini Açın
url: /tr/cpp/unlock/pptx/
keywords: PPTX Yazma Korumasını Kaldırma, Bir PPTX Şifresini Çözme, PPTX Sunumunun Kilidini Kaldırma, PPTX Korumasını Kaldırma
description: PPTX Sunumundan korumayı kaldırmak için C++ kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++ kullanarak PPTX kilidini açın" h2="PowerPoint'ten şifreleri kaldırmak ve sunucu tarafı API'lerini kullanarak sunum dosyalarının şifresini çözmek için kendi C++ uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="C++ Aracılığıyla PPTX Sunumundan Şifrelemeyi Kaldırma" %}}
Aspose.Slides for C++ kullanarak, PPTX sunumundaki şifrelemeyi veya parola korumasını kaldırabilirsiniz. Bu şekilde, kullanıcılar kısıtlama olmadan PPTX sunumuna erişebilir veya sunuyu değiştirebilir.
{{% blocks/products/pf/agp/code-block title="C++ kullanarak PPTX Şifre Korumasını devre dışı bırakma" offSpacer="true" %}}

```cpp

auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"123123");
    
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"encryption-removed.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Kullanarak PPTX Sunumundan Yazma Korumasını Kaldırma" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++ Aracılığıyla PPTX Ürününün Şifresini Kaldırma" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PPTX dosyalarından korumayı kaldırma adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX dosyasını bir Sunum örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ProtectionManager sınıfını kullanarak Yazma Korumasını kaldırın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPTX biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Formatlar" subTitle="C++ kullanarak, aşağıdaki biçimlerden de korumayı kaldırabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}