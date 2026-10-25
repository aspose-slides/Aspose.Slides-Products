---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Přidání vodoznaku do prezentací ODP v C++
url: /cs/cpp/watermark/odp/
description: Přidávejte textové nebo obrázkové vodoznaky do prezentací ODP v C++. Pomocí Aspose.Slides for C++ umístíte vodoznaky na snímky prezentace.
keywords: přidat vodoznak do ODP, přidat textový vodoznak do ODP, přidat obrázkový vodoznak do ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Přidání vodoznaku do prezentace ODP v C++" h2="Pomocí Aspose.Slides for C++ přidávejte textové nebo obrázkové vodoznaky do souborů prezentací bez aplikace Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Přidání vodoznaku do prezentace ODP pomocí C++" variant="code" %}}

Aspose.Slides for C++ umožňuje přidávat do prezentací ODP textové nebo obrázkové vodoznaky. Přidejte tvar vodoznaku na předlohu snímků pomocí `AddAutoShape`, přidejte text pomocí `AddTextFrame` nebo tvar vyplňte obrázkem načteným přes `File::ReadAllBytes` a `AddImage`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Přidání textového vodoznaku do ODP v C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Přidání obrázkového vodoznaku do prezentace ODP v C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak přidat vodoznak do ODP v C++" intro="Pomocí těchto kroků přidáte do souborů ODP textový nebo obrázkový vodoznak." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor ODP pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vyberte předlohu snímků z kolekce `Presentation::get_Masters`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte tvar vodoznaku metodou `AddAutoShape`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přidejte text vodoznaku metodou `AddTextFrame` nebo nastavte obrázkovou výplň pomocí `AddImage`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte soubor s vodoznakem pomocí `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Vytvořeno pomocí Aspose.Slides" title="Přidávejte vodoznaky do souborů ODP online" description="Bezplatná aplikace Aspose.Slides Watermark je vytvořena pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cs/cpp/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory ODP." button="Otevřít Aspose.Slides Watermark" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides přidává vodoznaky, ještě než napíšete kód.
- Přidejte do svého souboru ODP textový nebo obrázkový vodoznak.
- Stáhněte soubor s vodoznakem.
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další formáty podporující vodoznaky" subTitle="V C++ můžete přidávat vodoznaky také do následujících formátů." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/watermark/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
