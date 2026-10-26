---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Szöveg keresése PPTX bemutatókban Pythonnal
url: /hu/python-net/search/pptx/
description: Szöveg keresése PPTX bemutatókban Pythonnal és az Aspose.Slides segítségével.
keywords: szöveg keresése PPTX fájlban, szavak megtalálása PPTX fájlban, PPTX bemutató keresése Pythonnal
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Szöveg keresése PPTX bemutatókban Pythonnal" h2="Készítsen Python-alkalmazásokat, amelyek az Aspose.Slides segítségével keresnek szöveget PowerPoint-bemutatókban." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Szöveg keresése PPTX bemutatóban Pythonnal" variant="code" %}}

Az [Aspose.Slides for Python via .NET](/slides/hu/python-net/) segítségével a [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) metódussal megtalálhatja az egyes diák azon szövegkereteit, amelyek egy adott karakterláncot tartalmaznak.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szöveg keresése PPTX bemutatóban – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for slide in presentation.slides:
        matching_text_frames = slides.util.SlideUtil.get_text_boxes_contains_text(slide, "PowerPoint", False)

        for text_frame in matching_text_frames:
            print(text_frame.text)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Hogyan kereshet szöveget PPTX fájlban Pythonnal" intro="Az alábbi lépésekkel kereshet szöveget egy PPTX bemutatóban." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nyissa meg a PPTX fájlt a `Presentation` segítségével.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Haladjon végig a diákon, és mindegyikre hívja meg a [`SlideUtil.get_text_boxes_contains_text`](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/get_text_boxes_contains_text/) metódust.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Olvassa ki az egyes talált szövegkeretek `text` tulajdonságát.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Az Aspose.Slides segítségével készült" title="Szöveg keresése PPTX fájlokban online" description="Az ingyenes Aspose.Slides Search alkalmazás az [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/hu/python-net/) segítségével készült, ugyanazzal az API-val, mint a fenti kód. Nyissa meg, és nézze meg, mire képes az API a saját PPTX fájljaival." button="Aspose.Slides Search megnyitása" note="[Az összes ingyenes alkalmazás](https://products.aspose.app/slides/family)" >}}
- A böngészőben fut, semmit sem kell telepíteni.
- Nézze meg, hogyan talál szöveget az Aspose.Slides, mielőtt kódot írna.
- Keressen egyszerű szöveget vagy reguláris kifejezéseket a PPTX fájlban.
- Töltse le a találatokat szövegfájlként.
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="További támogatott formátumok kereséshez" subTitle="Pythonnal más támogatott bemutatóformátumokban is kereshet szöveget." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/hu/python-net/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
