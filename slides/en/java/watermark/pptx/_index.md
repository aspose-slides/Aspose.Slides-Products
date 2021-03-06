---
title: Watermark PPTX document via Java 
weight: 4930
url: /java/watermark/pptx/ 
description: Java sample code to add or remove watermark to PPTX file on Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Add Text Watermark to PPTX via Java" h2="Build your own Java apps to watermark PPTX files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="How to Watermark PPTX File Using Java" %}}

 In order to watermark PPTX file, we’ll use
 [Aspose.Slides for Java](https://products.aspose.com/slides/java) 
 API which is a feature-rich, powerful and easy to use watermarking API for Java platform. You can download its latest version directly from
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


{{< blocks/products/pf/agp/feature-section-col title="Steps to Add Watermark to PPTX via Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load PPTX file using Presentation class
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Loop through all slides
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add text using addTextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Set all the relevant options like color, fillType and more
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the document
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Java supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Add Watermark to PPTX - Java" offSpacer="" %}}

```cs

Presentation pres = new Presentation("TestPres.pptx");

for(ISlide slide:pres.getSlides()){
    IAutoShape ashp = slide.getShapes()
                    .addAutoShape(ShapeType.Rectangle,50, 50, 500, 500);
    ashp.addTextFrame("Watermark Text");

    ashp.getTextFrame().getParagraphs().get_Item(0).getPortions()
                        .get_Item(0).getPortionFormat().getFillFormat()
                        .setFillType(FillType.Solid);
    ashp.getTextFrame().getParagraphs().get_Item(0).getPortions()
                        .get_Item(0).getPortionFormat().getFillFormat()
                        .getSolidFillColor().setColor(Color.GRAY);
    ashp.getTextFrame().getParagraphs().get_Item(0).getPortions()
                        .get_Item(0).getPortionFormat().setFontHeight(25);

    // Change the line color of the rectangle to White
    ashp.getShapeStyle().getLineColor().setColor(Color.WHITE);
    ashp.getShapeStyle().setLineStyleIndex(LineStyle.ThinThin);

    // Remove any fill formatting in the shape
    ashp.getFillFormat().setFillType(FillType.NoFill);

    ashp.setRotation(-45);

    ashp.getAutoShapeLock().setSelectLocked(true);
    ashp.getAutoShapeLock().setSizeLocked(true);
    ashp.getAutoShapeLock().setTextLocked(true);
    ashp.getAutoShapeLock().setPositionLocked(true);
    ashp.getAutoShapeLock().setGroupingLocked(true);
}
  
pres.save(path + "SavedWatermark.pptx", SaveFormat.Pptx);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Slides for Java API" %}}

 Aspose.Slides API can be used to read, write, manipulate and convert Microsoft PowerPoint documents to PDF, XPS, HTML, TIFF, ODP and various other formats. One can create new files from scratch and save those in the relevant supported formats. Aspose.Slides is a standalone API for creating, parsing or manipulating presentations, slides and elements and it does not depend on any software like Microsoft or OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Watermark PPTX via Online App" sectionDescription="Add watermark to PPTX documents by visiting our [Live Demos website](https://products.aspose.app/slides/watermark). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPTX file, set your watermark and hit \"Add\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Watermarking Formats" subTitle="Using Java, one can easily watermark different formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/watermark/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}