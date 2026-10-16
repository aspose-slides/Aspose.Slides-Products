---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convertir HTML en PPTX en C++
url: /fr/cpp/conversion/html-to-pptx/
keywords: Convertir HTML en PPTX, HTML en PPTX, PowerPoint, HTML, PPTX, API C++, Bibliothèque C++
description: Convertir HTML en PPTX en C++. Utiliser l'API de la bibliothèque C++ pour convertir HTML en PowerPoint
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convertir HTML en PPTX en C++" h2="Puissante API C++ multiplateforme pour convertir HTML en PPTX à l'aide de code C++" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir HTML en PPTX en C++" variant="code" %}}

En utilisant [**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/), vous pouvez convertir un document HTML en présentation PowerPoint avec seulement quelques lignes de code :

{{< blocks/products/pf/slides-design-update-10-2026/code title="Code C++ pour convertir HTML en PPTX" >}}
```cpp
auto presentation = System::MakeObject<Presentation>();
presentation->get_Slides()->RemoveAt(0);

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convertir HTML en PPTX en utilisant Aspose.Slides" %}}

[**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/) est une puissante bibliothèque C++ utilisée pour créer, convertir et manipuler des présentations PowerPoint, des PDF, des documents HTML et d'autres des dossiers. Lorsque vous convertissez HTML en PPTX, vous déplacez essentiellement le contenu d'un document HTML vers des diapositives dans une présentation PowerPoint.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment convertir HTML en PPTX en C++" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installez **Aspose.Slides pour C++**. Voir [**Installation**](https://docs.aspose.com/slides/cpp/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez la bibliothèque comme référence dans votre projet.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Créez une instance de la classe Presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le document HTML que vous souhaitez convertir en PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Enregistrez le fichier résultant en tant que présentation PPTX.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Convertisseur en ligne gratuit"
  description="[Comment convertir PPT en HTML en Python](https://products.aspose.com/slides/fr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres conversions PowerPoint prises en charge" subTitle="Vous pouvez également convertir des fichiers dans d'autres formats en PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/fr/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
