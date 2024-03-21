---
title: Node.js via .NET PowerPoint API by Aspose.Slides
weight: 5890
url: /nodejs-net/ 
description: Aspose.Slides for Node.js via .NET is a Node.js PowerPoint API that lets you create, modify, and convert PowerPoint presentations in Node.js. 
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="Node.js PowerPoint API for Presentations" h2="Create, Read, Modify and Convert PowerPoint and OpenOffice presentations using Node.js without any external software." logoImageSrc="https://products.aspose.com/slides/images/aspose_slides-for-nodejs-via-java-header.svg" pfName="Aspose.Slides" subTitlepfName="for Node.js via .NET" downloadUrl="https://releases.aspose.com/slides/nodejs-net/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides" subTitlepfName="for Node.js via .NET" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://products.aspose.com/slides/images/aspose_slides-for-nodejs-via-net.svg" liveDemosLink="https://products.aspose.app/slides/family/" PricingLink="https://purchase.aspose.com/pricing/slides/nodejs-net/" buyLink="https://purchase.aspose.com/buy" docsLink="https://docs.aspose.com/slides/nodejs-net/" installationsDocsLink="https://docs.aspose.com/slides/nodejs-net/installation/" nugetLink="https://www.nuget.org/packages/Aspose.Slides.NET6.CrossPlatform" nugetPackageName="Aspose.Slides.NET6.CrossPlatform" mavenRepoLink=""  directDownloadLink="https://releases.aspose.com/slides/nodejs-net/" >}}

<p><strong>Aspose.Slides for Node.js via .NET</strong> is a Node.js library that lets you create, modify, and convert PowerPoint presentations in Node.js. It supports all presentation elements such as slides, shapes, text, charts, tables, images, and more. It also offers many advanced features such as merging, cloning, splitting, comparing, and printing presentations. It works without any dependencies and can process thousands of presentations in a short time.</p>

<p><strong>Aspose.Slides for Node.js via .NET</strong> provides these popular features:</p>
<ul>
    <li>Loading, opening, and viewing presentations.</li>
    <li>Editing presentations.</li>
    <li>Converting presentation files to popular presentation formats, such as PPT, PPTX, and ODP.</li>
    <li>Exporting presentations to PDF, JPG, HTML, GIF, SVG, and many other formats.</li>
    <li>Rendering and printing presentations.</li>
    <li>Encrypting and decrypting presentations; password-protecting presentations and removing passwords.</li>
    <li>Manipulating presentation entities, such as master slides, shapes, charts, picture frames, audio frames, video frames, OLE, VBA macros, animations, etc.</li>
    <li>And many more features.</li>
</ul>

<p>Node.js is a popular, free, open-source and cross-platform JavaScript runtime environmentthat lets developers write command line tools and server-side scripts outside of a browser. For this reason, the <strong>Aspose.Slides</strong> team is proud to offer <strong>Aspose.Slides for Node.js via .NET</strong> to the Node.js community.</p>

<!--Feature-section Start-->
<div class="container-fluid features-section bg-gray singleproduct">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">Advanced Node.js PowerPoint API Features</h2>
   <p>
   </p>
   <div class="col-lg-4">
    <em class="fa fa-copy ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Create or clone existing slides from templates</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-table ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Work with PowerPoint tables via API</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-shield ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Apply or remove the protection on shapes</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-bar-chart ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Add Excel charts as OleObjects to slides</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-image ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Create shapes and add text to shapes on slides
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-align-left ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Handle text &amp; shape formatting
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-database ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Generate presentations from database</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-lock ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Protect presentations &amp; resultant PDF</p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-print ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">Print presentations on a physical printer</p>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">System Requirements</h2>
    <ul>
      <li>Aspose.Slides for Node.js via .NET is server-side JavaScript API based on Node.js. It can run on Windows, Unix/Linux & Mac platforms with .NET6 or above.</li>
    </ul>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">How to Install</h2>
    <p>Use <strong>NPM</strong> to install our Node.js library for Presentation processing from the <a href="https://www.npmjs.com/package/aspose.slides.via.net">NPM Package repository:</a></p>
    <pre><code>npm install aspose.slides.via.net</code></pre>
   </div>
    <div class="col-lg-12">
        <h2 class="h2title">How to Create New PowerPoint Presentation in Node.js</h2>
        <p>In the example given below, we have added a rectangle to the first slide of the presentation.</p>
        <pre>
            <code class="JavaScript">	
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat, ShapeType } = asposeSlides;

var pres = new Presentation();
try 
{
    var slide = pres.slides.get(0);
    slide.shapes.addAutoShape(ShapeType.Rectangle, 50, 150, 300, 200);
    
    pres.save("pres.pptx", SaveFormat.Pptx);
}
finally
{
    if (pres != null) pres.dispose();
}
            </code>
        </pre>
    </div>
    
    <div class="col-lg-12">
        <h2 class="h2title">How to Add/Remove/Clone Slides and Edit Shape Properties in Node.js</h2>
        <p>This Node.js code shows you how to edit various properties and clone slides:</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, BackgroundType, FillType, ImageFormat } = asposeSlides;

var pres = new Presentation();
try 
{
    // Add an empty slide to the presentation
    pres.slides.addEmptySlide(pres.layoutSlides.get(0));
    
    // Create another presentation and add its clone into the pres
    var pres2 = new Presentation();
    pres.slides.addClone(pres2.slides.get(0));
    
    // Access and modify properties of the first slide in pres
    var slide = pres.slides.get(0); // Get the first slide
    var slideNumber = slide.slideNumber; // Get slide number
    var hidden = slide.hidden; // Check if the slide is hidden
	
    // Set the background of the first slide
    slide.background.type = BackgroundType.OwnBackground; // Set background type
    slide.background.fillFormat.fillType = FillType.Solid; // Set fill type to solid
    slide.background.fillFormat.solidFillColor.color = "#AEC025F4"; // Set a solid fill color
}
finally
{
    if (pres != null) pres.dispose();
}
            </code>
        </pre>
    </div>

    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to PDF in Node.js</h2>
        <p>This Node.js code shows you how to convert a PowerPoint to a PDF document</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat } = asposeSlides;

var pres = new Presentation("pres.pptx");
try 
{
    pres.save("pres.pdf", SaveFormat.Pdf);
}
finally
{
    if (pres != null) pres.dispose();
}
            </code>
        </pre>
    </div>

    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to GIF in Node.js</h2>
        <p>This Node.js code shows you how to convert a PowerPoint to a GIF image</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat } = asposeSlides;

var pres = new Presentation("pres.pptx");
try 
{
    pres.save("pres.gif", SaveFormat.Gif);
}
finally
{
    if (pres != null) pres.dispose();
}
            </code>
        </pre>
    </div>

    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to HTML in Node.js</h2>
        <p>This Node.js code shows you how to convert a PowerPoint to a HTML document</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat } = asposeSlides;

var pres = new Presentation("pres.pptx");
try 
{
    pres.save("pres.html", SaveFormat.Html);
}
finally
{
    if (pres != null) pres.dispose();
}
            </code>
        </pre>
    </div>    
    
    <div class="col-lg-12">
        <h2 class="h2title">How to Convert PowerPoint to ODP in Node.js</h2>
        <p>This Node.js code shows you how to convert a PowerPoint to a ODP document</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat } = asposeSlides;

var pres = new Presentation("pres.pptx");
try 
{
    pres.save("pres.odp", SaveFormat.Odp);
}
finally
{
    if (pres != null) pres.dispose();
}
            </code>
        </pre>
    </div>   

    <div class="col-lg-12">
        <h2 class="h2title">How to Merge Presentations in Node.js</h2>
        <p>This Node.js code shows you how to merge presentations:</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation, SaveFormat } = asposeSlides;

var pres1 = new Presentation("pres1.pptx");
var pres2 = new Presentation("pres2.pptx");
try 
{
    for (var i = 0; i < pres2.slides.length; i++) 
    {
        pres1.slides.addClone(pres2.slides.get(i));
    }
    
    pres1.save("combinedPresentation.pptx", SaveFormat.Pptx);
}
finally
{
    if (pres1 != null) pres1.dispose();
    if (pres2 != null) pres2.dispose();
}
            </code>
        </pre>
    </div>       

    <div class="col-lg-12">
        <h2 class="h2title">How to Retrieve Various Properties of a PowerPoint Presentation </h2>
        <p>The following example shows you how to retrieve various properties of a PowerPoint presentation .</p>
        <pre>
            <code class="JavaScript">
const asposeSlides = require('aspose.slides.via.net');

const { Presentation } = asposeSlides;

var pres = new Presentation("pres.pptx");
try 
{
    // Retrieve various properties of the presentation
    var countSlides = pres.slides.count; // Total number of slides
    var countMastersSlides = pres.masters.count; // Total number of master slides
    var countLayoutSlides = pres.layoutSlides.count; // Total number of layout slides
    var firstSlideNumber = pres.firstSlideNumber; // Number of the first slide
    var lastView = pres.viewProperties.lastView; // Last view type of the presentation
    var masterThemeName = pres.masterTheme.name; // Name of the master theme
    var sourceFormat = pres.sourceFormat; // Format of the source presentation
    var countVideos = pres.videos.count; // Total number of videos in the presentation
    var countImages = pres.images.count; // Total number of images in the presentation
    
    // Retrieve objects for further manipulation or information extraction
    var slideObject = pres.slides.get(0); // Object of the first slide
    var mastersSlideObject = pres.masters.get(0); // Object of the first master slide
    
    // Log the total number of slides to the console
    console.log("countSlides:" + countSlides);    
    console.log("countMastersSlides:" + countMastersSlides);    
    console.log("countLayoutSlides:" + countLayoutSlides);    
    console.log("firstSlideNumber:" + firstSlideNumber);    
    console.log("lastView=" + lastView);    
    console.log("masterThemeName:" + masterThemeName);    
    console.log("sourceFormat:" + sourceFormat);    
    console.log("countVideos:" + countVideos);    
    console.log("countImages:" + countImages);    
}
finally
{
    if (pres != null) pres.dispose();
}
            </code>
        </pre>
    </div>
  </div>
 </div>
</div>
<!--Feature-section End-->

{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/support-learning-resources >}}
    {{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
        {{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/slides/nodejs-net/" >}}
        {{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-slides/" >}}
        {{< blocks/products/pf/slr-element name="API References" href="https://docs.aspose.com/slides/nodejs-net/api-reference/" >}}
        {{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
    {{< /blocks/products/pf/slr-tab >}}

    {{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
        {{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/slides" >}}
        {{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
        {{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/slides/" >}}
        {{< blocks/products/pf/slr-element name="Release Notes" href="https://docs.aspose.com/slides/nodejs-net/release-notes/" >}}
    {{< /blocks/products/pf/slr-tab >}}

    {{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Slides for Node.js via .NET?" tabId="success-stories" >}}
        {{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
        {{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/aspose-slides" >}}
    {{< /blocks/products/pf/slr-tab >}}
{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://releases.aspose.com/slides/nodejs-net" pricingInformationLink="https://purchase.aspose.com/pricing/slides/nodejs-net" >}}

{{< blocks/products/pf/offers-section pfName="Aspose.Slides" description="Aspose.Slides offers individual PowerPoint APIs for other popular development environments as listed below:" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/net/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sdkName=".NET" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/java/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sdkName="Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/cpp/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sdkName="C++" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/android-java/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-android-java.svg" sdkName="Android via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/nodejs-java/" imgSrc="https://products.aspose.com/slides/images/aspose_slides-for-nodejs-via-java.svg" sdkName="Node.js via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/php-java/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-php-via-java.svg" sdkName="PHP via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/python-net/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sdkName="Python via .NET" >}}    
    {{< blocks/products/pf/offers-section-item link="/slides/sharepoint/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-sharepoint.svg" sdkName="SharePoint" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/reporting-services/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-reporting-services.svg" sdkName="Reporting Services" >}}
    {{< blocks/products/pf/offers-section-item link="/slides/jasperreports/" imgSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-jasperreports.svg" sdkName="JasperReports" >}}

{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

