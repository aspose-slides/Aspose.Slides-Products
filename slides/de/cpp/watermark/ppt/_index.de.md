---
title: Wasserzeichen zu PPT-Präsentationsdateien mit C++ hinzufügen
url: /de/cpp/watermark/ppt/
keywords: Wasserzeichen hinzufügen PPT, Textwasserzeichen hinzufügen PPT, Bildwasserzeichen hinzufügen PPT
description: C++-Quellcode zum Hinzufügen eines Wasserzeichens zur PPT-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Wasserzeichen zur PPT-Präsentation mit C++ hinzufügen" h2="Erstellen Sie Ihre eigenen C++-Apps, um mithilfe serverseitiger APIs Text- oder Bildwasserzeichen in PPT-, PPTX- oder ODP-Präsentationen einzufügen." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Wasserzeichen zur PPT-Präsentation über C++ hinzufügen" %}}
Mit Aspose.Slides for C++ können Sie der Präsentation von PPT ein Wasserzeichen hinzufügen. Wasserzeichen sind ein wesentlicher Bestandteil jeder Präsentation. Sie dienen dazu, den Inhalt der Präsentation vor der Vervielfältigung oder unerlaubten Verwendung zu schützen. Ein Wasserzeichen ist ein sichtbares oder unsichtbares Bild oder Text, das über der Präsentation platziert wird. Es kann verwendet werden, um den Eigentümer der Präsentation zu identifizieren und eine unbefugte Nutzung zu verhindern. Wasserzeichen können auch verwendet werden, um der Präsentation eine professionelle Note zu verleihen und sie eleganter aussehen zu lassen. 
{{% blocks/products/pf/agp/code-block title="Textwasserzeichen zu PPT mit C++ hinzufügen" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Bildwasserzeichen zur PPT-Präsentation mit C++ hinzufügen" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto image = presentation->get_Images()->AddImage(:File::ReadAllBytes(u"watermark.png"));

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(image);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"watermark2.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So fügen Sie über C++ ein Wasserzeichen zu PPT hinzu" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Hinzufügen von Textwasserzeichen zu PPT-Dateien." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPT mit einer Präsentationsinstanz
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Wählen Sie die Masterpräsentation aus
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie einen Formtyp mit der AddAutoShape-Methode hinzu
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Wasserzeichentext mit der AddTextFrame-Methode hinzu
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format PPT speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Formate" subTitle="Mit C++ können Sie Wasserzeichen auch zu den folgenden Formaten hinzufügen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/cpp/watermark/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}