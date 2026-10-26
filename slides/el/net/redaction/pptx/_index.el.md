---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Απόκρυψη δεδομένων σε αρχεία παρουσιάσεων PPTX με .NET
url: /el/net/redaction/pptx/
description: Πηγαίος κώδικας C# για εύρεση και αντικατάσταση κειμένου σε παρουσιάσεις PPTX.
keywords: Απόκρυψη δεδομένων σε PPTX, εύρεση και αντικατάσταση κειμένου σε PPTX, ενημέρωση παρουσίασης PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Απόκρυψη δεδομένων σε αρχεία PPTX με C#" h2="Δημιουργήστε εφαρμογές .NET που βρίσκουν και αντικαθιστούν κείμενο σε παρουσιάσεις με API διακομιστή." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Απόκρυψη δεδομένων σε παρουσίαση PPTX με C#" variant="code" %}}

Με το [Aspose.Slides for .NET](/slides/el/net/), μπορείτε να βρείτε και να αντικαταστήσετε κείμενο σε μια παρουσίαση PPTX. Χρησιμοποιήστε το `Presentation.ReplaceText` με το `TextSearchOptions` για να ελέγξετε την αναζήτηση και, στη συνέχεια, αποθηκεύστε την τροποποιημένη παρουσίαση.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Απόκρυψη δεδομένων σε παρουσίαση PPTX με C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
var searchOptions = new TextSearchOptions { WholeWordsOnly = true };

presentation.ReplaceText("PowerPoint", "Aspose.Slides", searchOptions, null);
presentation.Save("redacted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Πώς να αποκρύψετε δεδομένα σε παρουσίαση PPTX με C#" intro="Ακολουθήστε αυτά τα βήματα για να αντικαταστήσετε κείμενο σε μια παρουσίαση PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε το αρχείο PPTX με το `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε το [`Presentation.ReplaceText`](https://reference.aspose.com/slides/net/aspose.slides/presentation/replacetext/) με το `TextSearchOptions` για να αντικαταστήσετε το απαιτούμενο κείμενο.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Αποθηκεύστε την τροποποιημένη παρουσίαση με `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Δημιουργήθηκε με το Aspose.Slides" title="Διαδικτυακή απόκρυψη δεδομένων σε αρχεία PPTX" description="Η δωρεάν εφαρμογή Aspose.Slides Redaction έχει δημιουργηθεί με το [Aspose.Slides for .NET](https://products.aspose.com/slides/el/net/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPTX." button="Άνοιγμα Aspose.Slides Redaction" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides βρίσκει και αντικαθιστά κείμενο πριν γράψετε κώδικα.
- Βρείτε και αντικαταστήστε κείμενο στο αρχείο PPTX, ακόμη και με κανονικές εκφράσεις.
- Κατεβάστε το επεξεργασμένο αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές για απόκρυψη δεδομένων" subTitle="Με C#, μπορείτε επίσης να αποκρύψετε δεδομένα στις ακόλουθες μορφές." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/el/net/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
