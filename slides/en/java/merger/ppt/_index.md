---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Merge PPT Files using Java
weight: 730
url: /java/merger/ppt/
description: Merge PPT files in Java. Use Aspose.Slides for Java to combine PowerPoint 97-2003 presentations and save the merged file.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Merge PPT Files in Java" h2="Merge PPT documents using Aspose.Slides for Java server-side APIs."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Merge PPT Files Using Java" %}}

Use [Aspose.Slides for Java](/slides/java/) to load multiple `PPT` presentations, clone slides from one presentation into another, and save the merged file. You can install the `aspose-slides` package in a Maven-based project by adding the repository and dependency below.

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

{{< blocks/products/pf/slides-design-update-10-2026/code title="Merge PPT Files - Java" >}}
```java
Presentation destinationPresentation = new Presentation("presentation1.ppt");
try {
    Presentation sourcePresentation = new Presentation("presentation2.ppt");
    try {
        for (ISlide slide : sourcePresentation.getSlides()) {
            destinationPresentation.getSlides().addClone(slide);
        }
    } finally {
        sourcePresentation.dispose();
    }

    destinationPresentation.save("merged-presentation.ppt", SaveFormat.Ppt);
} finally {
    destinationPresentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Steps for Merging PPT Files in Java" intro="A basic document merge with [Aspose.Slides for Java](/slides/java/) APIs can be done with just a few lines of code." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the destination `PPT` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the source `PPT` file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Loop through the `ISlide` objects in the source presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `addClone` to add each source slide to the destination presentation.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `save` method with `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Requirements" intro="Before running the Java merge sample code, make sure that you have the following prerequisites." %}}

- Microsoft Windows, Linux, macOS, or another OS with a supported Java Runtime Environment.
- Get the latest version of Aspose.Slides for Java from Maven.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app />}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Files with the `.PPT` extension represent Microsoft PowerPoint 97-2003 presentation files. A `PPT` file can contain slides with text, images, multimedia, and other embedded objects.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Merging Formats" subTitle="Using Java, you can also merge many other file formats including the ones listed below." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/odp/" name="ODP" description="OpenDocument Presentation Format" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/otp/" name="OTP" description="OpenDocument Presentation Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/pot/" name="POT" description="PowerPoint 97–2003 Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/potm/" name="POTM" description="PowerPoint Macro-Enabled Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/potx/" name="POTX" description="PowerPoint Template" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/merger/pptx/" name="PPTX" description="Open XML Presentation Format" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
