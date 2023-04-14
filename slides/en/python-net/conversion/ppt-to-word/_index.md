---
title:  Convert PPT to Word in Python
url: /python-net/conversion/ppt-to-word/
keywords: Convert PPT to Word, PPT to Word, PPT to DOC, PowerPoint to Word, Python API, Python Library
description: Convert PPT to Word in Python. Use Python library API to convert PowerPoint to Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convert PPT to Word in Python" h2="Powerful cross-platform Python API for converting PowerPoint to Word using Python code without Microsoft PowerPoint or Office" >}}

{{% blocks/products/pf/feature-page-section h2="Convert PowerPoint to Word using Aspose.Slides and Aspose.Words" %}}

[**Aspose.Slides for Python via .NET**](https://products.aspose.com/slides/python-net/) and [**Aspose.Words for Python via .NET**](https://products.aspose.com/words/python-net/) are powerful Python libraries used to manipulate and convert PowerPoint presentations, Word documents, and other files. When you convert PowerPoint to Word, you are essentially moving the contents of a presentation's slides to pages in a Word document.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Convert PowerPoint to Word in Python" %}}
You can convert PPT to Word quickly with just a few lines of code

{{% blocks/products/pf/agp/code-block title="Python code for converting PowerPoint to Word" offSpacer="true" %}}
```py
presentation = slides.Presentation("pres.ppt")
doc = words.Document()
builder = words.DocumentBuilder(doc)

for index in range(presentation.slides.length):
    slide = presentation.slides[index]
    # generates and inserts slide image
    slide.get_thumbnail(2,2).save("slide_{i}.png".format(i = index), drawing.imaging.ImageFormat.png)
    builder.insert_image("slide_{i}.png".format(i = index))
    
    for shape in slide.shapes:
        # inserts slide's texts
        if (type(shape) is slides.AutoShape):
            builder.writeln(shape.text_frame.text)
   
    builder.insert_break(words.BreakType.PAGE_BREAK)
doc.save("presentation.docx")
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="How to convert PPT to Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Install **Aspose.Slides for Python via .NET** and **Aspose.Words for Python via .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Create an instance of the Presentation class and Doc class.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Load the PPT presentation you want to convert to Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Generate images and texts based on the slides' contents.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save the resulting Word document.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Free Online Converter" sectionDescription="[How to Convert PPT to HTML in Python](https://products.aspose.com/slides/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert PowerPoint to files in other formats" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppt-to-jpg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/python-net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}