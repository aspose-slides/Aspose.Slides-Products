---
title: Search ODP document without opening via Java 
weight: 1250
url: /java/search/odp/ 
description: Java sample code to search words with pattern in ODP file on Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Search ODP Formats in Java" h2="Native and high performance ODP document search using server-side Aspose.Slides for Java APIs, without the use of any software like Microsoft or Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="How to Search ODP File Using Java" %}}

 In order to search ODP file, we’ll use
 [Aspose.Slides for Java](https://products.aspose.com/slides/java) 
 API which is a feature-rich, powerful and easy to use Search API for Java platform. You can download its latest version directly from
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides) 
 and install it within your Maven-based project by adding the following configurations to the pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

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


{{< blocks/products/pf/agp/feature-section-col title="Steps to Search ODP Files in Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="A basic document search using Aspose.Slides APIs can be done with just few lines of code." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load ODP file by instantiating Presentation Class object.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Get an ITextFrame Objects Array from all slides.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Loop through the Array.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Loop through paragraphs in current ITextFrame.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Loop through portions in the current IParagraph.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Find and Display font height and font name.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Java supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with Java Runtime Environment for JSP/JSF Application and Desktop Applications.
-  Get latest version of Aspose.Slides for Java directly from
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Search ODP Files - Java" offSpacer="" %}}

```cs
//Load a ODP file
Presentation odpPresentation = new Presentation("demo.odp");
try 
{
    //Get an Array of ITextFrame objects from all slides
    ITextFrame[] textFramesPPTX = SlideUtil.getAllTextFrames(odpPresentation, true);

    //Loop through the Array of TextFrames
    for (int i = 0; i < textFramesPPTX.length; i++)
    {
        //Loop through paragraphs in current ITextFrame
        for(IParagraph para : textFramesPPTX[i].getParagraphs()) {
            //Loop through portions in the current IParagraph
            for (IPortion port : para.getPortions()) {
                //Find and Display text in the current portion
                System.out.print(port.getText());

                //Find and Display font height of the text
                System.out.print(port.getPortionFormat().getFontHeight());

                //Find and Display font name of the text
                if (port.getPortionFormat().getLatinFont() != null)
                    System.out.print(port.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    if (odpPresentation != null) odpPresentation.dispose();
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="About Aspose.Slides for Java API" %}}

 Aspose.Slides API can be used to read, write, manipulate and convert Microsoft PowerPoint documents to PDF, XPS, HTML, TIFF, ODP and various other formats. One can create new files from scratch and save those in the relevant supported formats. Aspose.Slides is a standalone API for creating, parsing or manipulating presentations, slides and elements and it does not depend on any software like Microsoft or OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Search Live Demos" sectionDescription="Search text, words, phrases within ODP documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/search). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your ODP files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Search result appears instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/about-file-text fileFormat="ODP " readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice). 

    {{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Search Documents" subTitle="Using Java, one can also search other files including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/search/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/search/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}