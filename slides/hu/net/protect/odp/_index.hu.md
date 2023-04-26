---
title: A ODP prezentációs fájlok védelme a .NET használatával
url: /hu/net/protect/odp/
keywords: Írásvédelem ODP, ODP titkosítása, ODP bemutató zárolása, ODP védelme
description: C# forráskód a ODP prezentáció védelmére.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zárolás vagy jelszavas védelem ODP a C# használatával" h2="Készítse el saját .NET alkalmazásait a prezentációs fájlok védelméhez szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="A ODP prezentáció védelme a C# segítségével" %}}
A Aspose.Slides for .NET használatával jelszó megadásával megvédheti ODP prezentációját a megnyitástól vagy módosítástól. Ezután a zárolt bemutató megnyitásához vagy módosításához a felhasználónak meg kell adnia a jelszót.
{{% blocks/products/pf/agp/code-block title="ODP prezentáció titkosítása a C# használatával" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Írásvédelem beállítása ODP prezentációra a C# használatával" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="A ODP jelszavas védelme a C# segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Ezek a lépések a ODP fájlok védelméhez." >}}

{{< blocks/products/pf/agp/step-autogen >}}
A ODP betöltése a Presentation egy példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Védje a prezentációt a ProtectionManager osztály segítségével
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az eredmény mentése ODP formátumban
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott védelmi formátumok" subTitle="A C# használatával a következő formátumokat is védheti:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}