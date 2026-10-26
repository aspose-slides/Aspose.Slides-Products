---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Разблокировка презентаций PPT на C++
url: /ru/cpp/unlock/ppt/
description: Разблокируйте презентации PPT на C++. Используйте Aspose.Slides for C++, чтобы снимать шифрование и защиту от записи с файлов презентаций.
keywords: Снятие защиты от записи PPT, расшифровка PPT, разблокировка презентации PPT, снятие защиты с PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Разблокировка PPT на C++" h2="Используйте Aspose.Slides for C++, чтобы снимать шифрование и защиту от записи с файлов презентаций без Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Снятие защиты с презентации PPT на C++" variant="code" %}}

Aspose.Slides for C++ позволяет снимать шифрование или защиту от записи с презентаций PPT. Используйте `LoadOptions`, чтобы открыть зашифрованный файл, а затем объект `ProtectionManager` класса `Presentation`, чтобы вызвать `RemoveEncryption` или `RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Снятие защиты паролем с PPT на C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.ppt", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Снятие защиты от записи с презентации PPT на C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.ppt");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как удалить пароль из PPT на C++" intro="Выполните следующие шаги, чтобы снять защиту с презентации PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPT с помощью класса `Presentation` и, если требуется пароль, `LoadOptions`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Используйте объект `ProtectionManager`, чтобы снять защиту.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите `RemoveEncryption` для зашифрованных файлов или `RemoveWriteProtection` для файлов, защищенных от записи.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните разблокированный файл с помощью `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Создано на основе Aspose.Slides" title="Разблокировка файлов PPT онлайн" description="Бесплатное приложение Aspose.Slides Unlock создано на основе [Aspose.Slides for C++](https://products.aspose.com/slides/ru/cpp/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPT." button="Открыть Aspose.Slides Unlock" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides снимает защиту, прежде чем писать код.
- Удалите пароль или защиту от записи из файла PPT.
- Скачайте разблокированный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для разблокировки" subTitle="С помощью C++ вы также можете снимать защиту со следующих форматов." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
