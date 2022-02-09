---
title: Microsoft PowerPoint Presentation Conversion to PDF in Python 
url: /python-net/conversion/
keywords: "Convert, PowerPoint, Presentation, Python, PDF, Convert to PDF, PPT to PDF"
description: Python API to Convert PPT to PDF. Convert Presentations to JPG, PNG and other formats in Python. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> PowerPoint Presentation to PDF Conversion in Python" h2="Python Source Codes for different conversion cases to convert PPT to PDF, PNG, HTML, JPEG, PPTX and other formats." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Slides for Python via .NET](https://products.aspose.com/words/python-net/) is a powerful on-premise class library used for processing and working with presentations. It is easy for the developers to convert PowerPoint to PDF with speed and accuracy. Get the results within no time for automating the business processes. We are discussing here few cases to read or load any input [supported PowerPoint formats](https://docs.aspose.com/slides/python-net/supported-file-formats/) and write or save to any supported output format. 

{{% /blocks/products/pf/feature-page-summary  %}}

<div class="col-lg-12">
    <h2 class="h2title">Python PowerPoint to PDF Conversion</h2>
    <p><a href="https://products.aspose.com/words/python-net/">Aspose.Slides</a> allows you to convert files in PowerPoint PPT, PPTX, and OpenOffice ODP formats to PDF. To convert a presentation to PDF, simply pass the file name and save format to the <a href="https://docs.aspose.com/slides/python-net/api-reference/aspose.slides/presentation/">Presentation.save</a> method. The <a href="https://docs.aspose.com/slides/python-net/api-reference/aspose.slides/presentation/">Presentation</a> class exposes the <a href="https://docs.aspose.com/slides/python-net/api-reference/aspose.slides/presentation/">save</a> method that can be called to convert the whole PPT, PPTX, or ODP presentation into a PDF document.</p>
    <pre>
        <code class="python">
import aspose.slides as slides

with slides.Presentation("PowerPoint.ppt") as presentation:
    presentation.save("PPT-to-PDF.pdf", slides.export.SaveFormat.PDF) 
        </code>
    </pre>
</div>
  
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf potm-to-pdf potx-to-pdf ppsm-to-pdf odp-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF to PPT Conversion in Python" %}}
[Aspose.Slides](https://products.aspose.com/words/python-net/) allows you to import presentations from PDFs. Essentially, you get to convert a PDF to a PowerPoint presentation. To convert PDF to Powerpoint, Go through these steps:
- Instantiate an object of the [Presentation](https://docs.aspose.com/slides/python-net/api-reference/aspose.slides/presentation/) class.
- Call the [add_from_pdf](https://docs.aspose.com/slides/python-net/api-reference/aspose.slides/slidecollection/) method and pass the PDF file.
- Use the [save](https://docs.aspose.com/slides/python-net/api-reference/aspose.slides/presentation/) method to save the file in the PowerPoint format.

{{% blocks/products/pf/feature-page-code h3="Python PDF to Powerpoint Conversion" %}}

{{% blocks/products/pf/agp/code-block title="Python PDF to Powerpoint Conversion" offSpacer="" %}}

```py
import aspose.slides as slides

with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("welcome-to-powerpoint.pdf")
    presentation.save("OutputPresentation.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-ppt pdf-to-pptx pdf-to-odp pdf-to-png pdf-to-jpg pdf-to-html" >}}


{{% blocks/products/pf/feature-page-section  h2="Convert PPT to PDF with custom options in Python" %}}

For converting PowerPoint slides to PDF accurately, Programmers can load the document using `Presentation` class and use [PdfOptions class](https://docs.aspose.com/slides/python-net/api-reference/aspose.slides.export/pdfoptions/) for all specific and custom options like text compression level, Jpeg quality, the behavior of metafiles, converting hidden slides as well as selecting specific slides and more. Even there is option to protect the converted PDF file with password.

{{% blocks/products/pf/agp/code-block title="Python PowerPoint to PDF Conversion with custom settings" offSpacer="" %}}

```py
import aspose.slides as slides

# Instantiate a Presentation object that represents a PPTX file
with slides.Presentation("PowerPoint.pptx") as presentation:

    # Instantiate the PdfOptions class
    pdfOptions = slides.export.PdfOptions()

    # Set Jpeg quality
    pdfOptions.jpeg_quality = 90

    # Set behavior for metafiles
    pdfOptions.save_metafiles_as_png = True

    # Set text compression level
    pdfOptions.text_compression = slides.export.PdfTextCompression.FLATE

    # Define the PDF standard
    pdfOptions.compliance = slides.export.PdfCompliance.PDF15

    # Save the presentation as PDF
    presentation.save("PowerPoint-to-PDF.pdf", slides.export.SaveFormat.PDF, pdfOptions)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Mircrosoft PowerPoint to HTML Conversion in Python" %}}
When ever there is need to embed presentations within webpages, then there is need to convert slides to HTML.

{{% blocks/products/pf/feature-page-code h3="Python Code for PowerPoint to HTML Conversion" %}}
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/agp/code-block offSpacer="" %}}

```py
import aspose.slides as slides

# Instantiate a Presentation object that represents a PPTX file
with slides.Presentation("PowerPoint.pptx") as presentation:
    # Save the PPTX as HTML
    presentation.Save("presentation-to.html", slides.export.SaveFormat.HTML5)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint to JPG" %}}
Converting Microsoft<sup>&reg;</sup> PowerPoint formats to images JPEG, PNG, TIFF etc is another commom use case mostly used for creating slides thumbnails. 
{{% blocks/products/pf/feature-page-code h3="Python PPT to JPG Converter Code" %}}

```py
import aspose.slides as slides
import aspose.pydrawing as drawing

# Instantiate a Presentation object that represents a PPTX file
with slides.Presentation("PowerPoint.pptx") as presentation:
    for slide in presentation.slides:
        bmp = slide.get_thumbnail(2, 2)
        bmp.save("Slide_{num}.jpg".format(num=str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)    
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-jpg pptx-to-jpg ppt-to-png pptx-to-png ppt-to-gif pptx-to-gif" >}}