---
title: Unisci TIFF a PDF in C#
url: /it/net/merger/tiff-to-pdf/
keywords: Da TIFF a PDF, Unisci TIFF a PDF, Unisci TIFF a PDF, PDF, TIFF, API C#, Libreria .NET
description: Unisci TIFF a PDF in C#. Utilizza l'API della libreria .NET per combinare TIFF e PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Unisci TIFF a PDF in C#" h2="Potente API .NET multipiattaforma per l'unione di file TIFF in PDF utilizzando il codice C# su piattaforme NET Framework, .NET Core, Windows Azure, Mono o Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Unisci TIFF in PDF utilizzando Aspose.Slides" %}}

[**Aspose.Slides per .NET**](https://products.aspose.com/slides/it/net/) è una potente libreria .NET utilizzata per creare, convertire, unire e manipolare presentazioni, PDF, immagini, e altri file. Quando unisci TIFF a PDF, combini effettivamente le immagini per ottenere un singolo file PDF.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Unisci TIFF a PDF in C#" %}}
Usando [**Aspose.Slides per .NET**](https://products.aspose.com/slides/it/net/), puoi unire rapidamente TIFF a PDF con poche righe di codice

{{% blocks/products/pf/agp/code-block title="Codice C# per unire TIFF in PDF" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage tiff1 = pres.Images.AddImage(File.ReadAllBytes("image1.tiff"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, tiff1);

    IPPImage tiff2 = pres.Images.AddImage(File.ReadAllBytes("image2.tiff"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, tiff2);

    pres.Save("MergedFile.pdf", SaveFormat.Pdf);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Come unire TIFF in PDF in C#" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installa **Aspose.Slides per .NET**. Vedere [**Installazione**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi la libreria come riferimento nel tuo progetto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crea un'istanza della classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carica i file TIFF che vuoi unire come cornici.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il PDF risultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Unisci altri file" subTitle="Puoi anche combinare file in altri formati per ottenere un unico file" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/png-to-pdf/" name="PNG TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}