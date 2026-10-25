---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Afficher ou modifier les métadonnées PPS avec C++
url: /fr/cpp/metadata/pps/
description: Affichez et modifiez les métadonnées PPS en C++. Utilisez Aspose.Slides for C++ pour mettre à jour les propriétés intégrées et personnalisées des présentations.
keywords: Modifier les métadonnées PPS, afficher les métadonnées PPS, modifier les propriétés PPS, afficher les propriétés PPS
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Modifier les métadonnées PPS en C++" h2="Utilisez Aspose.Slides for C++ pour afficher et mettre à jour les propriétés intégrées et personnalisées des fichiers de présentation." related="FODP,ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifier les propriétés PPS via C++" variant="code" %}}

Aspose.Slides for C++ permet de lire et de mettre à jour les métadonnées des fichiers PPS sans Microsoft PowerPoint. Utilisez l'objet [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) fourni par `Presentation::get_DocumentProperties` pour modifier des propriétés intégrées comme `Author` et `Title`, ou pour gérer des propriétés personnalisées avec `idx_set`, `GetCustomPropertyName` et `RemoveCustomProperty`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Modifier les propriétés intégrées PPS – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pps");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.pps", SaveFormat::Pps);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ajouter des propriétés personnalisées à PPS – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pps");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.pps", SaveFormat::Pps);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment afficher ou modifier les métadonnées PPS en C++" intro="Suivez ces étapes pour afficher ou modifier les métadonnées PPS." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier PPS avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenez l'objet `DocumentProperties` avec `get_DocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lisez ou mettez à jour des propriétés intégrées comme `Author` et `Title`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez, lisez ou supprimez des propriétés personnalisées avec `idx_set`, `GetCustomPropertyName` et `RemoveCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Conçu avec Aspose.Slides" title="Afficher et modifier les métadonnées PPS en ligne" description="L'application gratuite Aspose.Slides Metadata est conçue avec [Aspose.Slides for C++](https://products.aspose.com/slides/fr/cpp/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers PPS." button="Ouvrir Aspose.Slides Metadata" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides lit et écrit les propriétés avant d'écrire du code.
- Affichez et modifiez les propriétés intégrées et personnalisées de votre fichier PPS.
- Enregistrez et téléchargez le fichier mis à jour.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats de métadonnées pris en charge" subTitle="En C++, vous pouvez aussi gérer les métadonnées des formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
