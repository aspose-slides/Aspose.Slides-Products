---
title: قم بإزالة PPT Annotation عبر Java
weight: 3630
url: /ar/java/annotation/ppt/ 
description: نموذج كود Java لحذف التعليقات التوضيحية بتنسيق PPT على Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="إزالة التعليقات ومؤلفو التعليقات من PPT عبر Java" h2="قم ببناء تطبيقات Java الخاصة بك للتعامل مع التعليقات والمؤلفين في ملفات المستندات باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="كيفية شرح ملف PPT باستخدام Java" %}}

 من أجل التعليق على ملف PPT ، سنستخدم
 [Aspose.Slides for Java](https://products.aspose.com/slides/ar/java)
 API وهي واجهة برمجة تطبيقات للتعليقات التوضيحية غنية بالميزات وقوية وسهلة الاستخدام لمنصة Java. يمكنك تنزيل أحدث إصدار مباشرة من
 [مافن](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 وقم بتثبيته ضمن مشروعك المستند إلى Maven عن طريق إضافة التكوينات التالية إلى ملف pom.xml.

{{% blocks/products/pf/agp/code-block title="مخزن" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="الاعتماد" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="خطوات إزالة التعليقات من PPT عبر Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. قم بإنشاء مثيل لفئة العرض التقديمي
1. أضف جميع المؤلفين والتعليقات ذات الصلة
1. احفظه بتنسيق PPT
1. إزالة التعليق في مكان محدد
1. احفظ ملف PPT مرة أخرى وقارن

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Java يدعم جميع المنصات وأنظمة التشغيل الرئيسية. يرجى التأكد من توفر المتطلبات التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.
- احصل على أحدث إصدار من Aspose.Slides for Java مباشرة من Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="حذف التعليقات التوضيحية من PPT - Java" offSpacer="" %}}

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

    {{% blocks/products/pf/agp/content h2="حول Aspose.Slides for Java API" %}}

 يمكن استخدام Aspose.Slides API لقراءة وكتابة ومعالجة وتحويل مستندات Microsoft PowerPoint إلى PDF و XPS و HTML و TIFF و ODP وتنسيقات أخرى متنوعة. يمكن للمرء إنشاء ملفات جديدة من البداية وحفظ تلك في التنسيقات المدعومة ذات الصلة. Aspose.Slides هي واجهة برمجة تطبيقات مستقلة لإنشاء العروض التقديمية والشرائح والعناصر أو تحليلها أو معالجتها ، ولا تعتمد على أي برنامج مثل Microsoft أو OpenOffice.  



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

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات التعليقات التوضيحية الأخرى المعتمدة" subTitle="باستخدام Java ، يمكن للمرء بسهولة التعليق على التنسيقات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/annotation/odp/" name="ODP" description="تنسيق العرض التقديمي OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ar/java/annotation/pptx/" name="PPTX" description="افتح تنسيق عرض XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}