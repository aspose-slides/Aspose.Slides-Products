---
title: Преобразование PDF в PNG в JavaScript
url: /ru/nodejs-net/conversion/pdf-to-png/
keywords: PDF в PNG, преобразование PDF в PNG, Node.js API, библиотека JavaScript, PDF, PNG
description: Преобразуйте PDF в PNG в JavaScript. Используйте API библиотеки Node.js для преобразования файлов PDF в PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование PDF в PNG в JavaScript" h2="Aspose.Slides для Node.js через .NET — это мощная и простая в использовании библиотека, позволяющая конвертировать презентации PowerPoint в различные форматы с помощью JavaScript. Он поддерживает все элементы и форматы презентаций и предоставляет богатый API для доступа к ним и их изменения. Он также позволяет экспортировать слайды в различные форматы для дальнейшей обработки или обмена." >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование PDF в PNG в Node.js" %}}

[**Aspose.Slides для Node.js через .NET**](https://products.aspose.com/slides/ru/nodejs-net/) — мощная библиотека Node.js для создания файлов презентаций и управления ими. Более того, он предоставляет гибкие способы преобразования PDF в PNG. Используя **Aspose.Slides для Node.js через .NET**, любой разработчик или приложение может конвертировать файлы PDF в PNG с помощью всего лишь нескольких строк кода.

В качестве современного API обработки документов Aspose.Slides для Node.js через .NET быстро экспортирует файлы PDF в форматы файлов PNG. Библиотека Aspose PowerPoint позволяет конвертировать файлы PDF в PNG и многие другие форматы файлов.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование PDF в PNG с помощью JavaScript" %}}
Чтобы преобразовать PDF в PNG, вам нужно будет создать презентацию из файла PDF и сохранить ее как PNG.

{{% blocks/products/pf/agp/code-block title="Код JavaScript для преобразования PDF в PNG" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat, ShapeType } = asposeSlides;

var pres = new Presentation();
try
{
    pres.slides.removeAt(0);
    var slides = pres.slides.addFromPdf("welcome-to-powerpoint.pdf");

    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".png", ImageFormat.Png); 
    }
}
finally
{
    if (pres != null) pres.dispose();
} 

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как преобразовать PDF в PNG с помощью Aspose.Slides для Node.js через .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Чтобы преобразовать PDF в PNG с помощью Aspose.Slides для Node.js через .NET, вам необходимо импортировать пакет в файл JavaScript и создать экземпляр класса Presentation. Класс Presentation представляет документ PowerPoint и предоставляет методы для доступа к его элементам и управления ими." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Установите [**Aspose.Slides для Node.js через .NET**](https://products.aspose.com/slides/ru/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Откройте исходные файлы PDF в Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат как файл PNG.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Преобразование PDF в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать PDF и сохранять в другие форматы файлов. Все поддерживаемые форматы см. ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}