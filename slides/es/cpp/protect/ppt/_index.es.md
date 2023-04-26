---
title: Proteja los archivos de presentación de PPT usando C++
url: /es/cpp/protect/ppt/
keywords: Protección contra escritura PPT, encriptación de PPT, bloqueo de PPT presentación, protección de PPT
description: Código fuente de C++ para proteger la presentación de PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Bloquear o proteger con contraseña PPT usando C++" h2="Cree sus propias aplicaciones C++ para proteger los archivos de presentación mediante las API del lado del servidor." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Proteger una presentación de PPT a través de C++" %}}
Usando Aspose.Slides for C++, puede proteger su presentación PPT para que no se abra o modifique configurando una contraseña. Luego, para abrir o modificar la presentación bloqueada, el usuario debe proporcionar la contraseña.
{{% blocks/products/pf/agp/code-block title="Cifrar una presentación PPT usando C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.ppt");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Configurar la protección contra escritura en una presentación PPT usando C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.ppt");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Cómo proteger con contraseña PPT a través de C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estos son los pasos para proteger archivos PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue PPT con una instancia de Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Proteger la presentación usando la clase ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guardar resultado en formato PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Otros formatos de protección compatibles" subTitle="Usando C++, también puede proteger los siguientes formatos:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/cpp/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}