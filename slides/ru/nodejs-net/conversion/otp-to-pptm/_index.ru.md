---
lastmod: 2024-04-10
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Преобразование OTP в PPTM в JavaScript
url: /ru/nodejs-net/conversion/otp-to-pptm/
keywords: OTP в PPTM, преобразование OTP в PPTM, Node.js API, библиотека JavaScript, OTP, PPTM
description: Преобразуйте OTP в PPTM в JavaScript. Используйте API библиотеки Node.js для преобразования файлов OTP в PPTM
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Преобразование OTP в PPTM в JavaScript" h2="Aspose.Slides для Node.js через .NET — это мощная и простая в использовании библиотека, позволяющая конвертировать презентации PowerPoint в различные форматы с помощью JavaScript. Он поддерживает все элементы и форматы презентаций и предоставляет богатый API для доступа к ним и их изменения. Он также позволяет экспортировать слайды в различные форматы для дальнейшей обработки или обмена." >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование OTP в PPTM с помощью JavaScript" variant="code" %}}

Чтобы преобразовать OTP в PPTM, вам нужно будет создать презентацию из файла OTP и сохранить ее как PPTM.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Код JavaScript для преобразования OTP в PPTM" >}}
```javascript

const fs = require('fs');
const asposeSlides = require('aspose.slides.via.net');
const { Presentation, SaveFormat } = asposeSlides;
var pres = new Presentation("welcome-to-powerpoint.otp");
try
{
    pres.save("output.pptm", SaveFormat.Pptm);
}
finally
{
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Преобразование OTP в PPTM в Node.js" %}}

[**Aspose.Slides для Node.js через .NET**](https://products.aspose.com/slides/ru/nodejs-net/) — мощная библиотека Node.js для создания файлов презентаций и управления ими. Более того, он предоставляет гибкие способы преобразования OTP в PPTM. Используя **Aspose.Slides для Node.js через .NET**, любой разработчик или приложение может конвертировать файлы OTP в PPTM с помощью всего лишь нескольких строк кода.

В качестве современного API обработки документов Aspose.Slides для Node.js через .NET быстро экспортирует файлы OTP в форматы файлов PPTM. Библиотека Aspose PowerPoint позволяет конвертировать файлы OTP в PPTM и многие другие форматы файлов.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как преобразовать OTP в PPTM с помощью Aspose.Slides для Node.js через .NET API" intro="Чтобы преобразовать OTP в PPTM с помощью Aspose.Slides для Node.js через .NET, вам необходимо импортировать пакет в файл JavaScript и создать экземпляр класса Presentation. Класс Presentation представляет документ PowerPoint и предоставляет методы для доступа к его элементам и управления ими." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Установите [**Aspose.Slides для Node.js через .NET**](https://products.aspose.com/slides/ru/nodejs-net/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Добавьте ссылку на библиотеку (импортируйте библиотеку) в свой проект Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте исходные файлы OTP в Node.js.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохранить результат как файл PPTM.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Преобразование OTP в другие поддерживаемые форматы" subTitle="Вы также можете конвертировать OTP и сохранять в другие форматы файлов. Все поддерживаемые форматы см. ниже." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-pptx/" name="OTP TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-ppt/" name="OTP TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-pdf/" name="OTP TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-html/" name="OTP TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-png/" name="OTP TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-bmp/" name="OTP TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-jpg/" name="OTP TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-fodp/" name="OTP TO FODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-gif/" name="OTP TO GIF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-odp/" name="OTP TO ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-pot/" name="OTP TO POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-potm/" name="OTP TO POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-potx/" name="OTP TO POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-pps/" name="OTP TO PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-ppsm/" name="OTP TO PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-ppsx/" name="OTP TO PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-svg/" name="OTP TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ru/nodejs-net/conversion/otp-to-tiff/" name="OTP TO TIFF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
