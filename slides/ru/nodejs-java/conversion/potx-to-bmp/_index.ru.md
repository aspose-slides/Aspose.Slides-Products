---
title: Преобразование POTX в BMP в Node.js
url: /ru/nodejs-java/conversion/potx-to-bmp/
keywords: POTX в BMP, конвертировать POTX в BMP, API Node.js, библиотека Node.js, POTX, BMP
description: Преобразуйте POTX в BMP в Node.js. Используйте API библиотеки Node.js для преобразования файлов POTX в BMP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Преобразование POTX в BMP в Node.js" h2="Aspose.Slides for Node.js через Java — это мощная и простая в использовании библиотека, которая позволяет конвертировать презентации PowerPoint в различные форматы в Node.js. Он поддерживает все элементы и форматы презентаций и предоставляет богатый API для доступа к ним и их изменения. Он также позволяет экспортировать слайды в различные форматы для дальнейшей обработки или обмена." >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование POTX в BMP в Node.js" %}}

[**Aspose.Slides для Node.js через Java**](https://products.aspose.com/slides/ru/nodejs-java/) — мощная библиотека Node.js для создания файлов презентаций и управления ими. Более того, он предоставляет гибкие способы преобразования POTX в BMP. Используя **Aspose.Slides for Node.js через Java**, любой разработчик или приложение может конвертировать файлы POTX в BMP с помощью всего лишь нескольких строк кода.

В качестве современного API обработки документов Aspose.Slides для Node.js быстро экспортирует файлы POTX в форматы файлов BMP. Библиотека Aspose PowerPoint позволяет конвертировать файлы POTX в BMP и многие другие форматы файлов.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование POTX в BMP с помощью Node.js" %}}
Чтобы преобразовать POTX в BMP, вам нужно будет создать презентацию из файла POTX и сохранить ее как BMP.

{{% blocks/products/pf/agp/code-block title="Код Node.js для преобразования POTX в BMP" offSpacer="true" %}}

```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation("welcome-to-powerpoint.potx");
try
{
    for(var i = 0; i < pres.getSlides().size(); i++)
    {
        var sld = pres.getSlides().get_Item(i);
        var bi = sld.getThumbnail(2, 2);
        var outputfile = java.newInstanceSync("java.io.File", "slide_" + sld.getSlideNumber() + ".bmp");
        java.callStaticMethod("javax.imageio.ImageIO", "write", bi, "bmp", outputfile);
    }
}
finally
{
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как преобразовать POTX в BMP с помощью Aspose.Slides для Node.js через Java API" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Чтобы преобразовать POTX в BMP с помощью Aspose.Slides для Node.js через Java, вам необходимо импортировать пакет в файл JavaScript и создать экземпляр класса Presentation. Класс Presentation представляет документ PowerPoint и предоставляет методы для доступа к его элементам и управления ими." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Установите [**Aspose.Slides для Node.js через Java**](https://products.aspose.com/slides/ru/nodejs-java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Откройте исходные файлы POTX в Node.js.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат как файл BMP.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Преобразование POTX в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать POTX и сохранять в другие форматы файлов. Все поддерживаемые форматы см. ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-pptx/" name="POTX TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-ppt/" name="POTX TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-pdf/" name="POTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-html/" name="POTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-png/" name="POTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-jpg/" name="POTX TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-fodp/" name="POTX TO FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-gif/" name="POTX TO GIF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-odp/" name="POTX TO ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-otp/" name="POTX TO OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-pot/" name="POTX TO POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-potm/" name="POTX TO POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-pps/" name="POTX TO PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-ppsm/" name="POTX TO PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-ppsx/" name="POTX TO PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-pptm/" name="POTX TO PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-svg/" name="POTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/nodejs-java/conversion/potx-to-tiff/" name="POTX TO TIFF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}