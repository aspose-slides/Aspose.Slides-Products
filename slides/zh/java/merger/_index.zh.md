---
title: 使用 Java 合并 PDF、PPT、PPTX 和许多其他文件格式
url: /zh/java/merger/
keywords: 合并、加入、PowerPoint、演示文稿、Java、Aspose
description: 合并 Java PPT、PPTX、ODP、PDF、PNG、JPG 等多个文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 Java 中将 Powerpoint、PDF、PPT 或其他文档合并在一起" h2="用于合并 PPT、PPTX、PDF、PNG、JPEG 等格式的高速 Java 库。" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Java 合并 PPT、PPTX、PDF" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh/java/) 是一个强大的 Java 库，用于创建和操作演示文件。此外，它提供了灵活的方式来组合多个 PPT/PPTX 演示文稿。当您将一个演示文稿合并到另一个演示文稿时，您实际上是将他们的幻灯片合并到一个演示文稿中以获得一个文件。 Aspose.Slides 允许您以不同的方式合并两个演示文稿。您可以将演示文稿与其所有形状、样式、文本、格式、评论、动画等合并，而不必担心质量或数据丢失。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 Java 中合并 PowerPoint 演示文稿" %}}
要合并 PowerPoint 演示文稿，您需要将幻灯片从一个演示文稿克隆到另一个演示文稿。

{{% blocks/products/pf/agp/code-block title="使用 Java 合并 PPTX 文件" offSpacer="true" %}}

```java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge slides
for (ISlide slide : presentation2.getSlides()) {
	// Merge slides from source to target
	presentation1.getSlides().addClone(slide);
}

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Java 将演示文稿与幻灯片母版合并" %}}
此 Java 代码演示了如何将多个演示文稿合并为一个并应用幻灯片母版演示模板中的样式。因此，结果演示文稿将保持相同的源格式，并将包含来自另一个演示文稿的母版幻灯片的格式。

{{% blocks/products/pf/agp/code-block title="在Java中将多个PPT合并为一个" offSpacer="true" %}}

``` java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge first two slides only using slide master
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(0), presentation1.getMasters().get_Item(0), true);
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(1), presentation1.getMasters().get_Item(0), true);

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Java API 合并演示文稿" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是合并两个 PPTX 文件并将结果保存为 Java 中的 PDF 的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安装 [**Aspose.Slides for Java**](https://docs.aspose.com/slides/java/installation/)。 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库引用（导入库）添加到您的 Java 项目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Java 中打开源 PPTX 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 **addClone** 方法合并 PPTX 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存演示文稿并将结果保存为单个 PDF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的合并格式" subTitle="您还可以组合其他文件格式。请参阅下面的其他支持格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}