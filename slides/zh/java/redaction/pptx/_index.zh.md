---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Java 对 PPTX 演示文稿文件进行脱敏
url: /zh/java/redaction/pptx/
description: 使用 Aspose.Slides for Java 在 Java 中查找和替换 PPTX 演示文稿中的文本。
keywords: PPTX 脱敏，在 PPTX 中查找和替换文本，更新 PPTX 演示文稿
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 对 PPTX 进行脱敏" h2="构建通过服务器端 API 在演示文稿文件中查找和替换文本的 Java 应用程序。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 Java 对 PPTX 演示文稿进行脱敏" variant="code" %}}

借助 [Aspose.Slides for Java](/slides/zh/java/)，您可以在 PPTX 演示文稿中查找和替换文本。使用 `SlideUtil.findAndReplaceText` 方法搜索演示文稿，并将匹配的文本替换为新值。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 对 PPTX 演示文稿进行脱敏" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通过 Java 对 PPTX 进行脱敏" intro="按照以下步骤对 PPTX 演示文稿进行脱敏。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `SlideUtil.findAndReplaceText` 方法查找和替换文本。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Pptx` 保存更新后的演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="基于 Aspose.Slides 构建" title="在线对 PPTX 文件进行脱敏" description="免费的 Aspose.Slides Redaction 应用基于 [Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTX 文件。" button="打开 Aspose.Slides Redaction" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，了解 Aspose.Slides 如何查找和替换文本。
- 在您的 PPTX 文件中查找和替换文本，支持正则表达式。
- 下载脱敏后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持脱敏的格式" subTitle="使用 Java，您还可以对以下格式进行脱敏。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
