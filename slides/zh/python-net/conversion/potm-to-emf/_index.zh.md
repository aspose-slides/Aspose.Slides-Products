---
title: 在 Python 中将 POTM 转换为 EMF
weight: 1120
url: /zh/python-net/conversion/potm-to-emf/ 
keywords: "Convert, PowerPoint, POTM, EMF, Presentation, Python"
description: POTM 到 EMF Python 转换的示例代码。使用 PowerPoint Python API 将 POTM 文件批量转换为 EMF 文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="在 Python 中将 POTM 转换为 EMF" h2="用于将 POTM 转换为 EMF 的强大 PowerPoint Python 库" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="在 Python 中将 POTM 转换为 EMF" %}}

需要以编程方式将 POTM 文件转换为 EMF？使用 [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/zh/python-net/) 任何开发人员只需几行 Python 代码即可将 POTM 转换为 EMF 格式。

作为现代演示处理 API，Aspose.Slides for Python 从 POTM 快速创建 EMF。在您的 [浏览器](https://products.aspose.app/slides/conversion) 中测试 POTM 到 EMF 转换的质量。 Aspose PowerPoint PPTX 库允许您将 POTM 文件转换为许多流行的格式。

您可以使用以下 pip 命令从 [PyPI](https://pypi.org/project/Aspose.Slides/) 安装库：

{{% blocks/products/pf/agp/code-block title="控制台/终端" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 POTM 转换为 EMF" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是使用 Python 将 POTM 文件转换为 EMF 的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 类的实例加载 POTM 文件
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在指定输出文件路径和 SaveFormat.EMF 作为参数时调用 `save` 方法
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
POTM 文件将保存在指定路径
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

{{% blocks/products/pf/agp/code-block title="此示例代码显示 POTM 到 EMF Python 的转换" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.potm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="在 Python 中将 POTM 保存为 EMF" %}}
使用免费应用程序查看 POTM 到 EMF 转换过程的演示。 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="potm-to-emf"
        sectionTitle="免費應用程序將POTM轉換為EMF" 
        sectionDescription="[嘗試我們的免費Video app](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 POTM 转换为许多其他文件格式。请参阅下面的其他支持的转换" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-bmp/" name="POTM TO BMP" description="位图图像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-fodp/" name="POTM TO FODP" description="OpenDocument 平面 XML 演示文稿" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-gif/" name="POTM TO GIF" description="图形交换格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-html/" name="POTM TO HTML" description="超文本标记语言" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-jpg/" name="POTM TO JPG" description="JPEG图像" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-odp/" name="POTM TO ODP" description="OpenDocument 演示格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-otp/" name="POTM TO OTP" description="OpenDocument 标准格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-pdf/" name="POTM TO PDF" description="便携式文件格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-png/" name="POTM TO PNG" description="便携式网络图形" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-pot/" name="POTM TO POT" description="Microsoft PowerPoint 模板文件" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-potx/" name="POTM TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-pps/" name="POTM TO PPS" description="幻灯片放映" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="启用宏的幻灯片放映" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="幻灯片放映" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-ppt/" name="POTM TO PPT" description="微软PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-pptm/" name="POTM TO PPTM" description="启用宏的演示文件" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-pptx/" name="POTM TO PPTX" description="打开 XML 表示格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-svg/" name="POTM TO SVG" description="可缩放矢量图形" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-swf/" name="POTM TO SWF" description="SWF 格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-tiff/" name="POTM TO TIFF" description="标记图像格式" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/python-net/conversion/potm-to-xps/" name="POTM TO XPS" description="XML 纸张规格" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}