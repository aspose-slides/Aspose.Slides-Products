---
title: Преобразование PPSM в BMP в JavaScript
url: /ru/nodejs-net/conversion/ppsm-to-bmp/
keywords: PPSM в BMP, преобразование PPSM в BMP, Node.js API, библиотека JavaScript, PPSM, BMP
description: Преобразуйте PPSM в BMP в JavaScript. Используйте API библиотеки Node.js для преобразования файлов PPSM в BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование PPSM в BMP в JavaScript" h2="Aspose.Slides для Node.js через .NET — это мощная и простая в использовании библиотека, позволяющая конвертировать презентации PowerPoint в различные форматы с помощью JavaScript. Он поддерживает все элементы и форматы презентаций и предоставляет богатый API для доступа к ним и их изменения. Он также позволяет экспортировать слайды в различные форматы для дальнейшей обработки или обмена." >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование PPSM в BMP в Node.js" %}}

[**Aspose.Slides для Node.js через .NET**](https://products.aspose.com/slides/ru/nodejs-net/) — мощная библиотека Node.js для создания файлов презентаций и управления ими. Более того, он предоставляет гибкие способы преобразования PPSM в BMP. Используя **Aspose.Slides для Node.js через .NET**, любой разработчик или приложение может конвертировать файлы PPSM в BMP с помощью всего лишь нескольких строк кода.

В качестве современного API обработки документов Aspose.Slides для Node.js через .NET быстро экспортирует файлы PPSM в форматы файлов BMP. Библиотека Aspose PowerPoint позволяет конвертировать файлы PPSM в BMP и многие другие форматы файлов.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование PPSM в BMP с помощью JavaScript" %}}
Чтобы преобразовать PPSM в BMP, вам нужно будет создать презентацию из файла PPSM и сохранить ее как BMP.

{{% blocks/products/pf/agp/code-block title="Код JavaScript для преобразования PPSM в BMP" offSpacer="true" %}}

```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.ppsm");
try
{
    for (let i = 0; i < pres.slides.length; i++) {
        var slide = pres.slides.get(i);
        var image = slide.getThumbnail(new asposeSlides.RenderingOptions(), { width: 1080, height: 960 });

        image.save("slide" + i + ".bmp", ImageFormat.Bmp); 
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как преобразовать PPSM в BMP с помощью Aspose.Slides для Node.js через .NET API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Чтобы преобразовать PPSM в BMP с помощью Aspose.Slides для Node.js через .NET, вам необходимо импортировать пакет в файл JavaScript и создать экземпляр класса Presentation. Класс Presentation представляет документ PowerPoint и предоставляет методы для доступа к его элементам и управления ими." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Установите [**Aspose.Slides для Node.js через .NET**](https://products.aspose.com/slides/ru/nodejs-net/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Откройте исходные файлы PPSM в Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат как файл BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Преобразование PPSM в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать PPSM и сохранять в другие форматы файлов. Все поддерживаемые форматы см. ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-html/" name="PPSM TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-png/" name="PPSM TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-jpg/" name="PPSM TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-pot/" name="PPSM TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-svg/" name="PPSM TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}