---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteger archivos de presentación ODP con Python
url: /es/python-net/protect/odp/
description: Cifre presentaciones ODP o establezca la protección contra escritura con Python.
keywords: protección contra escritura ODP, cifrar ODP con Python, bloquear presentación ODP, proteger ODP con Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Proteger presentaciones ODP con Python" h2="Cree aplicaciones Python que cifren presentaciones o establezcan la protección contra escritura con Aspose.Slides." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteger una presentación ODP con Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/es/python-net/) ofrece dos mecanismos de protección distintos. Llame a `ProtectionManager.encrypt` para cifrar una presentación ODP y exigir una contraseña para abrirla. Como alternativa, llame a `ProtectionManager.set_write_protection` para desalentar las modificaciones sin cifrar el archivo. Un usuario aún puede abrir una presentación protegida contra escritura y guardar los cambios en otro archivo.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cifrar una presentación ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Establecer la protección contra escritura de una presentación ODP – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo proteger un ODP con Python" intro="Siga estos pasos para proteger un archivo ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra el archivo ODP con `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use `ProtectionManager.encrypt` para exigir una contraseña al abrir, o `ProtectionManager.set_write_protection` para desalentar los cambios.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde la presentación protegida como ODP con `SaveFormat.ODP`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Creado con Aspose.Slides" title="Proteger con contraseña archivos ODP en línea" description="La aplicación gratuita Aspose.Slides Lock está creada con [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/es/python-net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos ODP." button="Abrir Aspose.Slides Lock" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides protege las presentaciones antes de escribir código.
- Establezca una contraseña para abrir o editar su archivo ODP.
- Descargue el archivo protegido.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la protección" subTitle="Use Python para proteger otros formatos de presentación compatibles." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
