---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Desbloquear archivos de presentación PPTX con .NET
url: /es/net/unlock/pptx/
description: Código fuente C# para quitar la protección con contraseña de presentaciones PPTX.
keywords: Quitar protección contra escritura PPTX, descifrar PPTX, desbloquear presentación PPTX, desproteger PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Desbloquear archivos PPTX con C#" h2="Cree aplicaciones .NET que quiten el cifrado y la protección contra escritura de las presentaciones con API del lado del servidor." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Quitar la protección de una presentación PPTX con C#" variant="code" %}}

Con [Aspose.Slides for .NET](/slides/es/net/), puede quitar el cifrado o la protección contra escritura de una presentación PPTX. Para quitar el cifrado, cargue la presentación con la contraseña correcta y llame a `ProtectionManager.RemoveEncryption`. Para quitar la protección contra escritura, llame a `ProtectionManager.RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Quitar el cifrado de una presentación PPTX con C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.pptx", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Quitar la protección contra escritura de una presentación PPTX con C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.pptx");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo quitar la protección de una presentación PPTX con C#" intro="Siga estos pasos para quitar la protección de una presentación PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPTX con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Si el archivo está cifrado, proporcione la contraseña mediante `LoadOptions.Password` antes de cargarlo.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame a `ProtectionManager.RemoveEncryption` o a `ProtectionManager.RemoveWriteProtection`, según la protección aplicada.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde la presentación desbloqueada con `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Creado con Aspose.Slides" title="Desbloquear archivos PPTX en línea" description="La aplicación gratuita Aspose.Slides Unlock está creada con [Aspose.Slides for .NET](https://products.aspose.com/slides/es/net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPTX." button="Abrir Aspose.Slides Unlock" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides quita la protección antes de escribir código.
- Quite la contraseña o la protección contra escritura de su archivo PPTX.
- Descargue el archivo desbloqueado.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con el desbloqueo" subTitle="Con C#, también puede quitar la protección de los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
