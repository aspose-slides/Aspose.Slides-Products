---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Разблокировка файлов презентаций PPT с помощью Java
url: /ru/java/unlock/ppt/
description: Снимайте пароли и защиту от записи с презентаций PPT на Java с помощью Aspose.Slides for Java.
keywords: Снятие защиты от записи PPT, расшифровка PPT, разблокировка презентации PPT, снятие защиты с PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Разблокировка PPT на Java" h2="Создавайте Java-приложения, которые снимают пароли и защиту от записи с файлов презентаций с помощью серверных API." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Снятие защиты с презентации PPT на Java" variant="code" %}}

С помощью [Aspose.Slides for Java](/slides/ru/java/) можно снять шифрование или защиту от записи с презентации PPT. Используйте `LoadOptions.setPassword`, чтобы открыть зашифрованную презентацию, и методы `removeEncryption` и `removeWriteProtection` объекта `ProtectionManager`, чтобы снять параметры защиты.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Снятие защиты паролем с PPT на Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Снятие защиты от записи с презентации PPT на Java" >}}
```java
Presentation presentation = new Presentation("presentation.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как удалить пароль из PPT на Java" intro="Выполните следующие шаги, чтобы снять защиту с презентации PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPT с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Если презентация зашифрована, используйте `LoadOptions.setPassword`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите `removeEncryption` или `removeWriteProtection` объекта `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните разблокированную презентацию с помощью `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Создано на основе Aspose.Slides" title="Разблокировка файлов PPT онлайн" description="Бесплатное приложение Aspose.Slides Unlock создано на основе [Aspose.Slides for Java](https://products.aspose.com/slides/ru/java/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPT." button="Открыть Aspose.Slides Unlock" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides снимает защиту, прежде чем писать код.
- Удалите пароль или защиту от записи из файла PPT.
- Скачайте разблокированный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для разблокировки" subTitle="С помощью Java вы также можете снимать защиту со следующих форматов." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
