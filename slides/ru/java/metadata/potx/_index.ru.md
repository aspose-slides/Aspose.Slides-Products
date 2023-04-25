---
title: Просмотр или редактирование метаданных файлов POTX с помощью Java
url: /ru/java/metadata/potx/
keywords: Изменить метаданные POTX, просмотреть метаданные POTX, изменить свойства POTX, просмотреть свойства POTX
description: Исходный код Java для редактирования или просмотра метаданных формата POTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Измените свойства POTX, используя Java" h2="Создавайте собственные приложения Java для изменения встроенных и настраиваемых свойств в файлах презентаций с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Измените свойства POTX через Java" %}}
Используя Aspose.Slides for Java, разработчики могут получать доступ и изменять значения как встроенных, так и пользовательских свойств. Разработчики могут использовать свойство [DocumentProperties](https://reference.aspose.com/slides/java/com.aspose.slides/documentproperties/), предоставляемое объектом Presentation, для доступа к свойствам документа файла презентации.
{{% blocks/products/pf/agp/code-block title="Изменить встроенные свойства POTX – Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation("Presentation.potx");
try {
    // Create a reference to IDocumentProperties object associated with Presentation
    IDocumentProperties dp = pres.getDocumentProperties();
    
    // Set the built-in properties
    dp.setAuthor("Aspose.Slides for Java");
    dp.setTitle("Modifying Presentation Properties");
    dp.setSubject("Aspose Subject");
    dp.setComments("Aspose Description");
    dp.setManager("Aspose Manager");
    
    // Save your presentation to a file
    pres.save("DocProps.potx", SaveFormat.Potx);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Добавить пользовательские свойства в POTX – Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    // Getting Document Properties
    IDocumentProperties dProps = pres.getDocumentProperties();
    
    // Adding Custom properties
    dProps.set_Item("New Custom", 12);
    dProps.set_Item("My Name", "Aspose Metadata Editor");
    dProps.set_Item("Custom", 124);
    
    // Getting property name at particular index
    String getPropertyName = dProps.getCustomPropertyName(2);
    
    // Removing selected property
    dProps.removeCustomProperty(getPropertyName);
    
    // Saving presentation
    pres.save("CustomDemo.potx", SaveFormat.Potx);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как извлечь метаданные POTX через Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для извлечения метаданных из файлов POTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Создайте экземпляр класса Presentation с путем к файлу POTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Получить объект DocumentProperties, связанный с презентацией
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Перебрать элементы в объекте DocumentProperties
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Доступ и изменение пользовательских свойств
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы метаданных" subTitle="Используя Java, вы также можете управлять метаданными многих других форматов, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/java/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}