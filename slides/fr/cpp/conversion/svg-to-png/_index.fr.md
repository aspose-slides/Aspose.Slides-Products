---
title: Convertir SVG en PNG en C++
url: /fr/cpp/conversion/svg-to-png/
keywords: SVG en PNG, Convertir SVG en PNG, API C++, Bibliothèque C++, SVG, PNG
description: Convertissez SVG en PNG en C++. Utilisez l'API de la bibliothèque C++ pour convertir les fichiers SVG en PNGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir SVG en PNG en C++" h2="Bibliothèque C++ haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir SVG en PNG en C++" %}}

[**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/) est une puissante bibliothèque C++ pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir SVG en PNG. En utilisant **Aspose.Slides pour C++**, n'importe quel développeur ou application peut convertir des fichiers SVG en fichiers PNG avec seulement quelques lignes de code C++.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour C++ exporte rapidement les fichiers SVG vers les formats de fichier PNG. La bibliothèque Aspose PowerPoint vous permet de convertir SVG en PNGs et de nombreux autres formats de fichiers

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir SVG en PNG en utilisant C++" %}}
Pour convertir le SVG en PNG, vous devrez créer une présentation à partir du fichier SVG et l'enregistrer sous le nom PNG.

{{% blocks/products/pf/agp/code-block title="Code C++ pour convertir SVG en PNG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
System::String svgContent = System::IO::File::ReadAllText(svgPath);
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(svgContent);
System::SharedPtr<IPPImage> ppImage = pres->get_Images()->AddImage(svgImage);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(Aspose::Slides::ShapeType::Rectangle, 0.0f, 0.0f, 
    static_cast<float>(ppImage->get_Width()), 
    static_cast<float>(ppImage->get_Height()), ppImage);
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment convertir SVG en PNG en utilisant Aspose.Slides pour l'API C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir SVG en PNG en C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers source SVG en C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le résultat en tant que fichier PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir SVG vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir SVG et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}