---
title: Μετατροπή παρουσίασης Microsoft PowerPoint σε πολλαπλά αρχεία με χρήση Java
url: /el/java/conversion/
description: Μετατρέψτε τις διαφάνειες Microsoft PowerPoint σε διαφορετικά αρχεία, συμπεριλαμβανομένων μορφών HTML, PDF και εικόνας εντός εφαρμογών που βασίζονται σε Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή παρουσίασης Microsoft<sup>®</sup> PowerPoint μέσω Java" h2="Πηγαίοι κώδικες Java για διάφορα σενάρια μετατροπής για μετατροπή διαφανειών σε εικόνες, HTML, PDF και άλλες μορφές." >}}

{{% blocks/products/pf/feature-page-summary %}}

Η βιβλιοθήκη Java PowerPoint έχει κάνει τη μετατροπή των Παρουσιάσεων του Microsoft<sup>®</sup> PowerPoint απλές και εύκολες στην αυτοματοποίηση των διαδικασιών. Οι προγραμματιστές μπορούν να επιλέξουν το σχετικό σενάριο και να ενσωματώσουν τον κώδικα για να βελτιώσουν τη λειτουργικότητα της εφαρμογής. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Διαμετατροπή αρχείων Microsoft PowerPoint" %}}
Η αλληλομετατροπή αρχείων Microsoft<sup>®</sup> PowerPoint μέσω προγραμματισμού είναι απλώς ένας κώδικας δύο γραμμών. Φορτώστε το αρχείο χρησιμοποιώντας το [Presentation class](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) και καλέστε τη μέθοδο αποθήκευσης με το αρχείο εξόδου και [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) ως παραμέτρους.

{{% blocks/products/pf/feature-page-code h3="Κώδικας μετατροπής Java" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PowerPoint σε PDF" %}}

Η μετατροπή PowerPoint σε PDF είναι μια συνηθισμένη περίπτωση λόγω της τεράστιας κοινής χρήσης αρχείων PDF. Αντί για μη αυτόματες μετατροπές, οι προγραμματιστές μπορούν να το αυτοματοποιήσουν και να εξοικονομήσουν χρόνο για μια σειρά από παρουσιάσεις PowerPoint σε PDF. Η βιβλιοθήκη παρουσίασης παρέχει [κατηγορία PdfOptions](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) για την προσαρμογή συγκεκριμένων ρυθμίσεων όπως ορισμός επιπέδου συμπίεσης κειμένου, επίπεδο συμμόρφωσης PDF, ποιότητα JPEG, καθορισμός της συμπεριφοράς μετα-αρχείων, μετατροπή κρυφών διαφανειών, επιλογή επιλεγμένων διαφανειών και δημιουργία αρχείων PDF με κλειδωμένο κωδικό πρόσβασης.

{{% blocks/products/pf/feature-page-code h3="Κώδικας μετατροπής Java PowerPoint σε PDF" %}}

```cs
// Load file
Presentation powerpointopdf = new Presentation("srcFile.pptx");

// Create PdfOptions class object
PdfOptions slidetopdfOpt = new PdfOptions();
               
// Set JPEG Quality
slidetopdfOpt.setJpegQuality((byte) 90);

// Define behavior for Metafiles
slidetopdfOpt.setSaveMetafilesAsPng(true);

// Set Text Compression level
slidetopdfOpt.setTextCompression(PdfTextCompression.Flate);

// Define the PDF standard
slidetopdfOpt.setCompliance(PdfCompliance.Pdf15);
              
INotesCommentsLayoutingOptions options = slidetopdfOpt.getNotesCommentsLayouting();
options.setNotesPosition(NotesPositions.BottomFull);

// Specify that the generated document should include hidden slides
slidetopdfOpt.setShowHiddenSlides(true);
	
// Setting PDF password
slidetopdfOpt.setPassword("password");	

// Save the presentation to PDF with specified options
powerpointopdf.save("java-powerpoint-to.pdf", SaveFormat.Pdf, slidetopdfOpt);


// Setting array of slides positions
// int[] slides = new int[] { 2, 3, 5 };

// Save the presentation to PDF
// powerpointopdf.save("java-powerpoint-to.pdf", slides, SaveFormat.Pdf);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Μετατροπή Microsoft PowerPoint σε HTML" %}}

Καθώς οι διαφάνειες του PowerPoint δεν εμφανίζονται απευθείας σε ιστοσελίδες, επομένως υπάρχει ανάγκη μετατροπής. Οι προγραμματιστές μπορούν να φορτώσουν το αρχείο χρησιμοποιώντας την κλάση Presentation, να χρησιμοποιήσουν το [HtmlOptions class](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) για συγκεκριμένες ρυθμίσεις HTML και να επικαλέσουν τη μέθοδο αποθήκευσης.

{{% blocks/products/pf/feature-page-code h3="Κώδικας Java για Μετατροπή PowerPoint σε HTML" %}}

```cs

// Load the file
Presentation powerpointohtml = new Presentation("srcFile.pptx");

// Create HTML options
HtmlOptions pptxhtmlOpt = new HtmlOptions();

// Displaying hidden slides
pptxhtmlOpt.setShowHiddenSlides(true);

// Save the PPTX as HTML
powerpointohtml.save("java-powerpoint-to.html", SaveFormat.Html, pptxhtmlOpt); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή Microsoft PowerPoint σε εικόνες" %}}
Η μετατροπή μορφών Microsoft<sup>®</sup> PowerPoint σε εικόνες JPG, TIFF, PNG κ.λπ. είναι συνήθως για τη δημιουργία μικρογραφιών διαφανειών καθώς και για πολύ περισσότερες θήκες. Η διαδικασία κωδικοποίησης είναι απλή. Επαναλάβετε σε κάθε διαφάνεια μέσω της [διεπαφής ISlide](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) μετά τη φόρτωση του εγγράφου, μεταφέρετε τη μικρογραφία ISlide ISlide.getThumbnail(1f, 1f) [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) και στη συνέχεια αποθηκεύστε την στην απαιτούμενη μορφή εικόνας. 

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint σε κώδικα μετατροπής εικόνας" %}}
```cs
// Load the PowerPoint document
Presentation PowerPointtoImage = new Presentation("templatefile.pptx");


// for generating a full scale image
// BufferedImage bi = sld.getThumbnail(1f, 1f);

// for Customized dimensions, define dimensions
int finalX = 1200;
int finalY = 800;

// Get scaled values of X and Y
float DimensionX = (float)(1.0 / PowerPointtoImage.getSlideSize().getSize().getWidth()) * finalX;
float DimensionY = (float)(1.0 / PowerPointtoImage.getSlideSize().getSize().getHeight()) * finalY;

// Loop through each slide in the presentation
for (ISlide sld : PowerPointtoImage.getSlides()) {
	
// Create a full scale image
BufferedImage bi = sld.getThumbnail(DimensionX, DimensionY);

// Create a new file
File outputfile = new File(sld.getSlideNumber() + "_Slide.jpg");
	
// Save the image to disk in JPEG format
ImageIO.write(bi, "jpg", outputfile);
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}