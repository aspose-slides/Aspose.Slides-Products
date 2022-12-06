---
title: Fusionner SVG en PNG en C++
url: /fr/cpp/merger/svg-to-png/
keywords: Fusionner SVG vers PNG, SVG vers PNG, Joindre SVG vers PNG, Combiner SVG vers PNG, API C++, Bibliothèque C++
description: Fusionnez SVG en PNG en C++. Utilisez l'API de la bibliothèque C++ pour combiner des fichiers SVG et PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Fusionner SVG en PNG en C++" h2="Bibliothèque C++ haute vitesse et multiplateforme pour fusionner des images SVG vers PNG à l'aide de code C++" >}}

{{% blocks/products/pf/feature-page-section h2="Fusionner SVG en PNG en utilisant Aspose.Slides" %}}

[**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/) est une puissante bibliothèque C++ utilisée pour fusionner et manipuler des présentations, des images et d'autres fichiers. Lorsque vous fusionnez SVG en PNG, vous combinez effectivement des images SVG pour obtenir une image PNG.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Fusionner SVG en PNG en C++" %}}
En utilisant [**Aspose.Slides pour C++**](https://products.aspose.com/slides/fr/cpp/), vous pouvez rapidement fusionner des fichiers SVG en PNG avec seulement quelques lignes de code

{{% blocks/products/pf/agp/code-block title="Code C++ pour fusionner SVG en PNG" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();
String svgContent = IO::File::ReadAllText(svgPath);
	SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(svgContent);
	SharedPtr<IPPImage> ppImage = pres->get_Images()->AddImage(svgImage);
	pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, static_cast<float>(ppImage->get_Width()), static_cast<float>(ppImage->get_Height()), ppImage);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.png", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Png());
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Comment fusionner SVG en PNG en C++" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installez **Aspose.Slides pour C++**. Voir [**Installation**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez la bibliothèque comme référence dans votre projet.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Créez une instance de la classe Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chargez les fichiers SVG que vous souhaitez fusionner.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez l'image PNG résultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="Fusionner d'autres fichiers" subTitle="Vous pouvez également combiner des fichiers dans d'autres formats pour obtenir un seul fichier" >}}
  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/cpp/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}