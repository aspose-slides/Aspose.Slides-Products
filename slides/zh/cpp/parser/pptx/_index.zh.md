---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 2290
title: 使用 C++ 从 PPTX 演示文稿中提取文本
url: /zh/cpp/parser/pptx/ 
description: 在 C++ 中从 PPTX 演示文稿提取文本。使用 Aspose.Slides for C++ 解析幻灯片、文本框、段落和文本部分。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 C++ 中解析 PPTX 演示文稿" h2="使用 Aspose.Slides for C++，无需 Microsoft PowerPoint 即可从演示文稿幻灯片中提取文本。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C++ 解析 PPTX 文件的方法" %}}

使用 Aspose.Slides for C++ 解析 PPTX 演示文稿文件并从幻灯片中提取文本。该 API 通过 `SlideUtil::GetAllTextBoxes`、`ITextFrame`、`IParagraph` 和 `IPortion` 提供幻灯片文本，因此无需自动化 Microsoft PowerPoint 即可读取文本内容。从 NuGet 安装 [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) 包，或在程序包管理器控制台中使用下面的命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="命令" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="解析 PPTX 文件 - C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 C++ 中解析 PPTX 文件" intro="使用 Aspose.Slides for C++ 从 PPTX 文件中提取文本。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SlideUtil::GetAllTextBoxes` 获取第一张幻灯片的 `ITextFrame` 对象。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍历 `ITextFrame` 对象。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍历每个 `ITextFrame` 中的 `IParagraph` 对象。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍历每个 `IParagraph` 中的 `IPortion` 对象。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `get_Text` 读取文本。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系统要求" intro="Aspose.Slides for C++ 支持主流桌面和服务器平台。请确保您的项目满足以下先决条件。" %}}

-  Microsoft Windows、Linux、macOS 或其他带有受支持 C++ 运行时的兼容操作系统。
-  在项目中引用的 Aspose.Slides for C++ 库。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="基于 Aspose.Slides 构建" title="在线提取文本和图像" description="免费的 Aspose.Slides Parser 应用基于 [Aspose.Slides for C++](https://products.aspose.com/slides/zh/cpp/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTX 文件。" button="打开 Aspose.Slides Parser" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何读取您的文件。
- 上传 PPTX 文件，获取其中的文本和图像。
- 将所有内容下载为一个 ZIP 压缩包。
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

A PPTX file is a Microsoft PowerPoint Open XML presentation file. It stores slides, text, images, formatting, animations, and other presentation content in a zipped XML-based package.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持解析的格式" subTitle="使用 C++，还可以解析其他演示文稿格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/cpp/parser/odp/" name="ODP" description="OpenDocument 演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh/cpp/parser/ppt/" name="PPT" description="PowerPoint 97-2003 演示文稿" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
