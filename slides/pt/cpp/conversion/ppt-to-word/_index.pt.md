---
title: Converter PPT para Word em C++
url: /pt/cpp/conversion/ppt-to-word/
keywords: Converter PPT para Word, PPT para Word, PPT para DOC, PowerPoint para Word, API C++, Biblioteca C++, CPP
description: Converter PPT para Word em C++. Use a API da biblioteca C++ para converter PowerPoint em Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Converter PPT para Word em C++" h2="Poderosa API C++ de plataforma cruzada para converter PowerPoint em Word usando código C++ sem Microsoft PowerPoint ou Office" >}}

{{% blocks/products/pf/feature-page-section h2="Converter PowerPoint para Word usando Aspose.Slides e Aspose.Words" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/pt/cpp/) e [**Aspose.Words for C++**](https://products.aspose.com/ words/cpp/) são poderosas bibliotecas C++ usadas para manipular e converter apresentações do PowerPoint, documentos do Word e outros arquivos. Ao converter PowerPoint para Word, você está basicamente movendo o conteúdo dos slides de uma apresentação para páginas em um documento do Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Converter PowerPoint para Word em C++" %}}
Você pode converter PPT para Word rapidamente com apenas algumas linhas de código

{{% blocks/products/pf/agp/code-block title="Código C++ para converter PowerPoint para Word" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="Como converter PPT para Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para C++** e **Aspose.Words para C++** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Crie uma instância da classe Presentation e da classe Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregue a apresentação PPT que deseja converter para o Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gere imagens e textos com base no conteúdo dos slides.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Salve o documento do Word resultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Conversor Online Gratuito" sectionDescription="[Como converter PPT para HTML em Python](https://products.aspose.com/slides/pt/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter PowerPoint para arquivos em outros formatos" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}