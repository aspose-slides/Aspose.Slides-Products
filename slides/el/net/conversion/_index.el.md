---
title: Μετατροπή παρουσίασης Microsoft PowerPoint σε πολλά αρχεία με χρήση C#
url: /el/net/conversion/
description: Μετατρέψτε τις διαφάνειες Microsoft PowerPoint σε διαφορετικά αρχεία, συμπεριλαμβανομένων των μορφών PDF, HTML και εικόνας σε πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή παρουσίασης Microsoft<sup>®</sup> PowerPoint μέσω C#" h2="Πηγαίοι κώδικες C# για διαφορετικές περιπτώσεις μετατροπής για μετατροπή αρχείων σε εικόνες, PDF, HTML και άλλες μορφές." >}}

{{% blocks/products/pf/feature-page-summary %}}

Είναι εύκολο για τους προγραμματιστές να μετατρέψουν τις Παρουσιάσεις του Microsoft<sup>®</sup> PowerPoint με ταχύτητα και ακρίβεια. Λάβετε τα αποτελέσματα σε χρόνο μηδέν για την αυτοματοποίηση των επιχειρηματικών διαδικασιών. Εδώ συζητάμε μερικές περιπτώσεις για ανάγνωση ή φόρτωση οποιασδήποτε εισόδου [υποστηριζόμενες μορφές PowerPoint](https://docs.aspose.com/slides/net/supported-file-formats/) και εγγραφή ή αποθήκευση σε οποιαδήποτε υποστηριζόμενη μορφή εξόδου. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Διαμετατροπή αρχείων Microsoft PowerPoint" %}}
Όποτε υπάρχει ανάγκη αυτοματοποίησης της αλληλομετατροπής μορφών Microsoft<sup>®</sup> PowerPoint. Η **Βιβλιοθήκη C# PowerPoint** παρέχει κλάσεις για την επίτευξη αυτού του στόχου. Φορτώστε το αρχείο χρησιμοποιώντας [Τάξη παρουσίασης](https://apireference.aspose.com/net/slides/aspose.slides/presentation) για να φορτώσετε ή να διαβάσετε την επιθυμητή μορφή και καλώντας τη [Μέθοδος αποθήκευσης](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) της ίδιας κατηγορίας, προσδιορίζοντας το αρχείο εξόδου και το [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="Κωδικός μετατροπέα C# για παρουσιάσεις Microsoft PowerPoint" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Μετατροπή C# PowerPoint σε PDF" %}}

Για τη μετατροπή των διαφανειών του PowerPoint σε PDF με ακρίβεια, οι προγραμματιστές μπορούν να φορτώσουν το έγγραφο χρησιμοποιώντας την κλάση παρουσίασης και να χρησιμοποιήσουν την [Κλάση PdfOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) για όλα τα συγκεκριμένα και προσαρμοσμένα επιλογές όπως το επίπεδο συμπίεσης κειμένου, η ποιότητα Jpeg, η συμπεριφορά των μετααρχείων, η μετατροπή κρυφών διαφανειών καθώς και η επιλογή συγκεκριμένων διαφανειών και άλλα. Ακόμη και υπάρχει η επιλογή προστασίας του αρχείου PDF που έχει μετατραπεί με κωδικό πρόσβασης.
{{% blocks/products/pf/feature-page-code h3="Κωδικός μετατροπέα C# PowerPoint σε PDF" %}}

```cs
// Load PowerPoint file
Presentation pptxtopdf = new Presentation("sourceFile.pptx");

// Create PdfOptions class object for specific settings
PdfOptions pptPDFOptions = new PdfOptions();

// Set Jpeg quality
pptPDFOptions.JpegQuality = 90;

// Set behavior for metafiles
pptPDFOptions.SaveMetafilesAsPng = true;

// Set text compression level
pptPDFOptions.TextCompression = PdfTextCompression.Flate;

// Define the PDF 15 standard
pptPDFOptions.Compliance = PdfCompliance.Pdf15;

// Include hidden slides
pptPDFOptions.ShowHiddenSlides = true;

// Setting PDF password and access permissions
pptPDFOptions.Password = "password";
pptPDFOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;

// Save the presentation as PDF
pptxtopdf.Save("csharp-PowerPoint-to.pdf", SaveFormat.Pdf, pptPDFOptions);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Μετατροπή Microsoft PowerPoint σε HTML" %}}
Όταν χρειάζεται να ενσωματωθούν παρουσιάσεις σε ιστοσελίδες, τότε χρειάζεται να μετατραπούν οι διαφάνειες σε HTML. Το API παρέχει [κατηγορία HtmlOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), Χρησιμοποιήστε το μετά τη φόρτωση των αρχείων για ειδικές ρυθμίσεις όπως κρυφές διαφάνειες, καθώς από προεπιλογή, αυτές δεν θα να συμπεριληφθούν κατά τη διαδικασία μετατροπής. Περάστε τις οριστικοποιημένες επιλογές στη μέθοδο αποθήκευσης για μετατροπή.
{{% blocks/products/pf/feature-page-code h3="Κωδικός C# για μετατροπή PowerPoint σε HTML" %}}

```cs

// Load source presentation 
Presentation powerpoiontohtml = new Presentation("sourceFile.pptx");

// Create HTML options
HtmlOptions PowerPointhtmlOpt = new HtmlOptions();

// Show hidden slides
PowerPointhtmlOpt.ShowHiddenSlides = true;

// Save the PPTX as HTML
powerpoiontohtml.Save("presentation-to.html", SaveFormat.Html, PowerPointhtmlOpt); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή διαφανειών PowerPoint σε μορφές εικόνας" %}}
Η μετατροπή μορφών Microsoft<sup>®</sup> PowerPoint σε εικόνες JPEG, PNG, TIFF κ.λπ. είναι μια άλλη συνηθισμένη περίπτωση χρήσης που χρησιμοποιείται κυρίως για τη δημιουργία μικρογραφιών διαφανειών. Η διαδικασία κωδικοποίησης είναι απλή. Μετά τη φόρτωση του εγγράφου, χρησιμοποιήστε το [ISlide interface](https://apireference.aspose.com/net/slides/aspose.slides/islide) για επανάληψη σε κάθε διαφάνεια. Κατά τη διάρκεια κάθε επανάληψης, χρησιμοποιήστε το (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] μαζί με τη μέθοδο GetThumbnail που έχει προσαρμοσμένες διαστάσεις εικόνας. Τέλος αποθηκεύστε την εικόνα στην απαιτούμενη μορφή.
{{% blocks/products/pf/feature-page-code h3="C# Κώδικας μετατροπής PowerPoint σε εικόνα" %}}
```cs
using (Presentation powerpointtoimage = new Presentation("source-file.ppt")){
foreach (ISlide sld in powerpointtoimage.Slides){

// Create a full scale image
Bitmap bmp = sld.GetThumbnail(1f, 1f);
// or use some customized dimensions as sld.GetThumbnail(x, y)

// Save the image
bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
}
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}