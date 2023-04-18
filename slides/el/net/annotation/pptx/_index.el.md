---
title: Καταργήστε τον σχολιασμό PPTX χρησιμοποιώντας .NET
weight: 4380
url: /el/net/annotation/pptx/ 
description: Πηγαίος κώδικας C# για διαγραφή σχολιασμών μορφής PPTX σε πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Κατάργηση σχολίων και συντακτών σχολίων από το PPTX σε C#" h2="Δημιουργήστε τις δικές σας εφαρμογές .NET για να χειρίζεστε σχόλια και συντάκτες σε αρχεία εγγράφων χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Κατάργηση σχολίων από το PPTX μέσω C#" %}}
Για να καταργήσουμε τους σχολιασμούς από το αρχείο PPTX, θα χρησιμοποιήσουμε το [Aspose.Slides for .NET](https://products.aspose.com/slides/el/net) API που είναι πλούσιο σε χαρακτηριστικά, ισχυρό και εύκολο στη χρήση API χειρισμού εγγράφων για πλατφόρμα C#.
{{% blocks/products/pf/agp/code-block title="Διαγραφή σχολιασμών από PPTX - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.pptx"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Πώς να αφαιρέσετε σχόλια από το PPTX μέσω C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το **Aspose.Slides για .NET**. Δείτε [**Εγκατάσταση**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φορτώστε το PPTX με μια παρουσία της κλάσης Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Επανάληψη σε όλους τους Συντάκτες του φορτωμένου PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κατάργηση όλων των σχολίων ενός συγγραφέα
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κατάργηση όλων των Συντακτών στο τέλος
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές σχολιασμού" subTitle="Χρησιμοποιώντας C#, μπορεί κανείς εύκολα να σχολιάσει άλλες μορφές, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}