---
title: Skydda PPT presentationsfiler med Java
url: /sv/java/protect/ppt/
keywords: Skrivskydd PPT, kryptera en PPT, lås PPT presentation, skydda PPT
description: Java källkod för att skydda PPT presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Lås eller lösenordsskydda PPT med Java" h2="Bygg dina egna Java-appar för att skydda presentationsfiler med API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Skydda en PPT presentation via Java" %}}
Med Aspose.Slides for Java kan du skydda din PPT-presentation från att öppnas eller ändras genom att ange ett lösenord. Sedan, för att öppna eller ändra den låsta presentationen, måste en användare ange lösenordet.
{{% blocks/products/pf/agp/code-block title="Kryptera en PPT presentation med Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ställa in skrivskydd till en PPT presentation med Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Så här lösenordsskyddar du PPT via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att skydda PPT-filer." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda PPT med en instans av Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skydda presentationen med ProtectionManager-klassen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet i formatet PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra skyddade format som stöds" subTitle="Med Java kan du också skydda följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/java/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}