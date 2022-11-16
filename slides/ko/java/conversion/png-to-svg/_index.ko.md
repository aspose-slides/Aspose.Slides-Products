---
title: Java에서 PNG을 SVG로 변환
url: /ko/java/conversion/png-to-svg/
keywords: PNG에서 SVG으로, PNG에서 SVG로 변환, Java API, Java 라이브러리, PNG, SVG
description: Java에서 PNG을 SVG로 변환합니다. Java 라이브러리 API를 사용하여 PNG 파일을 SVG 파일로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Java에서 PNG을 SVG로 변환" h2="Microsoft 또는 Open Office, Adobe PDF와 같은 소프트웨어를 사용하지 않고 Microsoft PowerPoint 및 OpenOffice 프레젠테이션 파일을 생성, 병합, 검사 또는 변환할 수 있는 기능으로 응용 프로그램을 개발하는 데 도움이 되는 고속 및 교차 플랫폼 Java 라이브러리입니다." >}}

{{% blocks/products/pf/feature-page-section h2="Java에서 PNG을 SVG로 변환" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/)는 프레젠테이션 파일을 만들고 조작하기 위한 강력한 Java 라이브러리입니다. 또한 PNG을 SVG으로 변환하는 유연한 방법을 제공합니다. **Aspose.Slides for Java**를 사용하면 모든 개발자 또는 애플리케이션이 단 몇 줄의 Java 코드로 PNG을 SVG 파일로 변환할 수 있습니다.

최신 문서 처리 API인 Aspose.Slides for Java는 PNG 파일을 SVG 파일 형식으로 빠르게 내보냅니다. Aspose PowerPoint 라이브러리를 사용하면 PNG을 SVG 및 기타 여러 파일 형식으로 변환할 수 있습니다.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java를 사용하여 PNG을 SVG로 변환" %}}
PNG을 SVG로 변환하려면 PNG 파일에서 프레젠테이션을 생성하고 SVG로 저장해야 합니다.

{{% blocks/products/pf/agp/code-block title="PNG을 SVG로 변환하기 위한 Java 코드" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);

        FileOutputStream fileStream = new FileOutputStream("slide-" + index + ".svg");
        try {
            slide.writeAsSvg(fileStream);
        } finally {
            fileStream.close();
        }
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Java API를 사용하여 PNG을 SVG로 변환하는 방법" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Java에서 PNG을 SVG으로 변환하는 단계입니다." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source PNG files in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as SVG file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="PNG을 지원되는 다른 형식으로 변환" subTitle="PNG을 변환하고 다른 파일 형식으로 저장할 수도 있습니다. 아래에서 지원되는 모든 형식 보기" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/png-to-pdf/" name="PNG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}