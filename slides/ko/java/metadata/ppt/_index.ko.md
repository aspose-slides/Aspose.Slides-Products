---
title: Java을(를) 사용하여 PPT 파일 메타데이터 보기 또는 편집
url: /ko/java/metadata/ppt/
keywords: PPT 메타데이터 수정, PPT 메타데이터 보기, PPT 속성 수정, PPT 속성 보기
description: PPT 형식 메타데이터를 편집하거나 보기 위한 Java 소스 코드.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java을(를) 사용하여 PPT 속성 편집" h2="서버 측 API를 사용하여 프리젠테이션 파일의 기본 제공 속성과 사용자 정의 속성을 수정하려면 자신만의 Java 앱을 빌드하세요." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Java을 통해 PPT 속성 수정" %}}
개발자는 Aspose.Slides for Java을(를) 사용하여 기본 제공 속성 및 사용자 지정 속성의 값에 액세스하고 수정할 수 있습니다. 개발자는 프레젠테이션 파일의 문서 속성에 액세스하기 위해 Presentation 개체에 의해 노출된 [DocumentProperties](https://reference.aspose.com/slides/java/com.aspose.slides/documentproperties/) 속성을 사용할 수 있습니다.
{{% blocks/products/pf/agp/code-block title="PPT 내장 속성 수정 - Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation("Presentation.ppt");
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
    pres.save("DocProps.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="PPT에 맞춤 속성 추가 - Java" offSpacer="true" %}}

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
    pres.save("CustomDemo.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java을 통해 PPT의 메타데이터를 추출하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="다음은 PPT 파일에서 메타데이터를 추출하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT 파일에 대한 경로를 사용하여 프레젠테이션 클래스를 인스턴스화합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션과 연결된 DocumentProperties 개체 가져오기
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
DocumentProperties 개체의 항목을 반복합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
사용자 지정 속성 액세스 및 수정
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 메타데이터 형식" subTitle="Java을(를) 사용하여 다음을 비롯한 다양한 형식의 메타데이터를 조작할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}