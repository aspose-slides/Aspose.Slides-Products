---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Maskera PPT-presentationer med C++
url: /sv/cpp/redaction/ppt/
description: Maskera PPT-presentationer i C++. Använd Aspose.Slides for C++ för att söka efter och ersätta känslig text i presentationsfiler.
keywords: maskera PPT, sök och ersätt text i PPT, uppdatera PPT-presentation
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Maskera PPT med C++" h2="Använd Aspose.Slides for C++ för att söka efter och ersätta känslig text i presentationsfiler utan Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Maskera en PPT-presentation via C++" variant="code" %}}

Med Aspose.Slides for C++ kan du maskera PPT-presentationer genom att ersätta känslig text på bilderna. Använd `SlideUtil::FindAndReplaceText` med ett `Presentation`-objekt för att söka igenom presentationen och ersätta matchande text innan du sparar den uppdaterade filen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Maskera en PPT-presentation med C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Så maskerar du PPT via C++" intro="Följ de här stegen för att maskera en PPT-presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Läs in PPT-filen med klassen `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Använd metoden [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) för att söka efter och ersätta känslig text.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Spara den maskerade filen med `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Byggd med Aspose.Slides" title="Maskera PPT-filer online" description="Den kostnadsfria appen Aspose.Slides Redaction är byggd med [Aspose.Slides for C++](https://products.aspose.com/slides/sv/cpp/), samma API som i koden ovan. Öppna den och se vad API:et kan göra med dina egna PPT-filer." button="Öppna Aspose.Slides Redaction" note="[Alla gratisappar](https://products.aspose.app/slides/family)" >}}
- Körs i webbläsaren, inget att installera.
- Se hur Aspose.Slides söker efter och ersätter text innan du skriver kod.
- Sök efter och ersätt text i din PPT-fil, även med reguljära uttryck.
- Ladda ned den maskerade filen.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andra format som stöds för maskering" subTitle="Med C++ kan du även maskera följande format." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/sv/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
