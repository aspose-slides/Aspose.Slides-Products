---
title: Java에서 HTML을 PPTX로 변환
url: /ko/java/conversion/html-to-pptx/
keywords: HTML을 PPTX로, HTML을 PPTX로, PowerPoint, HTML, PPTX, Java API, Java 라이브러리로 변환
description: Java에서 HTML을 PPTX로 변환합니다. Java 라이브러리 API를 사용하여 HTML을 PowerPoint로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Java에서 HTML을 PPTX로 변환" h2="Java 코드를 사용하여 HTML을 PPTX로 변환하기 위한 강력한 크로스 플랫폼 Java API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides를 사용하여 HTML을 PPTX로 변환" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/)는 PowerPoint 프레젠테이션, PDF, HTML 문서 및 기타 문서를 생성, 변환 및 조작하는 데 사용되는 강력한 Java 라이브러리입니다. 파일. HTML을 PPTX로 변환하면 기본적으로 HTML 문서의 내용이 PowerPoint 프레젠테이션의 슬라이드로 이동됩니다.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="Java에서 HTML을 PPTX로 변환" %}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/)를 사용하면 몇 줄의 코드만으로 HTML 문서를 PowerPoint 프레젠테이션으로 변환할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="HTML을 PPTX로 변환하기 위한 Java 코드" offSpacer="true" %}}
```java
Presentation presentation = new Presentation();
try {
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        presentation.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    presentation.save("Presentation.pptx", SaveFormat.Pptx);
} catch(IOException e) {
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Java에서 HTML을 PPTX로 변환하는 방법" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Java**를 설치합니다. [**설치**](https://docs.aspose.com/slides/java/installation/)를 참조하세요.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
프로젝트에서 라이브러리를 참조로 추가하십시오.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스의 인스턴스를 만듭니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX로 변환하려는 HTML 문서를 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과 파일을 PPTX 프레젠테이션으로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="무료 온라인 변환기" sectionDescription="[Python에서 PPT를 HTML로 변환하는 방법](https://products.aspose.com/slides/ko/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 PowerPoint 변환" subTitle="다른 형식의 파일을 PowerPoint로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}