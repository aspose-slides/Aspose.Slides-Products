---
title: Java에서 PPTX를 Word로 변환
url: /ko/java/conversion/pptx-to-word/
keywords: PPTX를 Word로, PPTX를 Word로, PPTX를 DOC로, PowerPoint를 Word로, Java API, Java 라이브러리로 변환
description: Java에서 PPTX를 Word로 변환합니다. Java 라이브러리 API를 사용하여 PowerPoint를 Word로 변환
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Java에서 PPTX를 Word로 변환" h2="Microsoft PowerPoint 또는 Office 없이 Java 코드를 사용하여 PowerPoint를 Word로 변환하기 위한 강력한 교차 플랫폼 Java API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides 및 Aspose.Words를 사용하여 PowerPoint를 Word로 변환" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ko/java/) 및 [**Aspose.Words for Java**](https://products.aspose.com/ words/java/)는 PowerPoint 프레젠테이션, Word 문서 및 기타 파일을 조작하고 변환하는 데 사용되는 강력한 Java 라이브러리입니다. PowerPoint를 Word로 변환하면 기본적으로 프레젠테이션 슬라이드의 내용이 Word 문서의 페이지로 이동됩니다.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Java에서 PowerPoint를 Word로 변환" %}}
몇 줄의 코드만으로 빠르게 PPTX를 Word로 변환할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="PowerPoint를 Word로 변환하기 위한 Java 코드" offSpacer="true" %}}
```java
Presentation pres = new Presentation(inputPres);
try {
    Document doc = new Document();
    DocumentBuilder builder = new DocumentBuilder(doc);
    for (ISlide slide : pres.getSlides())
    {
        // generates and inserts slide image
        BufferedImage bitmap = slide.getThumbnail(1, 1);

        builder.insertImage(bitmap);

        // inserts slide's texts
        for (IShape shape : slide.getShapes())
        {
            if (shape instanceof AutoShape)
            {
                builder.writeln(((AutoShape)shape).getTextFrame().getText());
            }
        }

        builder.insertBreak(BreakType.PAGE_BREAK);
    }
    doc.save(outputDoc);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PPTX를 Word로 변환하는 방법" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Java** 및 **Aspose.Words for Java** 설치 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation 클래스와 Doc 클래스의 인스턴스를 만듭니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Word로 변환하려는 PPTX 프레젠테이션을 로드합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
슬라이드의 내용을 기반으로 이미지와 텍스트를 생성합니다.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
결과 Word 문서를 저장합니다.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="무료 온라인 변환기" sectionDescription="[Python에서 PPT를 HTML로 변환하는 방법](https://products.aspose.com/slides/ko/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="PowerPoint를 다른 형식의 파일로 변환할 수도 있습니다." >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ko/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}