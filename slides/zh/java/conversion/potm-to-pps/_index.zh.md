---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通过 Java 将 POTM 转换为 PPS
weight: 7190
url: /zh/java/conversion/potm-to-pps/ 
description: POTM 格式到 PPS 文件的示例 Java 转换代码。使用此示例代码将 PowerPoint 和 OpenOffice 演示文稿导出到任何基于 Web 或桌面 Java 的应用程序中的 PPS。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="通过 Java 将 POTM 转换为 PPS" h2="POTM 到 PPS Java 转换使用本地 Java 库将单个或多个页面转换为 PPS。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 Java 将 POTM 转换为 PPS" %}}

为了将 POTM 渲染为 PPS，我们将使用
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="POTM 到 PPS Java 转换源代码" >}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("template.potm");
// save the presentation as PPS
presentation.save("output.pps", SaveFormat.Pps);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="通过 Java 将 POTM 转换为 PPS 的步骤" intro="Java 开发人员只需几行代码即可轻松地将 POTM 文件转换为 PPS。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Presentation 类的实例加载 POTM 文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在指定输出文件路径和SaveFormat时调用Presentation.save方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPS文件将保存在指定路径{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系统要求" intro="在运行 Java 转换示例代码之前，请确保您具有以下先决条件。" %}}

- Microsoft Windows 或与 JSP/JSF 应用程序和桌面应用程序的 Java 运行时环境兼容的操作系统。
- 直接从 Maven 获取最新版本的 Aspose.Slides for Java。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="免費應用程序將POTM轉換為PPS"
  description="[嘗試我們的免費MP4 To MP3 app](https://products.aspose.app/slides/video/mp4-to-mp3/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的转换" subTitle="您还可以将 POTM 转换为许多其他文件格式，包括下面列出的一些文件格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-bmp/" name="POTM TO BMP" description="位图图像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-gif/" name="POTM TO GIF" description="图形交换格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-html/" name="POTM TO HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-jpeg/" name="POTM TO JPEG" description="JPEG图像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-odp/" name="POTM TO ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-otp/" name="POTM TO OTP" description="OpenDocument 标准格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-pdf/" name="POTM TO PDF" description="便携式文件格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-png/" name="POTM TO PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-pot/" name="POTM TO POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-potx/" name="POTM TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="启用宏的幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-ppt/" name="POTM TO PPT" description="微软PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-pptm/" name="POTM TO PPTM" description="启用宏的演示文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-pptx/" name="POTM TO PPTX" description="打开 XML 表示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-svg/" name="POTM TO SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-swf/" name="POTM TO SWF" description="SWF 格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-tiff/" name="POTM TO TIFF" description="标记图像格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/java/conversion/potm-to-xps/" name="POTM TO XPS" description="XML 纸张规格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
