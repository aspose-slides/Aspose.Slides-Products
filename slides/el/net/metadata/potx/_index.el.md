---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Προβολή ή επεξεργασία μεταδεδομένων αρχείων POTX με .NET
url: /el/net/metadata/potx/
description: Πηγαίος κώδικας C# για προβολή ή επεξεργασία μεταδεδομένων POTX.
keywords: επεξεργασία μεταδεδομένων POTX, προβολή μεταδεδομένων POTX, επεξεργασία ιδιοτήτων POTX, προβολή ιδιοτήτων POTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Επεξεργασία ιδιοτήτων POTX με C#" h2="Δημιουργήστε εφαρμογές .NET που διαβάζουν και τροποποιούν ενσωματωμένες και προσαρμοσμένες ιδιότητες παρουσιάσεων με API διακομιστή." related="FODP,ODP,OTP,POT,POTM,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Τροποποίηση ιδιοτήτων POTX με C#" variant="code" %}}

Με το [Aspose.Slides for .NET](/slides/el/net/) οι προγραμματιστές μπορούν να διαβάζουν και να τροποποιούν ενσωματωμένες και προσαρμοσμένες ιδιότητες παρουσιάσεων. Χρησιμοποιήστε την ιδιότητα [`DocumentProperties`](https://reference.aspose.com/slides/net/aspose.slides/documentproperties/) ενός αντικειμένου `Presentation` για να διαβάσετε και να ενημερώσετε μεταδεδομένα POTX.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Τροποποίηση ενσωματωμένων ιδιοτήτων POTX – C#" >}}
```cs
using var presentation = new Presentation("presentation.potx");
var documentProperties = presentation.DocumentProperties;

documentProperties.Author = "Aspose.Slides for .NET";
documentProperties.Title = "Modifying Presentation Properties";
documentProperties.Subject = "Aspose Subject";
documentProperties.Comments = "Aspose Description";
documentProperties.Manager = "Aspose Manager";

presentation.Save("DocumentProperties_out.potx", SaveFormat.Potx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Προσθήκη προσαρμοσμένων ιδιοτήτων σε POTX – C#" >}}
```cs
using var presentation = new Presentation();
var documentProperties = presentation.DocumentProperties;

documentProperties["New Custom"] = 12;
documentProperties["My Name"] = "Aspose Metadata Editor";
documentProperties["Custom"] = 124;

var propertyName = documentProperties.GetCustomPropertyName(2);
documentProperties.RemoveCustomProperty(propertyName);

presentation.Save("CustomDocumentProperties_out.potx", SaveFormat.Potx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να προβάλετε ή να επεξεργαστείτε μεταδεδομένα POTX σε C#" intro="Ακολουθήστε αυτά τα βήματα για να προβάλετε ή να επεξεργαστείτε μεταδεδομένα POTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο POTX με την `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Λάβετε το αντικείμενο `DocumentProperties` της παρουσίασης.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαβάστε ή ενημερώστε ενσωματωμένες ιδιότητες όπως `Author`, `Title` και `Subject`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Διαβάστε και τροποποιήστε προσαρμοσμένες ιδιότητες με την `DocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Δημιουργήθηκε με το Aspose.Slides" title="Προβολή και επεξεργασία μεταδεδομένων POTX online" description="Η δωρεάν εφαρμογή Aspose.Slides Metadata έχει δημιουργηθεί με το [Aspose.Slides for .NET](https://products.aspose.com/slides/el/net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία POTX." button="Άνοιγμα Aspose.Slides Metadata" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς διαβάζει και γράφει ιδιότητες το Aspose.Slides πριν γράψετε κώδικα.
- Προβάλετε και επεξεργαστείτε ενσωματωμένες και προσαρμοσμένες ιδιότητες του αρχείου POTX.
- Αποθηκεύστε και κατεβάστε το ενημερωμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές μεταδεδομένων" subTitle="Με C# μπορείτε επίσης να διαχειριστείτε τα μεταδεδομένα των παρακάτω μορφών." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
