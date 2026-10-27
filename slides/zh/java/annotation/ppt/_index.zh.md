---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3630
title: 使用 Java 删除 PPT 批注
url: /zh/java/annotation/ppt/ 
description: 借助 Aspose.Slides for Java，使用 Java 从 PPT 演示文稿中删除评论和评论作者。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 从 PPT 中删除评论和评论作者" h2="使用 Aspose.Slides for Java 从演示文稿文件中删除评论和评论作者。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 Java 从 PPT 中删除评论" variant="code" %}}

Aspose.Slides for Java 可让您从 PPT 演示文稿中删除评论和评论作者。使用 `Presentation` 类加载文件，遍历 `getCommentAuthors` 返回的 `ICommentAuthor` 对象并清除其评论，然后保存更新后的演示文稿。

{{< blocks/products/pf/slides-design-update-10-2026/code title="从 PPT 中删除批注 – Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
    {
        commentAuthor.getComments().clear();
    }

    presentation.getCommentAuthors().clear();

    presentation.save("cleaned-presentation.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通过 Java 从 PPT 中删除评论" intro="按照以下步骤从 PPT 演示文稿中删除评论和评论作者。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 Aspose.Slides for Java。请参阅[安装](https://docs.aspose.com/slides/java/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 PPT 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍历 `getCommentAuthors` 返回的 `ICommentAuthor` 对象。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `getComments().clear()` 清除每位作者的评论。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}清空评论作者集合并保存更新后的 PPT 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/annotation-app label="基于 Aspose.Slides 构建" title="在线删除 PPT 评论" description="免费的 Aspose.Slides Annotation 应用基于 [Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPT 文件。" button="打开 Aspose.Slides Annotation" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先了解 Aspose.Slides 如何删除评论。
- 删除 PPT 文件中的所有评论。
- 下载清理后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/annotation-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="批注支持的其他格式" subTitle="使用 Java，您还可以从其他格式中删除批注。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/annotation/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
