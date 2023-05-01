---
title: Εξαγωγή κειμένου και εικόνων από αρχεία ODP χρησιμοποιώντας Python
url: /el/python-net/parser/odp/
keywords: αναλύστε ODP χρησιμοποιώντας Python, ODP parser Python, εξαγωγή δεδομένων από ODP στο Python, εξαγωγή κειμένου από ODP χρησιμοποιώντας Python, εξαγωγή εικόνων από ODP χρησιμοποιώντας Python
description: Πηγαίος κώδικας Python για ανάλυση της παρουσίασης ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Εξαγωγή κειμένου και εικόνων από την παρουσίαση ODP χρησιμοποιώντας Python" h2="Δημιουργήστε τις δικές σας εφαρμογές Python για εξαγωγή αρχείων κειμένου, εικόνας, βίντεο και ήχου από το PowerPoint χρησιμοποιώντας API από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Εξαγωγή κειμένου από την παρουσίαση ODP μέσω Python" %}}
Για να σαρώσετε το κείμενο από ολόκληρη την παρουσίαση, χρησιμοποιήστε τη στατική μέθοδο [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) που εκτίθεται από την κλάση SlideUtil. Ο παρακάτω κώδικας σαρώνει το κείμενο και τις πληροφορίες μορφοποίησης από μια παρουσίαση, συμπεριλαμβανομένων των βασικών διαφανειών.
{{% blocks/products/pf/agp/code-block title="Εξαγωγή κειμένου από την παρουσίαση ODP χρησιμοποιώντας Python" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a ODP file
with slides.Presentation("pres.odp") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the ODP
    textFramesPPTX = slides.util.SlideUtil.get_all_text_frames(pptxPresentation, True)
    
    # Loop through the Array of TextFrames
    for i in range(len(textFramesPPTX)):
	    # Loop through paragraphs in current ITextFrame
        for para in textFramesPPTX[i].paragraphs:
            # Loop through portions in the current IParagraph
            for port in para.portions:
			    # Display text in the current portion
                print(port.text)

    			# Display font height of the text
                print(port.portion_format.font_height)

			    # Display font name of the text
                if port.portion_format.latin_font != None:
                    print(port.portion_format.latin_font.font_name)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Τρόπος εξαγωγής κειμένου από το ODP μέσω του Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Αυτά είναι τα βήματα για την ανάλυση αρχείων ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Φόρτωση του ODP με μια παρουσία παρουσίασης
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Λάβετε μια σειρά αντικειμένων TextFrame από όλες τις διαφάνειες στο ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κάντε βρόχο μέσα από τη Συστοιχία TextFrames
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κάντε βρόχο μέσω των παραγράφων στο τρέχον TextFrame
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Κάντε βρόχο μέσω τμημάτων στην τρέχουσα παράγραφο
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Λάβετε κείμενο στο τρέχον τμήμα
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές ανάλυσης" subTitle="Χρησιμοποιώντας το Python, μπορείτε επίσης να σαρώσετε τις ακόλουθες μορφές:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/parser/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/el/python-net/parser/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}