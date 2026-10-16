---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Convert OTP to BMP using Java
weight: 6880
url: /java/conversion/otp-to-bmp/
description: Convert OTP to BMP in Java. Use Aspose.Slides for Java to render OTP presentations as BMP images.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Convert OTP to BMP in Java" h2="Render OTP presentations as BMP images with Aspose.Slides for Java without OpenOffice."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family/"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Convert OTP to BMP Using Java" %}}

To convert `OTP` to `BMP`, use
 [Aspose.Slides for Java](/slides/java/).
 It is a PowerPoint and OpenDocument presentation API that lets you load an `OTP` file and render slides as `BMP` images. You can get the latest `aspose-slides` package from
 [Maven](https://releases.aspose.com/java/repo/)
 and add it to your Maven-based project with the following configuration in `pom.xml`.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Repository" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dependency" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="OTP to BMP Java Conversion Source Code" >}}
```java
Presentation presentation = new Presentation("template.otp");
try {
    for (ISlide slide : presentation.getSlides()) {
        IImage slideImage = slide.getImage(1f, 1f);
        try {
            slideImage.save("slide_" + slide.getSlideNumber() + ".bmp", ImageFormat.Bmp);
        } finally {
            slideImage.dispose();
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Convert OTP to BMP via Java" intro="Java developers can convert an `OTP` file to `BMP` in just a few lines of code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the `OTP` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Iterate through the `ISlide` collection returned by `Presentation.getSlides`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Render each slide with the `ISlide.getImage` method.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save each `IImage` object with `ImageFormat.Bmp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the Java conversion sample code, make sure that you have the following prerequisites." %}}

- A supported operating system with a Java Runtime Environment installed.
- Get the latest version of Aspose.Slides for Java from the Aspose Maven repository.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert OTP to BMP"
  description="Convert presentations and slides online." >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Conversions" subTitle="You can also convert OTP into many other file formats including a few listed below." >}}{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
