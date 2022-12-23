---
title: Modifica PPT in C#
url: /it/net/editor/ppt/
keywords: Modifica PPT, modifica PowerPoint, PPT, PowerPoint, API C#, libreria .NET
description: Modifica PPT in C#. Usa l'API della libreria .NET per modificare la presentazione di PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Modifica PPT in C#" h2="Potente API .NET multipiattaforma per la modifica di PPT utilizzando il codice C# su piattaforme NET Framework, .NET Core, Windows Azure, Mono o Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Modifica PPT utilizzando Aspose.Slides" %}}

[**Aspose.Slides per .NET**](https://products.aspose.com/slides/it/net/) è una potente libreria .NET utilizzata per manipolare e modificare le presentazioni. Puoi modificare una presentazione PPT aggiungendovi una nuova riga di testo. 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Modifica PPT in C#" %}}
Utilizzando [**Aspose.Slides per .NET**](https://products.aspose.com/slides/it/net/), puoi aggiungere una nuova riga di testo a un documento PPT con poche righe di codice.

{{% blocks/products/pf/agp/code-block title="Codice C# per modificare PPT" offSpacer="true" %}}
```cs
using (Presentation presentation = new Presentation("pres.ppt"))
{
    AutoShape shape = (AutoShape)presentation.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";
    presentation.Save("pres.ppt", SaveFormat.Ppt);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Come modificare PPT in C#" >}}


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
Carica la presentazione PPT che desideri modificare.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Aggiungi una nuova riga di testo.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salva il file PowerPoint modificato.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Modifica altri file" subTitle="Puoi anche modificare i file in altri formati" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/it/net/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}