---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Afficher ou modifier les métadonnées OTP avec C++
url: /fr/cpp/metadata/otp/
description: Affichez et modifiez les métadonnées OTP en C++. Utilisez Aspose.Slides for C++ pour mettre à jour les propriétés intégrées et personnalisées des présentations.
keywords: Modifier les métadonnées OTP, afficher les métadonnées OTP, modifier les propriétés OTP, afficher les propriétés OTP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Modifier les métadonnées OTP en C++" h2="Utilisez Aspose.Slides for C++ pour afficher et mettre à jour les propriétés intégrées et personnalisées des fichiers de présentation." related="FODP,ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modifier les propriétés OTP via C++" variant="code" %}}

Aspose.Slides for C++ permet de lire et de mettre à jour les métadonnées des fichiers OTP sans Microsoft PowerPoint. Utilisez l'objet [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) fourni par `Presentation::get_DocumentProperties` pour modifier des propriétés intégrées comme `Author` et `Title`, ou pour gérer des propriétés personnalisées avec `idx_set`, `GetCustomPropertyName` et `RemoveCustomProperty`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Modifier les propriétés intégrées OTP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.otp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.otp", SaveFormat::Otp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ajouter des propriétés personnalisées à OTP – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.otp");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.otp", SaveFormat::Otp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Comment afficher ou modifier les métadonnées OTP en C++" intro="Suivez ces étapes pour afficher ou modifier les métadonnées OTP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chargez le fichier OTP avec la classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenez l'objet `DocumentProperties` avec `get_DocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lisez ou mettez à jour des propriétés intégrées comme `Author` et `Title`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ajoutez, lisez ou supprimez des propriétés personnalisées avec `idx_set`, `GetCustomPropertyName` et `RemoveCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Conçu avec Aspose.Slides" title="Afficher et modifier les métadonnées OTP en ligne" description="L'application gratuite Aspose.Slides Metadata est conçue avec [Aspose.Slides for C++](https://products.aspose.com/slides/fr/cpp/), la même API que le code ci-dessus. Ouvrez-la et découvrez ce que l'API peut faire avec vos propres fichiers OTP." button="Ouvrir Aspose.Slides Metadata" note="[Toutes les applications gratuites](https://products.aspose.app/slides/family)" >}}
- Fonctionne dans votre navigateur, rien à installer.
- Voyez comment Aspose.Slides lit et écrit les propriétés avant d'écrire du code.
- Affichez et modifiez les propriétés intégrées et personnalisées de votre fichier OTP.
- Enregistrez et téléchargez le fichier mis à jour.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Autres formats de métadonnées pris en charge" subTitle="En C++, vous pouvez aussi gérer les métadonnées des formats suivants." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/fr/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
