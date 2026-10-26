---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Desbloquear presentaciones PPTX con Python
url: /es/python-net/unlock/pptx/
description: Quite el cifrado y la protección contra escritura de presentaciones PPTX con Python.
keywords: desbloquear PPTX, quitar contraseña de PPTX, quitar cifrado de PPTX, quitar protección contra escritura de PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Desbloquear presentaciones PPTX con Python" h2="Cree aplicaciones Python que quiten las contraseñas de apertura y la protección contra escritura de presentaciones PPTX con Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Quitar el cifrado y la protección contra escritura de PPTX con Python" variant="code" %}}

Con [Aspose.Slides for Python via .NET](/slides/es/python-net/), puede quitar el cifrado que exige una contraseña para abrir una presentación PPTX, o desactivar su protección contra escritura. Para abrir un archivo cifrado, proporcione la contraseña actual mediante `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Quitar el cifrado de una presentación PPTX – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.pptx", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Quitar la protección contra escritura de una presentación PPTX – Python" >}}
```py
with slides.Presentation("write-protected-presentation.pptx") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo quitar la protección de PPTX con Python" intro="Siga estos pasos para quitar la protección de una presentación PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Si el archivo PPTX está cifrado, establezca la contraseña actual en `LoadOptions` y, a continuación, abra el archivo con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame a `ProtectionManager.remove_encryption` para quitar la contraseña de apertura, o a `ProtectionManager.remove_write_protection` para desactivar la protección contra escritura.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde la presentación resultante con `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Creado con Aspose.Slides" title="Desbloquear archivos PPTX en línea" description="La aplicación gratuita Aspose.Slides Unlock está creada con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/es/python-net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos PPTX." button="Abrir Aspose.Slides Unlock" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides quita la protección antes de escribir código.
- Quite la contraseña o la protección contra escritura de su archivo PPTX.
- Descargue el archivo desbloqueado.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con el desbloqueo" subTitle="Use Python para quitar la protección de otros formatos de presentación compatibles." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
