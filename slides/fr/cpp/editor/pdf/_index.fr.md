---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Modifier un PDF en C++
url: /fr/cpp/editor/pdf/
keywords: Modifier PDF, PDF, API C++, bibliothèque C++
description: Modifier un PDF en C++. Utiliser l'API de la bibliothèque C++ pour modifier un document PDF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Modifier un PDF en C++" h2="Bibliothèque C++ haute vitesse et multiplateforme pour l'édition de PDF à l'aide de code C++" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifier un PDF en C++" variant="code" %}}

En utilisant [**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/), vous pouvez ajouter une nouvelle ligne de texte à un document PDF avec seulement quelques lignes de code.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code C++ pour l'édition de PDF" >}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromPdf(u"document.pdf");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"document.pdf", SaveFormat::Pdf);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifier un PDF à l'aide d'Aspose.Slides" %}}

[**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/) est une puissante bibliothèque C++ utilisée pour manipuler et modifier des présentations, des documents PDF et d'autres fichiers. Vous pouvez modifier un document PDF en y ajoutant une nouvelle ligne de texte.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment éditer un PDF en C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez **Aspose.Slides pour C++**. Voir [**Installation**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez la bibliothèque comme référence dans votre projet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créez une instance de la classe Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le document PDF que vous souhaitez modifier.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez une nouvelle ligne de texte.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier PDF modifié.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Modifier d'autres fichiers" subTitle="Vous pouvez également modifier des fichiers dans d'autres formats" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
