---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Java 查看或编辑 PPSX 文件元数据
url: /zh/java/metadata/ppsx/
description: 在 Java 中查看和编辑 PPSX 元数据。使用 Aspose.Slides for Java 更新演示文稿的内置属性与自定义属性。
keywords: 编辑 PPSX 元数据, 查看 PPSX 元数据, 编辑 PPSX 属性, 查看 PPSX 属性
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 编辑 PPSX 属性" h2="构建使用服务器端 API 修改演示文稿文件内置属性与自定义属性的 Java 应用程序。" related="FODP,ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 Java 修改 PPSX 属性" variant="code" %}}

借助 [Aspose.Slides for Java](/slides/zh/java/)，开发人员可以访问和修改演示文稿的内置属性与自定义属性。使用 `Presentation` 对象的 `getDocumentProperties` 方法访问演示文稿文件的 `IDocumentProperties` 对象。

{{< blocks/products/pf/slides-design-update-10-2026/code title="修改 PPSX 内置属性 - Java" >}}
```java
Presentation presentation = new Presentation("Presentation.ppsx");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.ppsx", SaveFormat.Ppsx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="向 PPSX 添加自定义属性 - Java" >}}
```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.ppsx", SaveFormat.Ppsx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 Java 中查看或编辑 PPSX 元数据" intro="按照以下步骤查看或编辑 PPSX 元数据。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 `PPSX` 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `getDocumentProperties` 方法获取 `IDocumentProperties` 对象。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}读取或更新 `Author`、`Title`、`Subject` 和 `Comments` 等内置属性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `set_Item`、`getCustomPropertyName` 和 `removeCustomProperty` 访问和修改自定义属性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="基于 Aspose.Slides 构建" title="在线查看和编辑 PPSX 元数据" description="免费的 Aspose.Slides Metadata 应用基于 [Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPSX 文件。" button="打开 Aspose.Slides Metadata" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何读写属性。
- 查看和编辑 PPSX 文件的内置属性与自定义属性。
- 保存并下载更新后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的元数据格式" subTitle="使用 Java，还可以管理以下格式的元数据。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
