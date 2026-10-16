---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通過 Java 將 OTP 轉換為 GIF
weight: 4650
url: /zh-hant/java/conversion/otp-to-gif/ 
description: OTP 格式到 GIF 文件的示例 Java 轉換代碼。使用此示例代碼可在任何基於 Web 或桌面 Java 的應用程序中將 PowerPoint 和 OpenOffice 演示文稿導出為 GIF。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="通過 Java 將 OTP 轉換為 GIF" h2="OTP 到 GIF Java 轉換使用本地 Java 庫將單個或多個頁面轉換為 GIF。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 Java 將 OTP 轉換為 GIF" %}}

為了將 OTP 渲染為 GIF，我們將使用
 [Aspose.Slides for Java](https://products.aspose.com/slides/zh-hant/java/)
 API 是一個功能豐富、功能強大且易於使用的 Java 平台轉換 API。您可以直接從
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 並通過將以下配置添加到 pom.xml 將其安裝在基於 Maven 的項目中。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="存儲庫" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="依賴" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="OTP轉GIF Java源代碼" >}}
```cs
// load OTP with Aspose.Slides
Presentation presentation = new Presentation("template.otp");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type GIF for every slide
  File outputfile = new File(sld.getSlideNumber() + ".gif");
  
  // save the slide image to disk
  ImageIO.write(bi, "gif", outputfile);
}   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="通過 Java 將 OTP 轉換為 GIF 的步驟" intro="Java 開發人員只需幾行代碼即可輕鬆地將 OTP 文件轉換為 GIF。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Presentation 類的實例加載 OTP 文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍歷演示文稿中的每張幻燈片{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}每次迭代創建一個全尺寸圖像作為位圖{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}調用帶有GIF文件擴展名和ImageFormat的Bitmap.save方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統要求" intro="在運行 Java 轉換示例代碼之前，請確保您具有以下先決條件。" %}}

- Microsoft Windows 或與 JSP/JSF 應用程序和桌面應用程序的 Java 運行時環境兼容的操作系統。
- 直接從 Maven 獲取最新版本的 Aspose.Slides for Java。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="免費應用程序將OTP轉換為GIF"
  description="[嘗試我們的免費MP4 To MP3 app](https://products.aspose.app/slides/video/mp4-to-mp3/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的轉換" subTitle="您還可以將 OTP 轉換為許多其他文件格式，包括下面列出的幾種文件格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-bmp/" name="OTP TO BMP" description="位圖圖像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-html/" name="OTP TO HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-jpeg/" name="OTP TO JPEG" description="JPEG圖像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-odp/" name="OTP TO ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-pdf/" name="OTP TO PDF" description="便攜式文件格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-png/" name="OTP TO PNG" description="便攜式網絡圖形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-pot/" name="OTP TO POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-potm/" name="OTP TO POTM" description="微軟 PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-potx/" name="OTP TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-pps/" name="OTP TO PPS" description="幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="啟用宏的幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="幻燈片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-ppt/" name="OTP TO PPT" description="微軟PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="啟用宏的演示文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="打開 XML 表示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-svg/" name="OTP TO SVG" description="可縮放矢量圖形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-swf/" name="OTP TO SWF" description="SWF 格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="標記圖像格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/conversion/otp-to-xps/" name="OTP TO XPS" description="XML 紙張規格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
