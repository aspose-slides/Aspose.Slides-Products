---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通过 Java 将 PPT 转换为 TIFF
weight: 8350
url: /zh/java/conversion/ppt-to-tiff/ 
description: PPT 格式到 TIFF 文件的示例 Java 转换代码。使用此示例代码将 PowerPoint 和 OpenOffice 演示文稿导出到任何基于 Web 或桌面 Java 的应用程序中的 TIFF。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="通过 Java 将 PPT 转换为 TIFF" h2="PPT 到 TIFF Java 转换使用本地 Java 库将单个或多个页面转换为 TIFF。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 Java 将 PPT 转换为 TIFF" %}}

为了将 PPT 渲染为 TIFF，我们将使用
 [Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/)
 API 是一个功能丰富、功能强大且易于使用的 Java 平台转换 API。您可以直接从
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 并通过将以下配置添加到 pom.xml 将其安装在基于 Maven 的项目中。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="存储库" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="依赖" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT转TIFF Java转换源码" >}}
```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("template.ppt");
// save the presentation as TIFF
presentation.save("output.tiff", SaveFormat.Tiff);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="通过 Java 将 PPT 转换为 TIFF 的步骤" intro="Java 开发人员只需几行代码即可轻松地将 PPT 文件转换为 TIFF。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加载带有Presentation类实例的PPT文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在指定输出文件路径和SaveFormat时调用Presentation.save方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}TIFF文件将保存在指定路径{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系统要求" intro="在运行 Java 转换示例代码之前，请确保您具有以下先决条件。" %}}

- Microsoft Windows 或与 JSP/JSF 应用程序和桌面应用程序的 Java 运行时环境兼容的操作系统。
- 直接从 Maven 获取最新版本的 Aspose.Slides for Java。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="基于 Aspose.Slides 构建" title="在线将 PPT 转换为 TIFF" description="免费的 Aspose.Slides Conversion 应用基于 [Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPT 文件。" button="打开 Aspose.Slides Conversion" note="[所有免费应用](https://products.aspose.app/slides/family)" upload="拖放或上传您的文件" saveAs="另存为" convert="转换" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何转换文件。
- 上传 PPT 文件并将其另存为 TIFF。
- 下载结果或转换更多文件。
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的转换" subTitle="您还可以将 PPT 转换为许多其他文件格式，包括下面列出的一些文件格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-bmp/" name="PPT TO BMP" description="位图图像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-gif/" name="PPT TO GIF" description="图形交换格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-html/" name="PPT TO HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-jpeg/" name="PPT TO JPEG" description="JPEG图像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-odp/" name="PPT TO ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-otp/" name="PPT TO OTP" description="OpenDocument 标准格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-pdf/" name="PPT TO PDF" description="便携式文件格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-png/" name="PPT TO PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-pot/" name="PPT TO POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-potm/" name="PPT TO POTM" description="微软 PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-potx/" name="PPT TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-pps/" name="PPT TO PPS" description="幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-ppsm/" name="PPT TO PPSM" description="启用宏的幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-ppsx/" name="PPT TO PPSX" description="幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-pptm/" name="PPT TO PPTM" description="启用宏的演示文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-pptx/" name="PPT TO PPTX" description="打开 XML 表示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-svg/" name="PPT TO SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-swf/" name="PPT TO SWF" description="SWF 格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/ppt-to-xps/" name="PPT TO XPS" description="XML 纸张规格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
