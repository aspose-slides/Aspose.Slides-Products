---
title: 通過 Java 從 PPTX 文檔中提取文本和圖像
weight: 1000
url: /zh-hant/java/parser/pptx/ 
description: Java 示例代碼，用於從 JSP/JSF 應用程序和桌面應用程序的 Java 運行時環境中的 PPTX 文件中提取文本和圖像。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="在 Java 中解析 PPTX 格式" h2="使用用於 Java API 的服務器端 Aspose.Slides 進行本機和高性能 PPTX 文檔解析，無需使用 Microsoft 或 Adob​​e PDF 等任何軟件。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="https://www.nuget.org/packages/aspose.slides.java" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 解析 PPTX 文件" %}}

 為了解析 PPTX 文件，我們將使用
 [Aspose.Slides for Java](https://products.aspose.com/slides/java)
 API 是一個功能豐富、功能強大且易於使用的 Java 平台解析 API。您可以直接從
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 並通過將以下配置添加到 pom.xml 將其安裝在基於 Maven 的項目中。

{{% blocks/products/pf/agp/code-block title="存儲庫" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依賴" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="在 Java 中解析 PPTX 文件的步驟" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="使用 [Aspose.Slides for Java](https://products.aspose.com/slides/java) API 解析基本文檔只需幾行代碼即可完成。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
通過實例​​化 Presentation 類加載 PPTX 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
獲取第一張幻燈片文本框架。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
循環遍歷每個段落部分。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
獲取所需的輸出，如文本、字體等。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Java 支持所有主要平台和操作系統。請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或與 JSP/JSF 應用程序和桌面應用程序的 Java 運行時環境兼容的操作系統。
- 直接從 Java 獲取最新版本的 Aspose.Slides
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="解析 PPTX 文件 - Java" offSpacer="" %}}

```cs
//Load PPTX file
Presentation pptxPresentation = new Presentation("demo.pptx");
try{
    //Get an Array of TextFrameEx objects from the first slide
    ITextFrame[] textFramesSlideOne = SlideUtil.getAllTextBoxes(pptxPresentation.getSlides().get_Item(0));

    //Loop through the Array of TextFrames
    for (int i = 0; i < textFramesSlideOne.length; i++){
        //Loop through paragraphs in current TextFrame
        for (IParagraph para : textFramesSlideOne[0].getParagraphs()){
            //Loop through portions in the current Paragraph
            for (IPortion port : para.getPortions()){
                //Display text in the current portion
                System.out.print(port.getText());

                //Display font height of the text
                System.out.print(port.getPortionFormat().getFontHeight());

                //Display font name of the text
                System.out.print(port.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    if (pptxPresentation != null) pptxPresentation.dispose();
}
//Similarly extarcting text from the Whole Presentation
//Use getAllTextFrames(pptxPresentation, true) method and Iterate through Array   

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="關於 Aspose.Slides for Java API" %}}

 Aspose.Slides API 可用於讀取、寫入、操作 Microsoft PowerPoint 文檔並將其轉換為 PDF、XPS、HTML、TIFF、ODP 和各種其他格式。可以從頭開始創建新文件並將其保存為相關支持的格式。 Aspose.Slides 是一個獨立的 API，用於創建、解析或操作演示文稿、幻燈片和元素，它不依賴於 Microsoft 或 OpenOffice 等任何軟件。  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Parser Live Demos" sectionDescription="Extract text and images from PPTX documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/parser). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPTX files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be parsed instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的解析文檔" subTitle="使用 Java，可以輕鬆解析其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/parser/odp/" name="ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/parser/ppt/" name="PPT" description="微軟PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}