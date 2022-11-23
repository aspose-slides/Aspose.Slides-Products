---
title: Convertir Image en JPG en C++
url: /fr/cpp/conversion/image-to-jpg/
keywords: Image en JPG, Convertir Image en JPG, API C++, Bibliothèque C++, Image, JPG
description: Convertissez Image en JPG en C++. Utilisez l'API de la bibliothèque C++ pour convertir les fichiers Image en JPGs
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir Image en JPG en C++" h2="Bibliothèque C++ haute vitesse et multiplateforme qui aide au développement d'applications avec la possibilité de créer, fusionner, inspecter ou convertir des fichiers de présentation Microsoft PowerPoint et OpenOffice sans utiliser de logiciel comme Microsoft ou Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Convertir Image en JPG en C++" %}}

[**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/) est une puissante bibliothèque C++ pour créer et manipuler des fichiers de présentation. De plus, il fournit des moyens flexibles pour convertir Image en JPG. En utilisant **Aspose.Slides pour C++**, n'importe quel développeur ou application peut convertir des fichiers Image en fichiers JPG avec seulement quelques lignes de code C++.

En tant qu'API de traitement de documents moderne, Aspose.Slides pour C++ exporte rapidement les fichiers Image vers les formats de fichier JPG. La bibliothèque Aspose PowerPoint vous permet de convertir Image en JPGs et de nombreux autres formats de fichiers

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir Image en JPG en utilisant C++" %}}
Pour convertir le Image en JPG, vous devrez créer une présentation à partir du fichier Image et l'enregistrer sous le nom JPG.

{{% blocks/products/pf/agp/code-block title="Code C++ pour convertir Image en JPG" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
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
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".jpg");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Jpeg());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Comment convertir Image en JPG en utilisant Aspose.Slides pour l'API C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Voici les étapes pour convertir Image en JPG en C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installez [**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez une référence de bibliothèque (importez la bibliothèque) à votre projet C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ouvrez les fichiers source Image en C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le résultat en tant que fichier JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Convertir Image vers d'autres formats pris en charge" subTitle="Vous pouvez également convertir Image et enregistrer dans d'autres formats de fichiers. Voir tous les formats pris en charge ci-dessous" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}