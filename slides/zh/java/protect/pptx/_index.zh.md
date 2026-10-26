---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Java 保护 PPTX 演示文稿文件
url: /zh/java/protect/pptx/
description: 在 Java 中保护 PPTX 演示文稿。使用 Aspose.Slides for Java 加密演示文稿文件并设置写保护。
keywords: PPTX 写保护, 加密 PPTX 文件, 锁定 PPTX 演示文稿, 保护 PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 锁定 PPTX 或为其设置密码保护" h2="构建通过服务器端 API 保护演示文稿文件的 Java 应用程序。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 Java 保护 PPTX 演示文稿" variant="code" %}}

借助 [Aspose.Slides for Java](/slides/zh/java/)，您可以通过设置密码防止 PPTX 演示文稿被打开或修改。使用 `Presentation` 类中的 `ProtectionManager` 对象调用 `encrypt` 和 `setWriteProtection` 等方法。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 加密 PPTX 演示文稿" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 为 PPTX 演示文稿设置写保护" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通过 Java 为 PPTX 设置密码保护" intro="按照以下步骤保护 PPTX 演示文稿。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `ProtectionManager` 对象的 `encrypt` 方法或 `setWriteProtection` 方法。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Pptx` 保存受保护的文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="基于 Aspose.Slides 构建" title="在线为 PPTX 文件设置密码保护" description="免费的 Aspose.Slides Lock 应用基于 [Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTX 文件。" button="打开 Aspose.Slides Lock" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先了解 Aspose.Slides 如何保护演示文稿。
- 设置打开或编辑 PPTX 文件所需的密码。
- 下载受保护的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持保护的格式" subTitle="使用 Java，您还可以保护以下格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
