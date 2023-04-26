---
title: Skydda ODP presentationsfiler med C++
url: /sv/cpp/protect/odp/
keywords: Skrivskydd ODP, kryptera en ODP, lås ODP presentation, skydda ODP
description: C++ källkod för att skydda ODP presentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Lås eller lösenordsskydda ODP med C++" h2="Bygg dina egna C++-appar för att skydda presentationsfiler med API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Skydda en ODP presentation via C++" %}}
Med Aspose.Slides for C++ kan du skydda din ODP-presentation från att öppnas eller ändras genom att ange ett lösenord. Sedan, för att öppna eller ändra den låsta presentationen, måste en användare ange lösenordet.
{{% blocks/products/pf/agp/code-block title="Kryptera en ODP presentation med C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ställa in skrivskydd till en ODP presentation med C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.odp", SaveFormat::Odp);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Så här lösenordsskyddar du ODP via C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Det här är stegen för att skydda ODP-filer." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda ODP med en instans av Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Skydda presentationen med ProtectionManager-klassen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Spara resultatet i formatet ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra skyddade format som stöds" subTitle="Med C++ kan du också skydda följande format:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/cpp/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}