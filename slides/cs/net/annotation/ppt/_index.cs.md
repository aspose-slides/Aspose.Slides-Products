---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Odebrání anotací z PPT pomocí .NET
url: /cs/net/annotation/ppt/ 
description: Odeberte komentáře a autory komentářů z prezentací PPT v C#.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Odebrání komentářů a autorů komentářů z PPT v C#" h2="Vytvářejte aplikace .NET, které pomocí serverových API pracují s komentáři a autory v souborech prezentací." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Odebrání komentářů z PPT pomocí C#" variant="code" %}}

Pomocí [Aspose.Slides for .NET](/slides/cs/net/) odeberete komentáře a autory komentářů ze souborů prezentací PPT. Následující příklad vyprázdní kolekci `Comments` každého autora a poté kolekci `CommentAuthors` prezentace.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Odstranění anotací z PPT – C#" >}}
```cs
using var presentation = new Presentation("example.ppt");

foreach (var commentAuthor in presentation.CommentAuthors)
{
    commentAuthor.Comments.Clear();
}

presentation.CommentAuthors.Clear();

presentation.Save("example_out.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak odebrat komentáře z PPT pomocí C#" intro="Postupujte podle těchto kroků a odeberte komentáře a autory komentářů z prezentace PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte Aspose.Slides for .NET. Viz [Instalace](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor PPT pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte kolekci `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vyprázdněte kolekci `Comments` každého autora komentářů.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vyprázdněte kolekci `CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte aktualizovanou prezentaci pomocí `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Vytvořeno pomocí Aspose.Slides" title="Odebrání komentářů z PPT online" description="Bezplatná aplikace Aspose.Slides Annotation je vytvořena pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/cs/net/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory PPT." button="Otevřít Aspose.Slides Annotation" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides odebírá komentáře, ještě než napíšete kód.
- Odeberte všechny komentáře ze souboru PPT.
- Stáhněte vyčištěný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro anotace" subTitle="Pomocí C# můžete odebrat anotace i z dalších formátů." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/net/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
