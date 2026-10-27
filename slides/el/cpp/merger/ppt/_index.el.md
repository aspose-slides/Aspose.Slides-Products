---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Συγχώνευση αρχείων PPT μέσω C++
weight: 4840
url: /el/cpp/merger/ppt/ 
description: Παράδειγμα κώδικα C++ για συνδυασμό εγγράφων PPT σε περιβάλλον χρόνου εκτέλεσης C++ για Windows 32 bit, Windows 64 bit και Linux 64 bit.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Συγχώνευση αρχείων PPT χρησιμοποιώντας C++" h2="Συγχώνευση εγγράφων PPT με χρήση API C++ από την πλευρά του διακομιστή."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Πώς να συγχωνεύσετε αρχείο PPT χρησιμοποιώντας C++" %}}

Για να συγχωνεύσουμε το αρχείο PPT, θα χρησιμοποιήσουμε
 [Aspose.Slides για C++](https://products.aspose.com/slides/el/cpp/)
 API που είναι ένα πλούσιο σε χαρακτηριστικά, ισχυρό και εύχρηστο API συγχώνευσης εγγράφων για πλατφόρμα C++. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας, απλά ανοίξτε
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 διαχειριστής πακέτων, αναζητήστε
 **Aspose.Slides.Cpp**
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Εντολή" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Συγχώνευση αρχείων PPT - C++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.ppt";
const String sourceFilePath2 = u"SourceFile3.ppt";
const String outputFilePath = u"mergedOutput.ppt";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Ppt);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Βήματα για τη συγχώνευση αρχείων PPT σε C++" intro="Ένα βασικό έγγραφο που συγχωνεύεται και συνδέεται με τα API [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/) μπορεί να γίνει με λίγες μόνο γραμμές κώδικα." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Φορτώστε και τα δύο αρχεία PPT.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε τη μέθοδο get\_Slides() για επανάληψη σε κάθε διαφάνεια.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε τη λειτουργία AddClone για συγχώνευση με το επιθυμητό αρχείο.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Χρησιμοποιήστε τη μέθοδο Save() για αποθήκευση σε καθορισμένη διαδρομή{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Απαιτήσεις συστήματος" intro="Το Aspose.Slides for C++ υποστηρίζει όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις." %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με C++ Runtime Environment για Windows 32 bit, Windows 64 bit και Linux 64 bit.
- Aspose.Slides για C++ DLL που αναφέρονται στο έργο σας.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Δημιουργήθηκε με το Aspose.Slides" title="Συγχώνευση αρχείων PPT online" description="Η δωρεάν εφαρμογή Aspose.Slides Merger έχει δημιουργηθεί με το [Aspose.Slides for C++](https://products.aspose.com/slides/el/cpp/), το ίδιο API με τον παραπάνω κώδικα. Ανοίξτε την και δείτε τι μπορεί να κάνει το API με τα δικά σας αρχεία PPT." button="Άνοιγμα Aspose.Slides Merger" note="[Όλες οι δωρεάν εφαρμογές](https://products.aspose.app/slides/family)" >}}
- Λειτουργεί στο πρόγραμμα περιήγησής σας, χωρίς εγκατάσταση.
- Δείτε πώς το Aspose.Slides συγχωνεύει αρχεία πριν γράψετε κώδικα.
- Ανεβάστε πολλά αρχεία PPT και συνδυάστε τα σε ένα.
- Κατεβάστε το συγχωνευμένο αποτέλεσμα ως ένα αρχείο.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

Ένα αρχείο με επέκταση .ppt είναι παρουσίαση PowerPoint που περιέχει μια συλλογή διαφανειών για προβολή. Χρησιμοποιεί τη δυαδική μορφή αρχείων που υποστηρίζει το Microsoft PowerPoint 97–2003. Ένα αρχείο PPT μπορεί να περιέχει διάφορους τύπους περιεχομένου, όπως κείμενο, λίστες με κουκκίδες, εικόνες, πολυμέσα και άλλα ενσωματωμένα αντικείμενα OLE. Από το PowerPoint 2007 και μετά, η Microsoft εισήγαγε τη νεότερη μορφή PPTX, που βασίζεται στο Office Open XML αντί για αυτή τη δυαδική μορφή. Αρχεία PPT μπορούν να δημιουργήσουν και άλλες εφαρμογές, όπως το OpenOffice Impress και το Apple Keynote.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Άλλες υποστηριζόμενες μορφές συγχώνευσης" subTitle="Χρησιμοποιώντας τη C++, το One μπορεί επίσης να συγχωνεύσει πολλές άλλες μορφές αρχείων, όπως.." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/merger/odp/" name="ODP" description="Μορφή παρουσίασης OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/merger/otp/" name="OTP" description="Τυπική μορφή OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/merger/pot/" name="POT" description="Αρχεία προτύπων Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/merger/potm/" name="POTM" description="Αρχείο προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/merger/potx/" name="POTX" description="Παρουσίαση προτύπου Microsoft PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/merger/pps/" name="PPS" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/merger/ppsm/" name="PPSM" description="Παρουσίαση με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/merger/ppsx/" name="PPSX" description="Παρουσίαση PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/merger/pptm/" name="PPTM" description="Αρχείο παρουσίασης με δυνατότητα μακροεντολής" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/el/cpp/merger/pptx/" name="PPTX" description="Ανοίξτε τη μορφή παρουσίασης XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
