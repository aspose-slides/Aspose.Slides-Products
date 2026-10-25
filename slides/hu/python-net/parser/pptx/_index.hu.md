---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Szöveg kinyerése PPTX fájlokból Pythonnal
url: /hu/python-net/parser/pptx/
description: Szöveg és szövegformázási részletek kinyerése PPTX bemutatókból Pythonnal.
keywords: PPTX elemzése Pythonnal, PPTX elemző Python, adatok kinyerése PPTX fájlból Pythonban, szöveg kinyerése PPTX fájlból Pythonnal
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Szöveg kinyerése PPTX bemutatókból Pythonnal" h2="Készítsen Python-alkalmazásokat, amelyek az Aspose.Slides segítségével szöveget és formázási részleteket nyernek ki PowerPoint-bemutatókból." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Szöveg kinyerése egy PPTX bemutatóból Pythonnal" variant="code" %}}

Az [**Aspose.Slides for Python via .NET**](/slides/hu/python-net/) a `SlideUtil` osztály statikus [`get_all_text_frames`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_all_text_frames/) metódusát kínálja. Ez a teljes bemutató `TextFrame` objektumait adja vissza, és a mintadiák szövegét is tartalmazhatja. Az alábbi példa szöveget és a kapcsolódó betűtípus-adatokat nyeri ki egy PPTX bemutatóból.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szöveg kinyerése egy PPTX bemutatóból – Python" >}}
```python
include_master_slides = True

with slides.Presentation("presentation.pptx") as presentation:
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Szöveg kinyerése PPTX fájlból Pythonnal lépésről lépésre" intro="Kövesse az alábbi lépéseket a szöveg kinyeréséhez egy PPTX fájlból." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a PPTX fájlt a `Presentation` osztállyal.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hívja meg a `SlideUtil.get_all_text_frames` metódust, és adja meg, hogy a mintadiák is szerepeljenek-e.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Járja be a visszaadott `TextFrame` objektumokat.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Járja be minden szövegkeret `paragraphs` gyűjteményét.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Járja be minden bekezdés `portions` gyűjteményét.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Olvassa ki az aktuális szövegrész `text` értékét és formázási tulajdonságait.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Az Aspose.Slides segítségével készült" title="Szöveg és képek kinyerése online" description="Az ingyenes Aspose.Slides Parser alkalmazás az [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hu/python-net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Parser megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan olvassa az Aspose.Slides a fájljait, mielőtt kódot írna.
- Töltsön fel egy PPTX fájlt, és kapja meg a szövegét és a képeit.
- Töltsön le mindent egyetlen ZIP-archívumban.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott elemzési formátumok" subTitle="Pythonnal más támogatott bemutatóformátumokból is kinyerhet szöveget." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/parser/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
