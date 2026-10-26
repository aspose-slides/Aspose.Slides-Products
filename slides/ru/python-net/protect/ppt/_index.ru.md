---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Защита файлов презентаций PPT с помощью Python
url: /ru/python-net/protect/ppt/
description: Шифруйте презентации PPT или устанавливайте защиту от записи с помощью Python.
keywords: защита PPT от записи, шифрование PPT на Python, блокировка презентации PPT, защита PPT на Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Защита презентаций PPT с помощью Python" h2="Создавайте приложения на Python, которые шифруют презентации или устанавливают защиту от записи с помощью Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Защита презентации PPT с помощью Python" variant="code" %}}

[**Aspose.Slides for Python via .NET**](/slides/ru/python-net/) предоставляет два разных механизма защиты. Вызовите `ProtectionManager.encrypt`, чтобы зашифровать презентацию PPT и требовать пароль для ее открытия. Либо вызовите `ProtectionManager.set_write_protection`, чтобы предостеречь от изменений без шифрования файла. Пользователь по-прежнему может открыть защищенную от записи презентацию и сохранить изменения в другой файл.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Шифрование презентации PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Установка защиты от записи для презентации PPT – Python" >}}
```python
with slides.Presentation("presentation.ppt") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как защитить PPT с помощью Python" intro="Выполните следующие шаги, чтобы защитить файл PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Откройте файл PPT с помощью `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Используйте `ProtectionManager.encrypt`, чтобы требовать пароль при открытии, или `ProtectionManager.set_write_protection`, чтобы предостеречь от изменений.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните защищенную презентацию в формате PPT с помощью `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Создано на основе Aspose.Slides" title="Защита файлов PPT паролем онлайн" description="Бесплатное приложение Aspose.Slides Lock создано на основе [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ru/python-net/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPT." button="Открыть Aspose.Slides Lock" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides защищает презентации, прежде чем писать код.
- Установите пароль для открытия или редактирования файла PPT.
- Скачайте защищенный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для защиты" subTitle="Используйте Python для защиты других поддерживаемых форматов презентаций." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/python-net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
