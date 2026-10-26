---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C++ 对 ODP 演示文稿脱敏
url: /zh/cpp/redaction/odp/
description: 在 C++ 中对 ODP 演示文稿进行脱敏。使用 Aspose.Slides for C++ 查找并替换演示文稿文件中的敏感文本。
keywords: ODP 脱敏，在 ODP 中查找和替换文本，更新 ODP 演示文稿
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 对 ODP 进行脱敏" h2="使用 Aspose.Slides for C++ 查找并替换演示文稿文件中的敏感文本，无需 Microsoft PowerPoint。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="通过 C++ 对 ODP 演示文稿进行脱敏" variant="code" %}}

Aspose.Slides for C++ 可以通过替换幻灯片中的敏感文本，对 ODP 演示文稿进行脱敏。将 `SlideUtil::FindAndReplaceText` 与 `Presentation` 对象结合使用来搜索演示文稿，并在保存更新后的文件之前替换匹配的文本。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 对 ODP 演示文稿进行脱敏" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何通过 C++ 对 ODP 进行脱敏" intro="按照以下步骤对 ODP 演示文稿进行脱敏。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 ODP 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) 方法查找并替换敏感文本。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat::Odp` 保存脱敏后的文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="基于 Aspose.Slides 构建" title="在线对 ODP 文件进行脱敏" description="免费的 Aspose.Slides Redaction 应用基于 [Aspose.Slides for C++](https://products.aspose.com/slides/zh/cpp/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 ODP 文件。" button="打开 Aspose.Slides Redaction" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，了解 Aspose.Slides 如何查找和替换文本。
- 在您的 ODP 文件中查找和替换文本，支持正则表达式。
- 下载脱敏后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持脱敏的格式" subTitle="使用 C++，您还可以对以下格式进行脱敏。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
