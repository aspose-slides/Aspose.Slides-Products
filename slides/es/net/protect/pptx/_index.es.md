---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteger archivos de presentación PPTX con .NET
url: /es/net/protect/pptx/
description: Código fuente C# para proteger con contraseña presentaciones PPTX.
keywords: Protección contra escritura PPTX, cifrar PPTX, bloquear presentación PPTX, proteger PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bloquear o proteger con contraseña archivos PPTX con C#" h2="Cree aplicaciones .NET que cifren presentaciones y restrinjan las modificaciones con API del lado del servidor." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteger una presentación PPTX con C#" variant="code" %}}

Con [Aspose.Slides for .NET](/slides/es/net/), puede cifrar una presentación PPTX o restringir su modificación con una contraseña. Para abrir una presentación cifrada con `ProtectionManager.Encrypt` se necesita la contraseña. Use `ProtectionManager.SetWriteProtection` para permitir abrir la presentación y restringir a la vez los cambios.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cifrar una presentación PPTX con C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Establecer la protección contra escritura de una presentación PPTX con C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo proteger con contraseña una presentación PPTX con C#" intro="Siga estos pasos para proteger con contraseña una presentación PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo PPTX con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cifre la presentación con `ProtectionManager.Encrypt` o restrinja los cambios con `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el archivo protegido con `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Creado con Aspose.Slides" title="Proteger con contraseña archivos PPTX en línea" description="La aplicación gratuita Aspose.Slides Lock está creada con [Aspose.Slides for .NET](https://products.aspose.com/slides/es/net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPTX." button="Abrir Aspose.Slides Lock" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides protege las presentaciones antes de escribir código.
- Establezca una contraseña para abrir o editar su archivo PPTX.
- Descargue el archivo protegido.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la protección" subTitle="Con C#, también puede proteger los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
