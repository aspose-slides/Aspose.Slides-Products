---
title: Java에서 HTML을 PDF로 변환
url: /ko/java/conversion/html-to-pdf/
keywords: HTML에서 PDF으로, HTML에서 PDF로 변환, Java API, Java 라이브러리, HTML, PDF
description: Java에서 HTML을 PDF로 변환합니다. Java 라이브러리 API를 사용하여 HTML 파일을 PDF 파일로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Java에서 HTML을 PDF로 변환" h2="Microsoft 또는 Open Office, Adobe PDF와 같은 소프트웨어를 사용하지 않고 Microsoft PowerPoint 및 OpenOffice 프레젠테이션 파일을 생성, 병합, 검사 또는 변환할 수 있는 기능으로 응용 프로그램을 개발하는 데 도움이 되는 고속 및 교차 플랫폼 Java 라이브러리입니다." >}}

{{% blocks/products/pf/feature-page-section h2="Java에서 HTML을 PDF로 변환" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/)는 프레젠테이션 파일을 만들고 조작하기 위한 강력한 Java 라이브러리입니다. 또한 HTML을 PDF으로 변환하는 유연한 방법을 제공합니다. **Aspose.Slides for Java**를 사용하면 모든 개발자 또는 애플리케이션이 단 몇 줄의 Java 코드로 HTML을 PDF 파일로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for Java는 HTML 파일을 PDF 파일 형식으로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 HTML을 PDF 및 기타 여러 파일 형식으로 변환할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java를 사용하여 HTML을 PDF로 변환" %}}
HTML을 PDF로 변환하려면 HTML 파일에서 프레젠테이션을 생성하고 PDF로 저장해야 합니다.

{{% blocks/products/pf/agp/code-block title="HTML을 PDF로 변환하기 위한 Java 코드" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    TextReader tr = new StreamReader("file.html");
    pres.getSlides().addFromHtml(tr);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Java API를 사용하여 HTML을 PDF로 변환하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java에서 HTML을 PDF으로 변환하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/)를 설치합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Java 프로젝트에 라이브러리 참조를 추가합니다(라이브러리 가져오기).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Java에서 소스 HTML 파일을 엽니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과를 PDF 파일로 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="HTML을 지원되는 다른 형식으로 변환" subTitle="HTML을 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식 보기" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}