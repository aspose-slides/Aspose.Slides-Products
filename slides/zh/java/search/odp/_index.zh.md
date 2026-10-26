---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Java 在 ODP 演示文稿文件中搜索文本
url: /zh/java/search/odp/
description: 使用 Aspose.Slides for Java 在 Java 中搜索 ODP 演示文稿中的文本。
keywords: 在 ODP 中搜索单词，在 ODP 中搜索文本，搜索 ODP 演示文稿文本
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 在 ODP 中搜索文本" h2="构建通过服务器端 API 在演示文稿文件中搜索文本的 Java 应用程序。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 Java 在 ODP 演示文稿中搜索文本" variant="code" %}}

借助 [Aspose.Slides for Java](/slides/zh/java/)，您可以在 ODP 演示文稿中搜索文本。使用 `SlideUtil.getAllTextBoxes` 方法收集文本框架，然后检查 `ITextFrame`、`IParagraph` 和 `IPortion` 对象。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 在 ODP 演示文稿中搜索文本" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通过 Java 在 ODP 中搜索文本" intro="按照以下步骤在 ODP 演示文稿中搜索文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 ODP 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `SlideUtil.getAllTextBoxes` 方法收集每张幻灯片的文本框架。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}检查 `ITextFrame`、`IParagraph` 和 `IPortion` 对象以查找匹配的文本。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="基于 Aspose.Slides 构建" title="在线搜索 ODP 文件中的文本" description="免费的 Aspose.Slides Search 应用基于 [Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 ODP 文件。" button="打开 Aspose.Slides Search" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，了解 Aspose.Slides 如何查找文本。
- 在您的 ODP 文件中搜索纯文本或正则表达式。
- 将匹配结果下载为文本文件。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持搜索的格式" subTitle="使用 Java，您还可以在以下格式中搜索文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/search/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
