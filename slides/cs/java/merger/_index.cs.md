---
title: Sloučit PDF, PPT, PPTX a mnoho dalších formátů souborů pomocí Java
url: /cs/java/merger/
keywords: Sloučení, připojení, PowerPoint, prezentace, Java, Aspose
description: Sloučení více souborů v Java PPT, PPTX, ODP, PDF, PNG, JPG a mnoha dalších.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Sloučit Powerpoint, PDF, PPT nebo jiné dokumenty dohromady v Javě" h2="Vysokorychlostní Java knihovna pro sloučení PPT, PPTX, PDF, PNG, JPEG a dalších formátů." >}}

{{% blocks/products/pf/feature-page-section h2="Sloučit PPT, PPTX, PDF pomocí Javy" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/cs/java/) je výkonná Java knihovna pro vytváření a manipulaci s prezentačními soubory. Navíc poskytuje flexibilní způsoby, jak kombinovat více PPT/PPTX prezentací. Když sloučíte jednu prezentaci do druhé, efektivně kombinujete jejich snímky do jedné prezentace, abyste získali jeden soubor. Aspose.Slides umožňuje sloučit dvě prezentace různými způsoby. Můžete sloučit prezentace se všemi jejich tvary, styly, texty, formátováním, komentáři, animacemi atd., aniž byste se museli obávat ztráty kvality nebo dat.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Sloučit PowerPoint prezentace v Javě" %}}
Chcete-li sloučit prezentace PowerPoint, budete muset naklonovat snímky z jedné prezentace do druhé.

{{% blocks/products/pf/agp/code-block title="Sloučit soubory PPTX pomocí Java" offSpacer="true" %}}

```java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge slides
for (ISlide slide : presentation2.getSlides()) {
	// Merge slides from source to target
	presentation1.getSlides().addClone(slide);
}

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Sloučit prezentace s Slide Master pomocí Java" %}}
Tento kód Java ukazuje, jak sloučit několik prezentací do jedné a použít styly ze šablony prezentace předlohy snímků. Takže výsledná prezentace si zachová stejné zdrojové formátování a bude obsahovat formátování z hlavního snímku jiné prezentace.

{{% blocks/products/pf/agp/code-block title="Sloučit více PPT do jednoho v Javě" offSpacer="true" %}}

``` java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge first two slides only using slide master
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(0), presentation1.getMasters().get_Item(0), true);
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(1), presentation1.getMasters().get_Item(0), true);

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Jak sloučit prezentace pomocí Aspose.Slides pro Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Toto jsou kroky ke sloučení dvou souborů PPTX a uložení výsledku jako PDF v Javě." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Nainstalujte [**Aspose.Slides for Java**](https://docs.aspose.com/slides/java/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Přidejte odkaz na knihovnu (importujte knihovnu) do svého projektu Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Otevřete zdrojové soubory PPTX v Javě.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinujte soubory PPTX pomocí metody **addClone**.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Uložte prezentaci a získejte výsledek jako jeden soubor PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty ke sloučení" subTitle="Můžete také kombinovat jiné formáty souborů. Další podporované formáty naleznete níže." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/java/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}