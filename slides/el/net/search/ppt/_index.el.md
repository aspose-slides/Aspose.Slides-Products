---
title: Αναζήτηση κειμένου σε PPT Αρχεία παρουσίασης χρησιμοποιώντας .NET
url: /el/net/search/ppt/
keywords: αναζήτηση λέξεων σε PPT, αναζήτηση και αντικατάσταση κειμένου σε PPT, κείμενο αναζήτησης PPT Παρουσίαση
description: Πηγαίος κώδικας C# για αναζήτηση κειμένου στην παρουσίαση PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Αναζήτηση κειμένου PPT χρησιμοποιώντας C#" h2="Δημιουργήστε τις δικές σας εφαρμογές .NET για αναζήτηση και αντικατάσταση κειμένου σε αρχεία παρουσίασης χρησιμοποιώντας API από την πλευρά του διακομιστή. Μάθετε πώς να βρίσκετε όλες τις εισόδους μιας συγκεκριμένης λέξης ή φράσης σε έγγραφα παρουσίασης. Αναζήτηση κειμένου με ακριβή αντιστοίχιση δεδομένων και αντιστοίχιση τυπικών εκφράσεων." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Αναζήτηση και αντικατάσταση κειμένου PPT Παρουσίαση μέσω C#" %}}
Μια βασική αναζήτηση εγγράφων και αντικατάσταση κειμένου σε περιεχόμενα, σχόλια, σημειώσεις διαφανειών ή μεταδεδομένα με API του Aspose.Slides for .NET μπορεί να γίνει με λίγες μόνο γραμμές κώδικα. Χρησιμοποιήστε αντιστοίχιση τυπικών εκφράσεων, αντιστοίχιση πεζών-κεφαλαίων για αναζήτηση κειμένου στην παρουσίαση. Αναζήτηση κειμένου σε τίτλους, περιεχόμενο, υποσέλιδο ή κεφαλίδα.
{{% blocks/products/pf/agp/code-block title="Κείμενο αναζήτησης PPT Παρουσίαση με χρήση C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.ppt"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος αναζήτησης κειμένου σε PPT μέσω C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την αναζήτηση αρχείων κειμένου PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του PPT με μια παρουσία παρουσίασης.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Χρησιμοποιήστε τη μέθοδο [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) για να βρείτε και να αντικαταστήσετε κείμενο.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Αποθήκευση αποτελέσματος σε μορφή PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Διαδικτυακή αναζήτηση σε ζωντανές επιδείξεις PPT" sectionDescription="Αναζητήστε και αντικαταστήστε κείμενο σε περιεχόμενα, σχόλια ή μεταδεδομένα σε έγγραφα PPT αυτήν τη στιγμή." >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές αναζήτησης" subTitle="Χρησιμοποιώντας το C#, μπορείτε επίσης να αναζητήσετε κείμενο στις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}