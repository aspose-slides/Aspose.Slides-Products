---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 1000
title: 使用 Java 從 PPTX 文件擷取文字
url: /zh-hant/java/parser/pptx/ 
description: 使用 Aspose.Slides for Java 在 Java 中從 PPTX 檔案擷取文字。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 Java 中剖析 PPTX 檔案" h2="使用 Aspose.Slides for Java 的伺服器端 API 從 PPTX 文件擷取文字與簡報內容。"
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Java 剖析 PPTX 檔案的方法" %}}

使用 [Aspose.Slides for Java](/slides/zh-hant/java/) 剖析 PPTX 簡報並從投影片擷取文字。在 `pom.xml` 檔案中使用下方的存放庫與相依性設定，即可將程式庫加入以 Maven 為基礎的專案。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="存放庫" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="相依性" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="剖析 PPTX 檔案 - Java" >}}
```java
Presentation presentation = new Presentation("demo.pptx");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 Java 中剖析 PPTX 檔案" intro="使用 Aspose.Slides for Java，只需幾行程式碼即可從 PPTX 簡報擷取文字。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 `PPTX` 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}呼叫 `SlideUtil.getAllTextBoxes` 方法取得第一張投影片的文字框。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}逐一處理每個 `ITextFrame`、`IParagraph` 和 `IPortion` 物件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}從每個 `IPortion` 物件讀取文字、字型大小和字型名稱。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系統需求" intro="Aspose.Slides for Java 支援主要平台和作業系統。請確認您的環境符合下列先決條件。" %}}

- Microsoft Windows 或具備 Java Runtime Environment 的相容作業系統，適用於 JSP/JSF 應用程式和桌面應用程式。
- 來自 [Maven](https://releases.aspose.com/java/repo/) 的最新版 Aspose.Slides for Java。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="以 Aspose.Slides 建置" title="線上擷取文字與影像" description="免費的 Aspose.Slides Parser 應用程式以 [Aspose.Slides for Java](https://products.aspose.com/slides/zh-hant/java/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPTX 檔案。" button="開啟 Aspose.Slides Parser" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先看看 Aspose.Slides 如何讀取您的檔案。
- 上傳 PPTX 檔案，取得其中的文字與影像。
- 將所有內容下載為一個 ZIP 壓縮檔。
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

Files with the PPTX extension use the Office Open XML presentation format. A PPTX file stores slides that can contain text, images, formatting, animations, and other presentation content.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援剖析的格式" subTitle="使用 Java，也可以剖析其他簡報格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/parser/odp/" name="ODP" description="OpenDocument 簡報" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/java/parser/ppt/" name="PPT" description="PowerPoint 97-2003 簡報" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
