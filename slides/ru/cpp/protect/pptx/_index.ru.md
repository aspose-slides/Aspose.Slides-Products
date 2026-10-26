---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Защита презентаций PPTX на C++
url: /ru/cpp/protect/pptx/
description: Защищайте презентации PPTX на C++. Используйте Aspose.Slides for C++ для шифрования файлов и установки защиты от записи.
keywords: Защита PPTX от записи, шифрование PPTX, блокировка презентации PPTX, защита PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Блокировка или защита паролем PPTX на C++" h2="Используйте Aspose.Slides for C++ для шифрования презентаций и установки защиты от записи без Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Защита презентации PPTX на C++" variant="code" %}}

Aspose.Slides for C++ позволяет защитить презентации PPTX от открытия или изменения. Используйте объект `ProtectionManager` класса `Presentation`, чтобы зашифровать файл методом `Encrypt` или ограничить редактирование методом `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Шифрование презентации PPTX на C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Установка защиты от записи для презентации PPTX на C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как защитить PPTX паролем на C++" intro="Выполните следующие шаги, чтобы защитить презентацию PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPTX с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Защитите презентацию с помощью объекта `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Используйте `Encrypt` для защиты паролем или `SetWriteProtection` для защиты от записи.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните защищенный файл с помощью `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Создано на основе Aspose.Slides" title="Защита файлов PPTX паролем онлайн" description="Бесплатное приложение Aspose.Slides Lock создано на основе [Aspose.Slides for C++](https://products.aspose.com/slides/ru/cpp/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Lock" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides защищает презентации, прежде чем писать код.
- Установите пароль для открытия или редактирования файла PPTX.
- Скачайте защищенный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для защиты" subTitle="С помощью C++ вы также можете защищать следующие форматы." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
