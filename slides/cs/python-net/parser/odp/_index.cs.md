---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Extrakce textu ze souborů ODP v Pythonu
url: /cs/python-net/parser/odp/
description: Extrahujte text a podrobnosti o formátování textu z prezentací ODP v Pythonu.
keywords: parsování ODP v Pythonu, parser ODP Python, extrakce dat z ODP v Pythonu, extrakce textu z ODP v Pythonu
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Extrakce textu z prezentací ODP v Pythonu" h2="Vytvářejte aplikace v Pythonu, které pomocí Aspose.Slides extrahují text a podrobnosti o formátování z prezentací OpenDocument." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Extrakce textu z prezentace ODP v Pythonu" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/cs/python-net/) nabízí statickou metodu [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) třídy `SlideUtil`. Vrací objekty `TextFrame` z celé prezentace a může zahrnout i text z předloh snímků. Následující příklad extrahuje text a související údaje o písmu z prezentace ODP.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Extrakce textu z prezentace ODP – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.odp") as presentation:
    text_frames = slides.util.SlideUtil.get_all_text_frames(presentation, include_master_slides)

    for text_frame in text_frames:
        for paragraph in text_frame.paragraphs:
            for portion in paragraph.portions:
                print(portion.text)

                font_height = portion.portion_format.font_height
                print(font_height)

                latin_font = portion.portion_format.latin_font
                if latin_font is not None:
                    print(latin_font.font_name)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak extrahovat text z ODP v Pythonu" intro="Pomocí těchto kroků extrahujete text ze souboru ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor ODP pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `SlideUtil.get_all_text_frames` a určete, zda zahrnout předlohy snímků.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte vrácené objekty `TextFrame`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte kolekci `paragraphs` každého textového rámce.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte kolekci `portions` každého odstavce.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Přečtěte `text` a vlastnosti formátování aktuální části textu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Vytvořeno pomocí Aspose.Slides" title="Extrakce textu a obrázků online" description="Bezplatná aplikace Aspose.Slides Parser je vytvořena pomocí [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/cs/python-net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory ODP." button="Otevřít Aspose.Slides Parser" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides čte vaše soubory, ještě než napíšete kód.
- Nahrajte soubor ODP a získejte jeho text a obrázky.
- Stáhněte vše jako jeden archiv ZIP.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro parsování" subTitle="V Pythonu můžete extrahovat text i z dalších podporovaných formátů prezentací." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/parser/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
