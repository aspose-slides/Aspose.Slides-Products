---
title: Proteja los archivos de presentación de ODP usando Java
url: /es/java/protect/odp/
keywords: Protección contra escritura ODP, encriptación de ODP, bloqueo de ODP presentación, protección de ODP
description: Código fuente de Java para proteger la presentación de ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Bloquear o proteger con contraseña ODP usando Java" h2="Cree sus propias aplicaciones Java para proteger los archivos de presentación mediante las API del lado del servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Proteger una presentación de ODP a través de Java" %}}
Usando Aspose.Slides for Java, puede proteger su presentación ODP para que no se abra o modifique configurando una contraseña. Luego, para abrir o modificar la presentación bloqueada, el usuario debe proporcionar la contraseña.
{{% blocks/products/pf/agp/code-block title="Cifrar una presentación ODP usando Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.odp");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Configurar la protección contra escritura en una presentación ODP usando Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.odp");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo proteger con contraseña ODP a través de Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para proteger archivos ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue ODP con una instancia de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Proteger la presentación usando la clase ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado en formato ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de protección compatibles" subTitle="Usando Java, también puede proteger los siguientes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}