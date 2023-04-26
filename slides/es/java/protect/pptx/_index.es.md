---
title: Proteja los archivos de presentación de PPTX usando Java
url: /es/java/protect/pptx/
keywords: Protección contra escritura PPTX, encriptación de PPTX, bloqueo de PPTX presentación, protección de PPTX
description: Código fuente de Java para proteger la presentación de PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Bloquear o proteger con contraseña PPTX usando Java" h2="Cree sus propias aplicaciones Java para proteger los archivos de presentación mediante las API del lado del servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Proteger una presentación de PPTX a través de Java" %}}
Usando Aspose.Slides for Java, puede proteger su presentación PPTX para que no se abra o modifique configurando una contraseña. Luego, para abrir o modificar la presentación bloqueada, el usuario debe proporcionar la contraseña.
{{% blocks/products/pf/agp/code-block title="Cifrar una presentación PPTX usando Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Configurar la protección contra escritura en una presentación PPTX usando Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo proteger con contraseña PPTX a través de Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para proteger archivos PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue PPTX con una instancia de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Proteger la presentación usando la clase ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado en formato PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de protección compatibles" subTitle="Usando Java, también puede proteger los siguientes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/java/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}