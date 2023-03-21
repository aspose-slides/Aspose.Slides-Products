---
title: Преобразование Image в JPG в C++
url: /ru/cpp/conversion/image-to-jpg/
keywords: Image в JPG, преобразовать Image в JPG, API C++, библиотеку C++, Image, JPG
description: Преобразование Image в JPG в C++. Используйте API библиотеки C++ для преобразования файлов Image в файлы JPG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование Image в JPG в C++" h2="Высокоскоростная и кроссплатформенная библиотека C++, которая помогает в разработке приложений с возможностью создания, объединения, проверки или преобразования файлов презентаций Microsoft PowerPoint и OpenOffice без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование Image в JPG в C++" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ru/cpp/) — мощная библиотека C++ для создания файлов презентаций и управления ими. Кроме того, он предоставляет гибкие способы преобразования Image в JPG. Используя **Aspose.Slides for C++**, любой разработчик или приложение может преобразовать файлы Image в JPG всего несколькими строками кода C++.

Как современный API обработки документов, Aspose.Slides для C++ быстро экспортирует файлы Image в форматы файлов JPG. Библиотека Aspose PowerPoint позволяет конвертировать Image в JPG и многие другие форматы файлов.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование Image в JPG с помощью C++" %}}
Чтобы преобразовать Image в JPG, вам нужно будет создать презентацию из файла Image и сохранить его как JPG.

{{% blocks/products/pf/agp/code-block title="Код C++ для преобразования Image в JPG" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="Как преобразовать Image в JPG с помощью Aspose.Slides for C++ API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для преобразования Image в JPG в C++." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Установите [**Aspose.Slides для C++**](https://products.aspose.com/slides/ru/cpp/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Откройте исходные файлы Image в C++.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат как файл JPG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Бесплатный онлайн-конвертер" sectionDescription="[Как преобразовать PPT в HTML в Python](https://products.aspose.com/slides/ru/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Конвертировать Image в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать Image и сохранять в файлы других форматов. См. все поддерживаемые форматы ниже" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/conversion/image-to-pdf/" name="IMAGE TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}