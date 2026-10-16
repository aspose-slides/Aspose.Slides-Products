---
lastmod: 2023-09-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование PDF в SVG в Node.js
url: /ru/nodejs-java/conversion/pdf-to-svg/
keywords: PDF в SVG, конвертировать PDF в SVG, API Node.js, библиотека Node.js, PDF, SVG
description: Преобразуйте PDF в SVG в Node.js. Используйте API библиотеки Node.js для преобразования файлов PDF в SVG.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование PDF в SVG в Node.js" h2="Aspose.Slides for Node.js через Java — это мощная и простая в использовании библиотека, которая позволяет конвертировать презентации PowerPoint в различные форматы в Node.js. Он поддерживает все элементы и форматы презентаций и предоставляет богатый API для доступа к ним и их изменения. Он также позволяет экспортировать слайды в различные форматы для дальнейшей обработки или обмена." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PDF в SVG с помощью Node.js" variant="code" %}}

Чтобы преобразовать PDF в SVG, вам нужно будет создать презентацию из файла PDF и сохранить ее как SVG.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Код Node.js для преобразования PDF в SVG" >}}
```javascript

var aspose = aspose || {};

aspose.slides = require("aspose.slides.via.java");

var pres = new aspose.slides.Presentation();
try
{
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("welcome-to-powerpoint.pdf");

    var slide = pres.getSlides().get_Item(0);
    var svgStream = java.newInstanceSync("java.io.FileOutputStream", "image.svg");
    slide.writeAsSvg(svgStream);
    svgStream.close();
}
finally
{
    if (pres != null) pres.dispose();
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование PDF в SVG в Node.js" %}}

[**Aspose.Slides для Node.js через Java**](https://products.aspose.com/slides/ru/nodejs-java/) — мощная библиотека Node.js для создания файлов презентаций и управления ими. Более того, он предоставляет гибкие способы преобразования PDF в SVG. Используя **Aspose.Slides for Node.js через Java**, любой разработчик или приложение может конвертировать файлы PDF в SVG с помощью всего лишь нескольких строк кода.

В качестве современного API обработки документов Aspose.Slides для Node.js быстро экспортирует файлы PDF в форматы файлов SVG. Библиотека Aspose PowerPoint позволяет конвертировать файлы PDF в SVG и многие другие форматы файлов.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать PDF в SVG с помощью Aspose.Slides для Node.js через Java API" intro="Чтобы преобразовать PDF в SVG с помощью Aspose.Slides для Node.js через Java, вам необходимо импортировать пакет в файл JavaScript и создать экземпляр класса Presentation. Класс Presentation представляет документ PowerPoint и предоставляет методы для доступа к его элементам и управления ими." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите [**Aspose.Slides для Node.js через Java**](https://products.aspose.com/slides/ru/nodejs-java/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте исходные файлы PDF в Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохранить результат как файл SVG.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Преобразование PDF в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать PDF и сохранять в другие форматы файлов. Все поддерживаемые форматы см. ниже." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-bmp/" name="PDF TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-fodp/" name="PDF TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-gif/" name="PDF TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-odp/" name="PDF TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-otp/" name="PDF TO OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-pot/" name="PDF TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-potm/" name="PDF TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-potx/" name="PDF TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-pps/" name="PDF TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-ppsm/" name="PDF TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-ppsx/" name="PDF TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-pptm/" name="PDF TO PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-java/conversion/pdf-to-tiff/" name="PDF TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
