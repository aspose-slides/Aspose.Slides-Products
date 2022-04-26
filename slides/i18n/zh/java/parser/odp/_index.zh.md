---
title: 通过 Java 从 ODP 文档中提取文本和图像
weight: 5200
url: /zh/java/parser/odp/ 
description: 用于从 JSP/JSF 应用程序和桌面应用程序的 Java 运行时环境中的 ODP 文件中提取文本和图像的 Java 示例代码。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="在 Java 中解析 ODP 格式" h2="使用用于 Java API 的服务器端 Aspose.Slides 进行本机和高性能 ODP 文档解析，无需使用 Microsoft 或 Adob​​e PDF 等任何软件。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="https://www.nuget.org/packages/aspose.slides.java" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 解析 ODP 文件" %}}

 为了解析 ODP 文件，我们将使用
 [Aspose.Slides for Java](https://products.aspose.com/slides/java)
 API 是一个功能丰富、功能强大且易于使用的 Java 平台解析 API。您可以直接从
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 并通过将以下配置添加到 pom.xml 将其安装在基于 Maven 的项目中。

{{% blocks/products/pf/agp/code-block title="存储库" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依赖" offSpacer="true" %}}

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


{{< blocks/products/pf/agp/feature-section-col title="在 Java 中解析 ODP 文件的步骤" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="使用 [Aspose.Slides for Java](https://products.aspose.com/slides/java) API 解析基本文档只需几行代码即可完成。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
通过实例化 Presentation 类加载 ODP 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
获取第一张幻灯片文本框架。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
循环遍历每个段落部分。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
获取所需的输出，如文本、字体等。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Java 支持所有主要平台和操作系统。请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- 适用于 JSP/JSF 应用程序和桌面应用程序的 Microsoft Windows 或具有 Java 运行时环境的兼容操作系统。
- 直接从 Java 获取最新版本的 Aspose.Slides
 [Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides）。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="解析 ODP 文件 - Java" offSpacer="" %}}

```cs
//Load ODP file
Presentation odpPresentation = new Presentation("demo.odp");
try{
    //Get an Array of TextFrameEx objects from the first slide
    ITextFrame[] textFramesSlideOne = SlideUtil.getAllTextBoxes(odpPresentation.getSlides().get_Item(0));

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
    if (odpPresentation != null) odpPresentation.dispose();
}
//Similarly extarcting text from the Whole Presentation
//Use getAllTextFrames(odpPresentation, true) method and Iterate through Array   

    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="关于 Aspose.Slides for Java API" %}}

 Aspose.Slides API 可用于读取、编写、操作 Microsoft PowerPoint 文档并将其转换为 PDF、XPS、HTML、TIFF、ODP 和各种其他格式。可以从头开始创建新文件并将其保存为相关支持的格式。 Aspose.Slides 是一个独立的 API，用于创建、解析或操作演示文稿、幻灯片和元素，它不依赖于 Microsoft 或 OpenOffice 等任何软件。  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Parser Live Demos" sectionDescription="Extract text and images from ODP documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/parser). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODP files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be parsed instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice). 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的解析文档" subTitle="使用 Java，可以轻松解析其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/parser/ppt/" name="PPT" description="微软PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/parser/pptx/" name="PPTX" description="打开 XML 表示格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}