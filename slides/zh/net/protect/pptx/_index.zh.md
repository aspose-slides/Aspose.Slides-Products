---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 .NET 保护 PPTX 演示文稿文件
url: /zh/net/protect/pptx/
description: 使用密码保护 PPTX 演示文稿的 C# 源代码。
keywords: PPTX 写保护, 加密 PPTX, 锁定 PPTX 演示文稿, 保护 PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 锁定 PPTX 文件或为其设置密码保护" h2="构建 .NET 应用，通过服务器端 API 加密演示文稿并限制修改。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C# 保护 PPTX 演示文稿" variant="code" %}}

借助 [Aspose.Slides for .NET](/slides/zh/net/)，您可以加密 PPTX 演示文稿，或使用密码限制对其的修改。打开使用 `ProtectionManager.Encrypt` 加密的演示文稿需要输入密码。使用 `ProtectionManager.SetWriteProtection` 可以允许打开演示文稿，同时限制更改。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 加密 PPTX 演示文稿" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 为 PPTX 演示文稿设置写保护" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 为 PPTX 演示文稿设置密码保护" intro="按照以下步骤为 PPTX 演示文稿设置密码保护。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 加载 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `ProtectionManager.Encrypt` 加密演示文稿，或使用 `ProtectionManager.SetWriteProtection` 限制更改。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Pptx` 保存受保护的文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="基于 Aspose.Slides 构建" title="在线为 PPTX 文件设置密码保护" description="免费的 Aspose.Slides Lock 应用基于 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTX 文件。" button="打开 Aspose.Slides Lock" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先了解 Aspose.Slides 如何保护演示文稿。
- 设置打开或编辑 PPTX 文件所需的密码。
- 下载受保护的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持保护的格式" subTitle="使用 C#，您还可以保护以下格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
