---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 Python 保护 ODP 演示文稿文件
url: /zh/python-net/protect/odp/
description: 使用 Python 加密 ODP 演示文稿或设置写保护。
keywords: ODP 写保护, 使用 Python 加密 ODP, 锁定 ODP 演示文稿, 使用 Python 保护 ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 Python 保护 ODP 演示文稿" h2="构建使用 Aspose.Slides 加密演示文稿或设置写保护的 Python 应用程序。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Python 保护 ODP 演示文稿" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/zh/python-net/) 提供两种不同的保护机制。调用 `ProtectionManager.encrypt` 可加密 ODP 演示文稿，打开时需要输入密码。也可以调用 `ProtectionManager.set_write_protection`，在不加密文件的情况下阻止修改。用户仍可打开写保护的演示文稿，并将更改保存到其他文件中。

{{< blocks/products/pf/slides-design-update-10-2026/code title="加密 ODP 演示文稿 – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="为 ODP 演示文稿设置写保护 – Python" >}}
```python
with slides.Presentation("presentation.odp") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.odp", slides.export.SaveFormat.ODP)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Python 保护 ODP" intro="按照以下步骤保护 ODP 文件。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 打开 ODP 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `ProtectionManager.encrypt` 要求打开时输入密码，或使用 `ProtectionManager.set_write_protection` 阻止更改。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.ODP` 将受保护的演示文稿另存为 ODP。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="基于 Aspose.Slides 构建" title="在线为 ODP 文件设置密码保护" description="免费的 Aspose.Slides Lock 应用基于 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/zh/python-net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 ODP 文件。" button="打开 Aspose.Slides Lock" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先了解 Aspose.Slides 如何保护演示文稿。
- 设置打开或编辑 ODP 文件所需的密码。
- 下载受保护的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持保护的格式" subTitle="使用 Python 保护其他受支持的演示文稿格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
