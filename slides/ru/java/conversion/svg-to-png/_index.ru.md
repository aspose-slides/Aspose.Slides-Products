---
title: Преобразование SVG в PNG в Java
url: /ru/java/conversion/svg-to-png/
keywords: SVG в PNG, преобразовать SVG в PNG, API Java, библиотеку Java, SVG, PNG
description: Преобразование SVG в PNG в Java. Используйте API библиотеки Java для преобразования файлов SVG в файлы PNG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование SVG в PNG в Java" h2="Высокоскоростная и кроссплатформенная библиотека Java, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование SVG в PNG в Java" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ru/java/) — мощная библиотека Java для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования SVG в PNG. Используя **Aspose.Slides for Java**, любой разработчик или приложение может преобразовать файлы SVG в PNG всего несколькими строками кода Java.

Как современный API обработки документов, Aspose.Slides для Java быстро экспортирует файлы SVG в форматы файлов PNG. Библиотека Aspose PowerPoint позволяет конвертировать SVG в PNG и многие другие форматы файлов.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование SVG в PNG с помощью Java" %}}
Чтобы преобразовать SVG в PNG, вам нужно будет создать презентацию из файла SVG и сохранить его как PNG.

{{% blocks/products/pf/agp/code-block title="Код Java для преобразования SVG в PNG" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    String svgContent = new String(Files.readAllBytes(Paths.get("image.svg")));
    ISvgImage svgImage = new SvgImage(svgContent);
    IPPImage ppImage = pres.getImages().addImage(svgImage);
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 
			ppImage.getWidth(), ppImage.getHeight(), ppImage);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как преобразовать SVG в PNG с помощью Aspose.Slides for Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для преобразования SVG в PNG в Java." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](https://products.aspose.com/slides/ru/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source SVG files in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as PNG file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Конвертировать SVG в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать SVG и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}