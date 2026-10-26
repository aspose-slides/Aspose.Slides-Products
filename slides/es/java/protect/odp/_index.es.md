---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteger archivos de presentación ODP con Java
url: /es/java/protect/odp/
description: Proteja presentaciones ODP en Java. Use Aspose.Slides for Java para cifrar archivos de presentación y establecer la protección contra escritura.
keywords: Protección contra escritura ODP, cifrar un ODP, bloquear presentación ODP, proteger ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Bloquear o proteger con contraseña un ODP con Java" h2="Cree aplicaciones Java que protejan archivos de presentación con API del lado del servidor." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteger una presentación ODP con Java" variant="code" %}}

Con [Aspose.Slides for Java](/slides/es/java/), puede impedir que una presentación ODP se abra o se modifique estableciendo una contraseña. Use el objeto `ProtectionManager` de la clase `Presentation` para llamar a métodos como `encrypt` y `setWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Cifrar una presentación ODP con Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Establecer la protección contra escritura de una presentación ODP con Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo proteger con contraseña un ODP con Java" intro="Siga estos pasos para proteger una presentación ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo ODP con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Llame al método `encrypt` o al método `setWriteProtection` del objeto `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el archivo protegido con `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Creado con Aspose.Slides" title="Proteger con contraseña archivos ODP en línea" description="La aplicación gratuita Aspose.Slides Lock está creada con [Aspose.Slides for Java](https://products.aspose.com/slides/es/java/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos ODP." button="Abrir Aspose.Slides Lock" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides protege las presentaciones antes de escribir código.
- Establezca una contraseña para abrir o editar su archivo ODP.
- Descargue el archivo protegido.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Otros formatos compatibles con la protección" subTitle="Con Java, también puede proteger los siguientes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/es/java/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
