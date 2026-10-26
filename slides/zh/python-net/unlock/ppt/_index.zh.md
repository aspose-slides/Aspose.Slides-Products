---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 解锁 PPT 演示文稿
url: /zh/python-net/unlock/ppt/
description: 使用 Python 移除 PPT 演示文稿的加密和写保护。
keywords: 解锁 PPT, 移除 PPT 密码, 移除 PPT 加密, 移除 PPT 写保护
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 解锁 PPT 演示文稿" h2="构建使用 Aspose.Slides 移除 PPT 演示文稿打开密码和写保护设置的 Python 应用程序。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 移除 PPT 的加密和写保护" variant="code" %}}

借助 [Aspose.Slides for Python via .NET](/slides/zh/python-net/)，您可以移除打开 PPT 演示文稿时需要输入密码的加密，或清除其写保护设置。要打开加密文件，请通过 `LoadOptions` 提供当前密码。

{{< blocks/products/pf/slides-design-update-10-2026/code title="移除 PPT 演示文稿的加密 – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.ppt", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="移除 PPT 演示文稿的写保护 – Python" >}}
```py
with slides.Presentation("write-protected-presentation.ppt") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 移除 PPT 的保护" intro="按照以下步骤移除 PPT 演示文稿的保护。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}对于加密的 PPT 文件，请在 `LoadOptions` 中设置当前密码，然后使用 `Presentation` 打开文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 `ProtectionManager.remove_encryption` 移除打开密码，或调用 `ProtectionManager.remove_write_protection` 清除写保护。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.PPT` 保存生成的演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="基于 Aspose.Slides 构建" title="在线解锁 PPT 文件" description="免费的 Aspose.Slides Unlock 应用基于 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh/python-net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPT 文件。" button="打开 Aspose.Slides Unlock" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先了解 Aspose.Slides 如何移除保护。
- 移除 PPT 文件的密码或写保护。
- 下载解锁后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持解锁的格式" subTitle="使用 Python 移除其他受支持演示文稿格式的保护。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
