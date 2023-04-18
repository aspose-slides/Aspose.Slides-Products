---
title: Java를 사용하여 ODP 주석 제거
weight: 1790
url: /ko/java/annotation/odp/ 
description: JSP/JSF 응용 프로그램 및 데스크톱 응용 프로그램용 Java Runtime Environment에서 ODP 형식 주석을 삭제하는 Java 샘플 코드입니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java의 ODP에서 주석 및 주석 작성자 제거" h2="서버 측 API를 사용하여 문서 파일에서 댓글과 작성자를 조작하는 고유한 Java 앱을 빌드합니다." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 ODP에서 주석 제거" %}}
ODP 파일에서 주석을 제거하기 위해 기능이 풍부하고 강력하며 사용하기 쉬운 [Aspose.Slides for Java](https://products.aspose.com/slides/ko/java/) API를 사용합니다. Java 플랫폼용 문서 조작 API.
{{% blocks/products/pf/agp/code-block title="ODP에서 주석 삭제 - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.odp");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Java를 통해 ODP에서 주석을 제거하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Java**를 설치합니다. [**설치**](https://docs.aspose.com/slides/java/installation/)를 참조하세요.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프레젠테이션 클래스의 인스턴스로 ODP 로드
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
로드된 ODP의 모든 작성자에 대해 반복
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
작성자의 모든 주석 제거
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
마지막에 모든 작성자 제거
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 주석 형식" subTitle="Java를 사용하면 다음을 포함한 다른 형식에 쉽게 주석을 달 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}