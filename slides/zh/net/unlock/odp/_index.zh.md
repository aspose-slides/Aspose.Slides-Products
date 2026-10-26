---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 .NET 解锁 ODP 演示文稿文件
url: /zh/net/unlock/odp/
description: 移除 ODP 演示文稿密码保护的 C# 源代码。
keywords: 移除 ODP 写保护, 解密 ODP, 解锁 ODP 演示文稿, 取消 ODP 保护
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 解锁 ODP 文件" h2="构建 .NET 应用，通过服务器端 API 移除演示文稿的加密和写保护。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C# 移除 ODP 演示文稿的保护" variant="code" %}}

借助 [Aspose.Slides for .NET](/slides/zh/net/)，您可以移除 ODP 演示文稿的加密或写保护。要移除加密，请使用正确的密码加载演示文稿并调用 `ProtectionManager.RemoveEncryption`。要移除写保护，请调用 `ProtectionManager.RemoveWriteProtection`。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 移除 ODP 演示文稿的加密" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.odp", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 移除 ODP 演示文稿的写保护" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.odp");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 移除 ODP 演示文稿的保护" intro="按照以下步骤移除 ODP 演示文稿的保护。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 加载 ODP 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}对于加密文件，请在加载前通过 `LoadOptions.Password` 提供密码。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}根据所应用的保护类型，调用 `ProtectionManager.RemoveEncryption` 或 `ProtectionManager.RemoveWriteProtection`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Odp` 保存解锁后的演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="基于 Aspose.Slides 构建" title="在线解锁 ODP 文件" description="免费的 Aspose.Slides Unlock 应用基于 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 ODP 文件。" button="打开 Aspose.Slides Unlock" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先了解 Aspose.Slides 如何移除保护。
- 移除 ODP 文件的密码或写保护。
- 下载解锁后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持解锁的格式" subTitle="使用 C#，您还可以移除以下格式的保护。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
