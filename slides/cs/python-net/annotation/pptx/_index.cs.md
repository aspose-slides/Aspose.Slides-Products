---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Odebrání komentářů z PPTX v Pythonu
url: /cs/python-net/annotation/pptx/ 
description: Odeberte komentáře a autory komentářů z prezentací PPTX v Pythonu pomocí Aspose.Slides for Python via .NET.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Odebrání komentářů a autorů komentářů z PPTX v Pythonu" h2="Pomocí Aspose.Slides for Python via .NET odeberete komentáře prezentace i jejich autory." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Odebrání komentářů z PPTX pomocí Pythonu" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/cs/python-net/) poskytuje přístup ke komentářům a autorům komentářů uloženým v prezentaci PPTX. Načtěte soubor pomocí `Presentation`, vyprázdněte kolekci `comments` každého autora, vyprázdněte `comment_authors` a uložte výsledek ve formátu PPTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Odebrání komentářů z PPTX v Pythonu" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    for comment_author in presentation.comment_authors:
        comment_author.comments.clear()

    presentation.comment_authors.clear()
    presentation.save("presentation-without-comments.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak odebrat komentáře z PPTX pomocí Pythonu" intro="Postupujte podle těchto kroků a odeberte všechny komentáře a autory komentářů z prezentace PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte [Aspose.Slides for Python via .NET](https://docs.aspose.com/slides/python-net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Otevřete soubor PPTX pomocí `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte `comment_authors` a vyprázdněte kolekci `comments` každého autora.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vyprázdněte kolekci `comment_authors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zavolejte `save` se `SaveFormat.PPTX` a zapište aktualizovanou prezentaci PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Vytvořeno pomocí Aspose.Slides" title="Odebrání komentářů z PPTX online" description="Bezplatná aplikace Aspose.Slides Annotation je vytvořena pomocí [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/cs/python-net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPTX." button="Otevřít Aspose.Slides Annotation" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides odebírá komentáře, ještě než napíšete kód.
- Odeberte všechny komentáře ze souboru PPTX.
- Stáhněte vyčištěný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro anotace" subTitle="Pomocí Pythonu můžete odebrat anotace i z dalších formátů." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/python-net/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
