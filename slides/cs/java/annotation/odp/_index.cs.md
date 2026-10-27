---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1790
title: Odebrání anotací z ODP pomocí Javy
url: /cs/java/annotation/odp/ 
description: Odeberte komentáře a autory komentářů z prezentací ODP v Javě pomocí Aspose.Slides for Java.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Odebrání komentářů a autorů komentářů z ODP v Javě" h2="Pomocí Aspose.Slides for Java odeberete komentáře a autory komentářů ze souborů prezentací." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Odebrání komentářů z ODP pomocí Javy" variant="code" %}}

Aspose.Slides for Java umožňuje odebrat komentáře a autory komentářů z prezentací ODP. Načtěte soubor pomocí třídy `Presentation`, projděte objekty `ICommentAuthor` z `getCommentAuthors`, vymažte jejich komentáře a uložte aktualizovanou prezentaci.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Odstranění anotací z ODP – Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak odebrat komentáře z ODP pomocí Javy" intro="Postupujte podle těchto kroků a odeberte komentáře a autory komentářů z prezentace ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte Aspose.Slides for Java. Viz [Instalace](https://docs.aspose.com/slides/java/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor ODP pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte objekty `ICommentAuthor` z `getCommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vymažte komentáře každého autora pomocí `getComments().clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vyprázdněte kolekci autorů komentářů a uložte aktualizovaný soubor ODP.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Vytvořeno pomocí Aspose.Slides" title="Odebrání komentářů z ODP online" description="Bezplatná aplikace Aspose.Slides Annotation je vytvořena pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/cs/java/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory ODP." button="Otevřít Aspose.Slides Annotation" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides odebírá komentáře, ještě než napíšete kód.
- Odeberte všechny komentáře ze souboru ODP.
- Stáhněte vyčištěný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro anotace" subTitle="Pomocí Javy můžete odebrat anotace i z dalších formátů." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/annotation/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
