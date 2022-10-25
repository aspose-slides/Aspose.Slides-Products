---
title: Συγχώνευση PDF, PPT, PPTX και πολλών άλλων μορφών αρχείων χρησιμοποιώντας C#
url: /el/net/merger/
keywords: Συγχώνευση, Συμμετοχή, PowerPoint, Παρουσίαση, C#, .NET, Aspose
description: Συγχώνευση πολλαπλών αρχείων σε C# PPT, PPTX, ODP, PDF, PNG, JPG και πολλά άλλα.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Συγχώνευση Powerpoint, PDF, PPT ή άλλων εγγράφων μαζί σε C#" h2="Βιβλιοθήκη C# υψηλής ταχύτητας για συγχώνευση PPT, PPTX, PDF, PNG, JPEG και άλλες μορφές." >}}

{{% blocks/products/pf/feature-page-section h2="Συγχώνευση PPT, PPTX, PDF χρησιμοποιώντας C#" %}}

Το [**Aspose.Slides for .NET**](https://products.aspose.com/slides/el/net/) είναι μια ισχυρή βιβλιοθήκη C# για τη δημιουργία και το χειρισμό αρχείων παρουσίασης. Επιπλέον, παρέχει ευέλικτους τρόπους συνδυασμού πολλαπλών παρουσιάσεων PPT/PPTX. Όταν συγχωνεύετε μια παρουσίαση με μια άλλη, συνδυάζετε αποτελεσματικά τις διαφάνειές τους σε μια παρουσίαση για να αποκτήσετε ένα αρχείο. Το Aspose.Slides σάς επιτρέπει να συγχωνεύσετε δύο παρουσιάσεις με διαφορετικούς τρόπους. Μπορείτε να συγχωνεύσετε παρουσιάσεις με όλα τα σχήματα, στυλ, κείμενα, μορφοποίηση, σχόλια, κινούμενα σχέδια κ.λπ. χωρίς να χρειάζεται να ανησυχείτε για απώλεια ποιότητας ή δεδομένων.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Συγχώνευση παρουσιάσεων PowerPoint σε C#" %}}
Για να συγχωνεύσετε τις παρουσιάσεις του PowerPoint, θα χρειαστεί να κλωνοποιήσετε τις διαφάνειες από τη μία παρουσίαση στην άλλη.

{{% blocks/products/pf/agp/code-block title="Συγχώνευση αρχείων PPTX χρησιμοποιώντας C#" offSpacer="true" %}}

```csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        foreach (ISlide slide in presentation2.Slides)
        {
            // Merge slides from source to target 
            presentation1.Slides.AddClone(slide);
        }
    }
    // Save the presentation
    presentation1.Save("merged-presentation.pptx", Export.SaveFormat.Pptx);
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Συγχώνευση παρουσιάσεων με το Slide Master χρησιμοποιώντας C#" %}}
Αυτός ο κώδικας C# δείχνει πώς συγχωνεύονται πολλές παρουσιάσεις σε μία και εφαρμόζονται στυλ από το πρότυπο παρουσίασης κύριας διαφάνειας. Έτσι, η παρουσίαση αποτελεσμάτων θα διατηρήσει την ίδια μορφοποίηση πηγής και θα περιέχει μορφοποίηση από την κύρια διαφάνεια μιας άλλης παρουσίασης.

{{% blocks/products/pf/agp/code-block title="Συγχώνευση πολλαπλών PPT σε ένα σε C#" offSpacer="true" %}}

``` csharp

// Instantiate a Presentation object that represents a target presentation file
using (Presentation presentation1 = new Presentation("presentation1.pptx"))
{
    // Instantiate a Presentation object that represents a source presentation file
    using (Presentation presentation2 = new Presentation("presentation2.pptx"))
    {
        // Merge first two slides only using slide master
        presentation1.Slides.AddClone(presentation2.Slides[0], presentation1.Masters[0], true);
        presentation1.Slides.AddClone(presentation2.Slides[1], presentation1.Masters[0], true);
    }
    presentation1.Save("merged-presentation-master.pptx", Export.SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος συγχώνευσης Παρουσιάσεων χρησιμοποιώντας το Aspose.Slides για .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για τη συγχώνευση δύο αρχείων PPTX και την αποθήκευση του αποτελέσματος ως PDF στο .NET." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Εγκαταστήστε το [**Aspose.Slides για .NET**](https://docs.aspose.com/slides/net/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Προσθέστε μια αναφορά βιβλιοθήκης (εισάγετε τη βιβλιοθήκη) στο έργο σας C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ανοίξτε τα αρχεία προέλευσης PPTX σε C#.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Συνδυάστε αρχεία PPTX χρησιμοποιώντας τη μέθοδο **AddClone**.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθηκεύστε την παρουσίαση και λάβετε αποτέλεσμα ως μεμονωμένο αρχείο PDF.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές για συγχώνευση" subTitle="Μπορείτε επίσης να συνδυάσετε άλλες μορφές αρχείων. Δείτε άλλες υποστηριζόμενες μορφές παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}