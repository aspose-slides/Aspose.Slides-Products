---
title: Java kullanarak PPTX Sunum Dosyalarını koruyun
url: /tr/java/protect/pptx/
keywords: Yazma Koruması PPTX, Bir PPTX Şifreleme, PPTX Sunumu Kilitleme, PPTX Koruma
description: PPTX Sunumunu korumak için Java kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java kullanarak PPTX Kilitleyin veya Parolayla Koruyun" h2="Sunucu tarafı API'lerini kullanarak sunum dosyalarını korumak için kendi Java uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Bir PPTX Sunumunu Java Aracılığıyla Koruma" %}}
Aspose.Slides for Java kullanarak, bir şifre belirleyerek PPTX sunumunuzu açılmaya veya değiştirilmeye karşı koruyabilirsiniz. Ardından, kilitli sunuyu açmak veya değiştirmek için kullanıcının parolayı sağlaması gerekir.
{{% blocks/products/pf/agp/code-block title="Bir PPTX Sunumunu Java kullanarak şifreleme" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Java kullanarak bir PPTX Sunumuna Yazma Koruması Ayarlama" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java Aracılığıyla PPTX Parola Koruması Nasıl Yapılır?" >}}

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

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Koruma Biçimleri" subTitle="Java kullanarak aşağıdaki biçimleri de koruyabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}