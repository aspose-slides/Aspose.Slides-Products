---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Modifier PPT en C++
url: /fr/cpp/editor/ppt/
keywords: Modifier PPT, Modifier PowerPoint, PPT, PowerPoint, API C++, Bibliothèque C++
description: Modifier PPT en C++. Utiliser l'API de la bibliothèque C++ pour modifier la présentation PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Modifier PPT en C++" h2="Bibliothèque C++ haute vitesse et multiplateforme pour l'édition de PPT à l'aide de code C++" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifier PPT en C++" variant="code" %}}

En utilisant [**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/), vous pouvez ajouter une nouvelle ligne de texte à un document PPT avec seulement quelques lignes de code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code C++ pour l'édition de PPT" >}}
```cpp

auto pres = System::MakeObject<Presentation>(u"pres.ppt");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"pres.pdf", SaveFormat::Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifier le PPT à l'aide d'Aspose.Slides" %}}

[**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/) est une puissante bibliothèque C++ utilisée pour manipuler et modifier des présentations. Vous pouvez modifier une présentation PPT en y ajoutant une nouvelle ligne de texte.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment éditer PPT en C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez **Aspose.Slides pour C++**. Voir [**Installation**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez la bibliothèque comme référence dans votre projet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créez une instance de la classe Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez la présentation PPT que vous souhaitez modifier.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez une nouvelle ligne de texte.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier PowerPoint modifié.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Modifier d'autres fichiers" subTitle="Vous pouvez également modifier des fichiers dans d'autres formats" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
