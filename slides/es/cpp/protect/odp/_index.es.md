---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteger presentaciones ODP con C++
url: /es/cpp/protect/odp/
description: Proteja presentaciones ODP en C++. Use Aspose.Slides for C++ para cifrar archivos y establecer la protección contra escritura.
keywords: Protección contra escritura ODP, cifrar ODP, bloquear presentación ODP, proteger ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bloquear o proteger con contraseña un ODP con C++" h2="Use Aspose.Slides for C++ para cifrar presentaciones y establecer la protección contra escritura sin Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteger una presentación ODP con C++" variant="code" %}}

Aspose.Slides for C++ le permite impedir que las presentaciones ODP se abran o se modifiquen. Use el objeto `ProtectionManager` de la clase `Presentation` para cifrar un archivo con `Encrypt` o restringir la edición con `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cifrar una presentación ODP con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Establecer la protección contra escritura de una presentación ODP con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo proteger con contraseña un ODP con C++" intro="Siga estos pasos para proteger una presentación ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo ODP con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Proteja la presentación con el objeto `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use `Encrypt` para la protección con contraseña o `SetWriteProtection` para la protección contra escritura.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el archivo protegido con `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Creado con Aspose.Slides" title="Proteger con contraseña archivos ODP en línea" description="La aplicación gratuita Aspose.Slides Lock está creada con [Aspose.Slides for C++](https://products.aspose.com/slides/es/cpp/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos ODP." button="Abrir Aspose.Slides Lock" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides protege las presentaciones antes de escribir código.
- Establezca una contraseña para abrir o editar su archivo ODP.
- Descargue el archivo protegido.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la protección" subTitle="Con C++, también puede proteger los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
