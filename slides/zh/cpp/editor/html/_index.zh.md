---
title: 在 C++ 中编辑 HTML
url: /zh/cpp/editor/html/
keywords: 编辑 HTML、HTML、C++ API、C++ 库
description: 在 C++ 中编辑 HTML。使用 C++ 库 API 编辑 HTML 文件
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 C++ 中编辑 HTML" h2="用于使用 C++ 代码编辑 HTML 的高速跨平台 C++ 库" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 编辑 HTML" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/) 是一个功能强大的 C++ 库，用于操作和编辑演示文稿、HTML 文档和其他文件。您可以通过向其中添加新的文本行来编辑 HTML 文档。 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 C++ 中编辑 HTML" %}}
使用 [**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/)，只需几行代码即可向 HTML 文档添加新的文本行。

{{% blocks/products/pf/agp/code-block title="用于编辑 HTML 的 C++ 代码" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromHtml(htmlText1);

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"page.html", SaveFormat::Html5);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 C++ 中编辑 HTML" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
安装**Aspose.Slides for C++**。请参阅 [**安装**](https://docs.aspose.com/slides/cpp/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库添加为项目中的参考。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
创建一个 Presentation 类的实例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加载要编辑的 HTML 文档。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加新的文本行。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存更改后的 HTML 文件。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="编辑其他文件" subTitle="您还可以编辑其他格式的文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}