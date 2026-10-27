---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 4380
title: Odebrání anotací z ODP pomocí C++
url: /cs/cpp/annotation/odp/ 
description: Zdrojový kód C++ pro odebrání anotací z prezentací ODP.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Odebrání komentářů a autorů komentářů z ODP v C++" h2="Vytvářejte aplikace C++, které pomocí serverových API pracují s komentáři a autory v souborech prezentací." related="PPTX,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Odebrání komentářů z ODP pomocí C++" variant="code" %}}

Pomocí [Aspose.Slides for C++](/slides/cs/cpp/) odeberete komentáře a autory komentářů z prezentací ODP. Následující příklad vymaže komentáře každého autora z `get_CommentAuthors` a poté vyprázdní kolekci autorů komentářů.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Odstranění anotací z ODP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"example.odp");

// Delete all comments from the presentation.
for (auto author : presentation->get_CommentAuthors())
{
    author->get_Comments()->Clear();
}

// Delete all authors.
presentation->get_CommentAuthors()->Clear();

presentation->Save(u"output.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak odebrat komentáře z ODP pomocí C++" intro="Postupujte podle těchto kroků a odeberte komentáře a autory komentářů z prezentace ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Nainstalujte Aspose.Slides for C++. Viz [Instalace](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Načtěte soubor ODP pomocí třídy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Projděte autory komentářů z `get_CommentAuthors`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vymažte komentáře každého autora pomocí `get_Comments()->Clear()`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Vyprázdněte kolekci autorů komentářů.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Uložte aktualizovanou prezentaci pomocí `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="Vytvořeno pomocí Aspose.Slides" title="Odebrání komentářů z ODP online" description="Bezplatná aplikace Aspose.Slides Annotation je vytvořena pomocí [Aspose.Slides for C++](https://products.aspose.com/slides/cs/cpp/), stejného API jako ve výše uvedeném kódu. Otevřete ji a vyzkoušejte, co API dokáže s vašimi vlastními soubory ODP." button="Otevřít Aspose.Slides Annotation" note="[Všechny bezplatné aplikace](https://products.aspose.app/slides/family)" >}}
- Běží ve vašem prohlížeči, nic není třeba instalovat.
- Podívejte se, jak Aspose.Slides odebírá komentáře, ještě než napíšete kód.
- Odeberte všechny komentáře ze souboru ODP.
- Stáhněte vyčištěný soubor.
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Další podporované formáty pro anotace" subTitle="Pomocí C++ můžete odebrat anotace i z dalších formátů." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cs/cpp/annotation/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
