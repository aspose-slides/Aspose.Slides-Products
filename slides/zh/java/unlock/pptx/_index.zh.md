---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Java 解锁 PPTX 演示文稿文件
url: /zh/java/unlock/pptx/
description: 使用 Aspose.Slides for Java 在 Java 中移除 PPTX 演示文稿的密码和写保护。
keywords: 移除 PPTX 写保护, 解密 PPTX, 解锁 PPTX 演示文稿, 取消 PPTX 保护
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Java 解锁 PPTX" h2="构建通过服务器端 API 移除演示文稿文件密码和写保护的 Java 应用程序。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 Java 移除 PPTX 演示文稿的保护" variant="code" %}}

借助 [Aspose.Slides for Java](/slides/zh/java/)，您可以移除 PPTX 演示文稿的加密或写保护。使用 `LoadOptions.setPassword` 打开加密的演示文稿，并使用 `ProtectionManager` 的 `removeEncryption` 和 `removeWriteProtection` 方法移除保护设置。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 移除 PPTX 的密码保护" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.pptx", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 Java 移除 PPTX 演示文稿的写保护" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通过 Java 移除 PPTX 的密码" intro="按照以下步骤移除 PPTX 演示文稿的保护。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}如果演示文稿已加密，请使用 `LoadOptions.setPassword`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `ProtectionManager` 对象的 `removeEncryption` 或 `removeWriteProtection`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Pptx` 保存解锁后的演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="基于 Aspose.Slides 构建" title="在线解锁 PPTX 文件" description="免费的 Aspose.Slides Unlock 应用基于 [Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTX 文件。" button="打开 Aspose.Slides Unlock" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先了解 Aspose.Slides 如何移除保护。
- 移除 PPTX 文件的密码或写保护。
- 下载解锁后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持解锁的格式" subTitle="使用 Java，您还可以移除以下格式的保护。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/java/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
