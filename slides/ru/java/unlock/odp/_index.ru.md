---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Разблокировка файлов презентаций ODP с помощью Java
url: /ru/java/unlock/odp/
description: Снимайте пароли и защиту от записи с презентаций ODP на Java с помощью Aspose.Slides for Java.
keywords: Снятие защиты от записи ODP, расшифровка ODP, разблокировка презентации ODP, снятие защиты с ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Разблокировка ODP на Java" h2="Создавайте Java-приложения, которые снимают пароли и защиту от записи с файлов презентаций с помощью серверных API." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Снятие защиты с презентации ODP на Java" variant="code" %}}

С помощью [Aspose.Slides for Java](/slides/ru/java/) можно снять шифрование или защиту от записи с презентации ODP. Используйте `LoadOptions.setPassword`, чтобы открыть зашифрованную презентацию, и методы `removeEncryption` и `removeWriteProtection` объекта `ProtectionManager`, чтобы снять параметры защиты.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Снятие защиты паролем с ODP на Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.odp", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Снятие защиты от записи с презентации ODP на Java" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как удалить пароль из ODP на Java" intro="Выполните следующие шаги, чтобы снять защиту с презентации ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл ODP с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Если презентация зашифрована, используйте `LoadOptions.setPassword`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите `removeEncryption` или `removeWriteProtection` объекта `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните разблокированную презентацию с помощью `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Создано на основе Aspose.Slides" title="Разблокировка файлов ODP онлайн" description="Бесплатное приложение Aspose.Slides Unlock создано на основе [Aspose.Slides for Java](https://products.aspose.com/slides/ru/java/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами ODP." button="Открыть Aspose.Slides Unlock" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides снимает защиту, прежде чем писать код.
- Удалите пароль или защиту от записи из файла ODP.
- Скачайте разблокированный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для разблокировки" subTitle="С помощью Java вы также можете снимать защиту со следующих форматов." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
