---
title: تحرير أو عرض البيانات الوصفية لملفات OTP عبر Java
weight: 4920
url: /ar/java/metadata/otp/ 
description: نموذج كود Java لتحرير أو عرض البيانات الوصفية بتنسيق OTP في Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="استخراج OTP Metadata عبر Java" h2="قم ببناء تطبيقات Java الخاصة بك لإضافة أو تحرير أو إزالة أو استخراج البيانات الوصفية من ملفات OTP باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="OTP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="كيفية استخراج بيانات OTP الوصفية باستخدام Java" %}}

 من أجل الحصول على البيانات الوصفية لملف OTP ، سنستخدمها
 [Aspose.Slides for Java](https://products.aspose.com/slides/java)
 API وهي واجهة برمجة تطبيقات للبيانات الوصفية غنية بالميزات وقوية وسهلة الاستخدام لمنصة Java. يمكنك تنزيل أحدث إصدار مباشرة من
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


{{< blocks/products/pf/agp/feature-section-col title="خطوات استخراج البيانات الوصفية لمرة واحدة عبر جافا" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="تمثل فئة IDocumentProperties خصائص المستند المرتبطة بملف العرض التقديمي. يمكن للمطورين استخدام هذه الخاصية للوصول إلى البيانات الوصفية كما هو موضح أدناه." >}}

{{< blocks/products/pf/agp/step-autogen >}}
الحصول على معلومات OTP باستخدام getPresentationInfo ()
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
اقرأ جميع الخصائص
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
قم بتعيين الخصائص الجديدة
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
تحديث وكتابة معلومات OTP مع الخصائص الجديدة
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Java يدعم جميع المنصات وأنظمة التشغيل الرئيسية. يرجى التأكد من توفر المتطلبات التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.
- احصل على أحدث إصدار من Aspose.Slides for Java مباشرة من
 [مافن](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="استخراج البيانات الوصفية من OTP - Java" offSpacer="" %}}

```cs

// read the info of presentation
IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("presentation.otp");

// obtain the current properties
IDocumentProperties props = info.readDocumentProperties();

// set the new values of Author and Title fields
props.setAuthor("New Author");
props.setTitle("New Title");

// update the presentation with a new values
info.updateDocumentProperties(props);
info.writeBindedPresentation("presentation.otp");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Slides for Java API" %}}

 يمكن استخدام Aspose.Slides API لقراءة وكتابة ومعالجة وتحويل مستندات Microsoft PowerPoint إلى PDF و XPS و HTML و TIFF و ODP وتنسيقات أخرى متنوعة. يمكن للمرء إنشاء ملفات جديدة من البداية وحفظ تلك في التنسيقات المدعومة ذات الصلة. Aspose.Slides هي واجهة برمجة تطبيقات مستقلة لإنشاء العروض التقديمية والشرائح والعناصر أو تحليلها أو معالجتها ، ولا تعتمد على أي برنامج مثل Microsoft أو OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of OTP via Online App" sectionDescription="View & edit Metadata to OTP documents by using our [Live Demos](https://products.aspose.app/slides/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your OTP file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" >}}
Files with .OTP extension represent presentation template files created by applications in OASIS OpenDocument standard format. The contents of such a file include presentation information in the form of slides with text, images, shapes, multimedia content, transition effects and other slide elements. These template files are used for creating new presentations quickly based on the styling information stored in the template itself. OTP files can be created and saved with several different applications such as Impress that comes with OpenOffice suite and Microsoft PowerPoint. The OTP file format is similar to Microsoft PowerPoint template files .POT and .POTX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات البيانات الوصفية المدعومة الأخرى" subTitle="باستخدام Java ، يمكن للمرء أيضًا معالجة البيانات الوصفية للعديد من التنسيقات الأخرى بما في ذلك" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/odp/" name="ODP" description="تنسيق العرض التقديمي OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/pot/" name="POT" description="ملفات قوالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/potm/" name="POTM" description="ملف قالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/potx/" name="POTX" description="عرض تقديمي لقالب Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/pps/" name="PPS" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/ppsm/" name="PPSM" description="عرض شرائح ممكّن بماكرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/ppsx/" name="PPSX" description="عرض شرائح PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/ppt/" name="PPT" description="مايكروسوفت باور بوينت 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/pptm/" name="PPTM" description="ملف العرض التقديمي الممكّن بماكرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/metadata/pptx/" name="PPTX" description="افتح تنسيق عرض XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}