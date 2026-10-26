---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C++ 解锁 PPTX 演示文稿
url: /zh/cpp/unlock/pptx/
description: 在 C++ 中解锁 PPTX 演示文稿。使用 Aspose.Slides for C++ 移除演示文稿文件的加密和写保护。
keywords: 移除 PPTX 写保护, 解密 PPTX, 解锁 PPTX 演示文稿, 取消 PPTX 保护
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 解锁 PPTX" h2="使用 Aspose.Slides for C++ 移除演示文稿文件的加密和写保护，无需 Microsoft PowerPoint。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 C++ 移除 PPTX 演示文稿的保护" variant="code" %}}

Aspose.Slides for C++ 可以移除 PPTX 演示文稿的加密或写保护。使用 `LoadOptions` 打开加密文件，然后使用 `Presentation` 类中的 `ProtectionManager` 对象调用 `RemoveEncryption` 或 `RemoveWriteProtection`。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 移除 PPTX 的密码保护" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 移除 PPTX 演示文稿的写保护" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通过 C++ 移除 PPTX 的密码" intro="按照以下步骤移除 PPTX 演示文稿的保护。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 PPTX 文件，需要密码时同时使用 `LoadOptions`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `ProtectionManager` 对象移除保护。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}对加密文件调用 `RemoveEncryption`，对写保护文件调用 `RemoveWriteProtection`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat::Pptx` 保存解锁后的文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="基于 Aspose.Slides 构建" title="在线解锁 PPTX 文件" description="免费的 Aspose.Slides Unlock 应用基于 [Aspose.Slides for C++](https://products.aspose.com/slides/zh/cpp/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTX 文件。" button="打开 Aspose.Slides Unlock" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先了解 Aspose.Slides 如何移除保护。
- 移除 PPTX 文件的密码或写保护。
- 下载解锁后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持解锁的格式" subTitle="使用 C++，您还可以移除以下格式的保护。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/cpp/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
