---
title: 在 Python 中将 PPS 转换为 EMF
weight: 1560
url: /zh/python-net/conversion/pps-to-emf/ 
keywords: "Convert, PowerPoint, PPS, EMF, Presentation, Python"
description: PPS 到 EMF Python 转换的示例代码。使用 PowerPoint Python API 将 PPS 文件批量转换为 EMF 文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="在 Python 中将 PPS 转换为 EMF" h2="用于将 PPS 转换为 EMF 的强大 PowerPoint Python 库" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="在 Python 中将 PPS 转换为 EMF" %}}

需要以编程方式将 PPS 文件转换为 EMF？使用 [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/zh/python-net/) 任何开发人员只需几行 Python 代码即可将 PPS 转换为 EMF 格式。

作为现代演示处理 API，Aspose.Slides for Python 可以快速从 PPS 创建 EMF。在您的 [浏览器](https://products.aspose.app/slides/conversion) 中测试 PPS 到 EMF 转换的质量。 Aspose PowerPoint PPTX 库允许您将 PPS 文件转换为许多流行的格式。

您可以使用以下 pip 命令从 [PyPI](https://pypi.org/project/Aspose.Slides/) 安装库：

{{% blocks/products/pf/agp/code-block title="控制台/终端" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 PPS 转换为 EMF" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是使用 Python 将 PPS 文件转换为 EMF 的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 类的实例加载 PPS 文件
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在指定输出文件路径和 SaveFormat.EMF 作为参数时调用 `save` 方法
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPS文件将保存在指定路径
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 Python 转换示例源代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- 基于 Microsoft Windows 或 Linux 的操作系统（参见 [更多](https://docs.aspose.com/slides/python-net/system-requirements/)）。
- Python 3.5 或更高版本
- 项目中引用的 Python Aspose.Slides。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此示例代码显示 PPS 到 EMF Python 的转换" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.pps") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="在 Python 中将 PPS 保存为 EMF" %}}
使用免费应用程序查看 PPS 到 EMF 转换过程的演示。 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="免費應用程序將PPS轉換為EMF" 
        sectionDescription="[嘗試我們的免費Text To Gif app](https://products.aspose.app/slides/text-to-gif/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 PPS 转换为许多其他文件格式。请参阅下面的其他支持的转换" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-bmp/" name="PPS TO BMP" description="位图图像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-fodp/" name="PPS TO FODP" description="OpenDocument 平面 XML 演示文稿" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-gif/" name="PPS TO GIF" description="图形交换格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-html/" name="PPS TO HTML" description="超文本标记语言" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-jpg/" name="PPS TO JPG" description="JPEG图像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-odp/" name="PPS TO ODP" description="OpenDocument 演示格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-otp/" name="PPS TO OTP" description="OpenDocument 标准格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-pdf/" name="PPS TO PDF" description="便携式文件格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-png/" name="PPS TO PNG" description="便携式网络图形" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-pot/" name="PPS TO POT" description="Microsoft PowerPoint 模板文件" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-potm/" name="PPS TO POTM" description="微软 PowerPoint 模板文件" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-potx/" name="PPS TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-ppsm/" name="PPS TO PPSM" description="启用宏的幻灯片放映" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-ppsx/" name="PPS TO PPSX" description="幻灯片放映" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-ppt/" name="PPS TO PPT" description="微软PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-pptm/" name="PPS TO PPTM" description="启用宏的演示文件" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-pptx/" name="PPS TO PPTX" description="打开 XML 表示格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-svg/" name="PPS TO SVG" description="可缩放矢量图形" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-swf/" name="PPS TO SWF" description="SWF 格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-tiff/" name="PPS TO TIFF" description="标记图像格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/pps-to-xps/" name="PPS TO XPS" description="XML 纸张规格" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}