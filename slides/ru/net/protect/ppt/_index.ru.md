---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Защита файлов презентаций PPT с помощью .NET
url: /ru/net/protect/ppt/
description: Исходный код на C# для защиты презентаций PPT паролем.
keywords: Защита PPT от записи, шифрование PPT, блокировка презентации PPT, защита PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Блокировка или защита паролем файлов PPT на C#" h2="Создавайте приложения .NET, которые шифруют презентации и ограничивают их изменение с помощью серверных API." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Защита презентации PPT на C#" variant="code" %}}

С помощью [Aspose.Slides for .NET](/slides/ru/net/) можно зашифровать презентацию PPT или ограничить ее изменение паролем. Чтобы открыть презентацию, зашифрованную с помощью `ProtectionManager.Encrypt`, требуется пароль. Используйте `ProtectionManager.SetWriteProtection`, чтобы презентацию можно было открыть, но нельзя было свободно изменить.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Шифрование презентации PPT на C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Установка защиты от записи для презентации PPT на C#" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как защитить презентацию PPT паролем на C#" intro="Выполните следующие шаги, чтобы защитить презентацию PPT паролем." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPT с помощью `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Зашифруйте презентацию с помощью `ProtectionManager.Encrypt` или ограничьте изменения с помощью `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните защищенный файл с помощью `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Создано на основе Aspose.Slides" title="Защита файлов PPT паролем онлайн" description="Бесплатное приложение Aspose.Slides Lock создано на основе [Aspose.Slides for .NET](https://products.aspose.com/slides/ru/net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPT." button="Открыть Aspose.Slides Lock" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides защищает презентации, прежде чем писать код.
- Установите пароль для открытия или редактирования файла PPT.
- Скачайте защищенный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для защиты" subTitle="С помощью C# вы также можете защищать следующие форматы." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
