---
title: C++ kullanarak PPTX Sunum Dosyalarını koruyun
url: /tr/cpp/protect/pptx/
keywords: Yazma Koruması PPTX, Bir PPTX Şifreleme, PPTX Sunumu Kilitleme, PPTX Koruma
description: PPTX Sunumunu korumak için C++ kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++ kullanarak PPTX Kilitleyin veya Parolayla Koruyun" h2="Sunucu tarafı API'lerini kullanarak sunum dosyalarını korumak için kendi C++ uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Bir PPTX Sunumunu C++ Aracılığıyla Koruma" %}}
Aspose.Slides for C++ kullanarak, bir şifre belirleyerek PPTX sunumunuzu açılmaya veya değiştirilmeye karşı koruyabilirsiniz. Ardından, kilitli sunuyu açmak veya değiştirmek için kullanıcının parolayı sağlaması gerekir.
{{% blocks/products/pf/agp/code-block title="Bir PPTX Sunumunu C++ kullanarak şifreleme" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ kullanarak bir PPTX Sunumuna Yazma Koruması Ayarlama" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++ Aracılığıyla PPTX Parola Koruması Nasıl Yapılır?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PPTX dosyalarını Koruma adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX dosyasını bir Sunum örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ProtectionManager sınıfını kullanarak sunuyu koruyun
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPTX biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Koruma Biçimleri" subTitle="C++ kullanarak aşağıdaki biçimleri de koruyabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}