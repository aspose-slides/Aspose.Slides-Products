---
title: PPT-annotatie verwijderen via Java
weight: 3630
url: /nl/java/annotation/ppt/ 
description: Java-voorbeeldcode voor het verwijderen van annotaties in PPT-indeling in Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Verwijder opmerkingen en commentaarauteurs van PPT via Java" h2="Bouw uw eigen Java-apps om opmerkingen en auteurs in documentbestanden te manipuleren met behulp van server-side API's." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Hoe een PPT-bestand annoteren met Java" %}}

 Om het PPT-bestand te annoteren, gebruiken we
 [Aspose.Slides voor Java](https://products.aspose.com/slides/nl/java)
 API, een veelzijdige, krachtige en gebruiksvriendelijke annotatie-API voor het Java-platform. U kunt de nieuwste versie rechtstreeks downloaden van
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 en installeer het binnen uw op Maven gebaseerde project door de volgende configuraties toe te voegen aan pom.xml.

{{% blocks/products/pf/agp/code-block title="Opslagplaats" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Afhankelijkheid" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Stappen om opmerkingen van PPT te verwijderen via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Maak een instantie van de klasse Presentatie
1. Voeg alle relevante auteurs en opmerkingen toe
1. Sla het op in PPT-formaat
1. Reactie op specifieke locatie verwijderen
1. Sla PPT-bestand opnieuw op en vergelijk

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides voor Java ondersteunt alle belangrijke platforms en besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met Java Runtime Environment voor JSP/JSF-applicaties en desktopapplicaties.
- Download de nieuwste versie van Aspose.Slides voor Java rechtstreeks van Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Annotaties verwijderen uit PPT - Java" offSpacer="" %}}

```cs
Presentation pres = new Presentation();
try{
// Add comment
ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());

// Add reply for comment1
ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
reply1.setParentComment(comment1);

// Add reply for comment1
IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0),  new Point2D.Float(10, 10), new Date());
reply2.setParentComment(comment1);

// Add reply to reply
IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0),  new Point2D.Float(10, 10), new Date());
subReply.setParentComment(reply2);

IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());

IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
reply3.setParentComment(comment3);

// Display hierarchy on console
ISlide slide = pres.getSlides().get_Item(0);
IComment[] comments = slide.getSlideComments(null);
for (int i = 0; i < comments.length; i++){

IComment comment = comments[i];
while (comment.getParentComment() != null){
        System.out.print("\t");
        comment = comment.getParentComment();
}

System.out.println(comments[i].getAuthor().getName() +  " : " + comments[i].getText());
                System.out.println();
}
pres.save(dataDir + "parent_comment.pptx",SaveFormat.Pptx);
// Remove comment1 and all its replies
comment1.remove();
            
pres.save(dataDir + "remove_comment.pptx",SaveFormat.Pptx);
}finally {
 pres.dispose();
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Over Aspose.Slides voor Java API" %}}

 Aspose.Slides API kan worden gebruikt om Microsoft PowerPoint-documenten te lezen, schrijven, manipuleren en converteren naar PDF, XPS, HTML, TIFF, ODP en verschillende andere formaten. Men kan vanaf het begin nieuwe bestanden maken en deze opslaan in de relevante ondersteunde formaten. Aspose.Slides is een zelfstandige API voor het maken, parseren of manipuleren van presentaties, dia's en elementen en is niet afhankelijk van software zoals Microsoft of OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Remove Annotation from PPT via Online App" sectionDescription="Delete PPT document annotations right now by visiting our [Live Demos website](https://products.aspose.app/slides/annotation). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPT file and hit the \"Remove\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde annotatie-indelingen" subTitle="Met behulp van Java kan men gemakkelijk andere formaten annoteren, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/annotation/odp/" name="ODP" description="OpenDocument-presentatie-indeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/java/annotation/pptx/" name="PPTX" description="Open XML-presentatie-indeling" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}