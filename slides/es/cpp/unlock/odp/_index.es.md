---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Desbloquear presentaciones ODP con C++
url: /es/cpp/unlock/odp/
description: Desbloquee presentaciones ODP en C++. Use Aspose.Slides for C++ para quitar el cifrado y la protección contra escritura de archivos de presentación.
keywords: Quitar protección contra escritura ODP, descifrar ODP, desbloquear presentación ODP, desproteger ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Desbloquear un ODP con C++" h2="Use Aspose.Slides for C++ para quitar el cifrado y la protección contra escritura de archivos de presentación sin Microsoft PowerPoint." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Quitar la protección de una presentación ODP con C++" variant="code" %}}

Aspose.Slides for C++ le permite quitar el cifrado o la protección contra escritura de presentaciones ODP. Use `LoadOptions` para abrir un archivo cifrado y, a continuación, el objeto `ProtectionManager` de la clase `Presentation` para llamar a `RemoveEncryption` o `RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Quitar la protección con contraseña de un ODP con C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.odp", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Quitar la protección contra escritura de una presentación ODP con C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.odp");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo quitar la contraseña de un ODP con C++" intro="Siga estos pasos para quitar la protección de una presentación ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo ODP con la clase `Presentation` y, si se requiere una contraseña, con `LoadOptions`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use el objeto `ProtectionManager` para quitar la protección.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame a `RemoveEncryption` para archivos cifrados o a `RemoveWriteProtection` para archivos protegidos contra escritura.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el archivo desbloqueado con `SaveFormat::Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Creado con Aspose.Slides" title="Desbloquear archivos ODP en línea" description="La aplicación gratuita Aspose.Slides Unlock está creada con [Aspose.Slides for C++](https://products.aspose.com/slides/es/cpp/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos ODP." button="Abrir Aspose.Slides Unlock" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides quita la protección antes de escribir código.
- Quite la contraseña o la protección contra escritura de su archivo ODP.
- Descargue el archivo desbloqueado.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con el desbloqueo" subTitle="Con C++, también puede quitar la protección de los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
