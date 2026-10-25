---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ver o editar los metadatos de POTM con C++
url: /es/cpp/metadata/potm/
description: Vea y edite los metadatos de POTM en C++. Use Aspose.Slides for C++ para actualizar las propiedades integradas y personalizadas de las presentaciones.
keywords: Editar metadatos de POTM, ver metadatos de POTM, editar propiedades de POTM, ver propiedades de POTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Editar metadatos de POTM con C++" h2="Use Aspose.Slides for C++ para ver y actualizar las propiedades integradas y personalizadas de los archivos de presentación." related="FODP,ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modificar propiedades de POTM con C++" variant="code" %}}

Aspose.Slides for C++ permite leer y actualizar los metadatos de archivos POTM sin Microsoft PowerPoint. Use el objeto [`DocumentProperties`](https://reference.aspose.com/slides/cpp/aspose.slides/documentproperties/) que proporciona `Presentation::get_DocumentProperties` para cambiar propiedades integradas como `Author` y `Title`, o para administrar propiedades personalizadas con `idx_set`, `GetCustomPropertyName` y `RemoveCustomProperty`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Modificar propiedades integradas de POTM – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.potm");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->set_Author(u"New Author");
documentProperties->set_Title(u"New Title");

presentation->Save(u"updated-presentation.potm", SaveFormat::Potm);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Agregar propiedades personalizadas a POTM – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.potm");
auto documentProperties = presentation->get_DocumentProperties();

documentProperties->idx_set(u"Department", ObjectExt::Box<String>(u"Sales"));
documentProperties->idx_set(u"Project", ObjectExt::Box<String>(u"Metadata Update"));
documentProperties->idx_set(u"Revision", ObjectExt::Box<int32_t>(3));

auto customPropertyName = documentProperties->GetCustomPropertyName(2);
documentProperties->RemoveCustomProperty(customPropertyName);

presentation->Save(u"updated-custom-properties.potm", SaveFormat::Potm);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo ver o editar los metadatos de POTM en C++" intro="Siga estos pasos para ver o editar los metadatos de POTM." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo POTM con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Obtenga el objeto `DocumentProperties` con `get_DocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Lea o actualice propiedades integradas como `Author` y `Title`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agregue, lea o elimine propiedades personalizadas con `idx_set`, `GetCustomPropertyName` y `RemoveCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Creado con Aspose.Slides" title="Ver y editar metadatos de POTM en línea" description="La aplicación gratuita Aspose.Slides Metadata está creada con [Aspose.Slides for C++](https://products.aspose.com/slides/es/cpp/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos POTM." button="Abrir Aspose.Slides Metadata" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides lee y escribe propiedades antes de escribir código.
- Vea y edite las propiedades integradas y personalizadas de su archivo POTM.
- Guarde y descargue el archivo actualizado.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos de metadatos compatibles" subTitle="Con C++, también puede administrar los metadatos de los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
