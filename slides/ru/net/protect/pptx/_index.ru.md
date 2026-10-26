---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Защита файлов презентаций PPTX с помощью .NET
url: /ru/net/protect/pptx/
description: Исходный код на C# для защиты презентаций PPTX паролем.
keywords: Защита PPTX от записи, шифрование PPTX, блокировка презентации PPTX, защита PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Блокировка или защита паролем файлов PPTX на C#" h2="Создавайте приложения .NET, которые шифруют презентации и ограничивают их изменение с помощью серверных API." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Защита презентации PPTX на C#" variant="code" %}}

С помощью [Aspose.Slides for .NET](/slides/ru/net/) можно зашифровать презентацию PPTX или ограничить ее изменение паролем. Чтобы открыть презентацию, зашифрованную с помощью `ProtectionManager.Encrypt`, требуется пароль. Используйте `ProtectionManager.SetWriteProtection`, чтобы презентацию можно было открыть, но нельзя было свободно изменить.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Шифрование презентации PPTX на C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Установка защиты от записи для презентации PPTX на C#" >}}
```cs
using var presentation = new Presentation("presentation.pptx");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как защитить презентацию PPTX паролем на C#" intro="Выполните следующие шаги, чтобы защитить презентацию PPTX паролем." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPTX с помощью `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Зашифруйте презентацию с помощью `ProtectionManager.Encrypt` или ограничьте изменения с помощью `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните защищенный файл с помощью `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Создано на основе Aspose.Slides" title="Защита файлов PPTX паролем онлайн" description="Бесплатное приложение Aspose.Slides Lock создано на основе [Aspose.Slides for .NET](https://products.aspose.com/slides/ru/net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Lock" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides защищает презентации, прежде чем писать код.
- Установите пароль для открытия или редактирования файла PPTX.
- Скачайте защищенный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для защиты" subTitle="С помощью C# вы также можете защищать следующие форматы." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
