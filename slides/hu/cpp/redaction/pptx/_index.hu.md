---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX bemutatók kitakarása C++ használatával
url: /hu/cpp/redaction/pptx/
description: Takarjon ki PPTX bemutatókat C++ nyelven. Az Aspose.Slides for C++ segítségével bizalmas szöveget kereshet és cserélhet bemutatófájlokban.
keywords: PPTX kitakarása, szöveg keresése és cseréje PPTX fájlban, PPTX bemutató frissítése
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX kitakarása C++ használatával" h2="Az Aspose.Slides for C++ segítségével Microsoft PowerPoint nélkül kereshet és cserélhet bizalmas szöveget bemutatófájlokban." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPTX bemutató kitakarása C++ segítségével" variant="code" %}}

Az Aspose.Slides for C++ segítségével PPTX bemutatókat takarhat ki a diák bizalmas szövegének cseréjével. A `SlideUtil::FindAndReplaceText` és egy `Presentation` objektum segítségével keresse át a bemutatót, és cserélje le az egyező szöveget, mielőtt mentené a frissített fájlt.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX bemutató kitakarása C++ használatával" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan takarható ki egy PPTX fájl C++ segítségével" intro="Az alábbi lépésekkel takarhat ki egy PPTX bemutatót." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Töltse be a PPTX fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}A bizalmas szöveget a [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) metódussal keresse meg és cserélje le.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Mentse a kitakart fájlt a `SaveFormat::Pptx` értékkel.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Az Aspose.Slides segítségével készült" title="PPTX fájlok kitakarása online" description="Az ingyenes Aspose.Slides Redaction alkalmazás az [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Redaction megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan keres és cserél szöveget az Aspose.Slides, mielőtt kódot írna.
- Keressen és cseréljen szöveget a PPTX fájlban, akár reguláris kifejezésekkel is.
- Töltse le a kitakart fájlt.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok kitakaráshoz" subTitle="C++ használatával a következő formátumokat is kitakarhatja." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/cpp/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
