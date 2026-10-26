---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Разблокировка презентаций PPTX с помощью Python
url: /ru/python-net/unlock/pptx/
description: Снимайте шифрование и защиту от записи с презентаций PPTX с помощью Python.
keywords: разблокировать PPTX, удалить пароль из PPTX, снять шифрование PPTX, снять защиту от записи с PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Разблокировка презентаций PPTX с помощью Python" h2="Создавайте приложения на Python, которые снимают пароли на открытие и защиту от записи с презентаций PPTX с помощью Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Снятие шифрования и защиты от записи с PPTX с помощью Python" variant="code" %}}

С помощью [Aspose.Slides for Python via .NET](/slides/ru/python-net/) можно снять шифрование, из-за которого для открытия презентации PPTX требуется пароль, или отключить ее защиту от записи. Чтобы открыть зашифрованный файл, укажите текущий пароль через `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Снятие шифрования с презентации PPTX – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.pptx", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Снятие защиты от записи с презентации PPTX – Python" >}}
```py
with slides.Presentation("write-protected-presentation.pptx") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как снять защиту с PPTX с помощью Python" intro="Выполните следующие шаги, чтобы снять защиту с презентации PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Для зашифрованного файла PPTX задайте текущий пароль в `LoadOptions`, а затем откройте файл с помощью `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Вызовите `ProtectionManager.remove_encryption`, чтобы удалить пароль на открытие, или `ProtectionManager.remove_write_protection`, чтобы отключить защиту от записи.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните полученную презентацию с помощью `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Создано на основе Aspose.Slides" title="Разблокировка файлов PPTX онлайн" description="Бесплатное приложение Aspose.Slides Unlock создано на основе [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ru/python-net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Unlock" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides снимает защиту, прежде чем писать код.
- Удалите пароль или защиту от записи из файла PPTX.
- Скачайте разблокированный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для разблокировки" subTitle="Используйте Python, чтобы снимать защиту с других поддерживаемых форматов презентаций." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
