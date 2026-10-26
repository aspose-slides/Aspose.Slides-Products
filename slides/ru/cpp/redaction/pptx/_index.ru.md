---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Скрытие данных в презентациях PPTX с помощью C++
url: /ru/cpp/redaction/pptx/
description: Скрывайте данные в презентациях PPTX на C++. Используйте Aspose.Slides for C++, чтобы находить и заменять конфиденциальный текст в файлах презентаций.
keywords: скрыть данные в PPTX, найти и заменить текст в PPTX, обновить презентацию PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Скрытие данных в PPTX с помощью C++" h2="Используйте Aspose.Slides for C++, чтобы находить и заменять конфиденциальный текст в файлах презентаций без Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Скрытие данных в презентации PPTX на C++" variant="code" %}}

Aspose.Slides for C++ позволяет скрывать данные в презентациях PPTX, заменяя конфиденциальный текст на слайдах. Используйте `SlideUtil::FindAndReplaceText` с объектом `Presentation`, чтобы выполнить поиск по презентации и заменить совпадающий текст перед сохранением обновлённого файла.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Скрытие данных в презентации PPTX с помощью C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Как скрыть данные в PPTX на C++" intro="Выполните следующие шаги, чтобы скрыть данные в презентации PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Загрузите файл PPTX с помощью класса `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Используйте метод [`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/), чтобы найти и заменить конфиденциальный текст.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Сохраните итоговый файл с `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Создано на основе Aspose.Slides" title="Скрытие данных в файлах PPTX онлайн" description="Бесплатное приложение Aspose.Slides Redaction создано на основе [Aspose.Slides for C++](https://products.aspose.com/slides/ru/cpp/) — того же API, что и в коде выше. Откройте его и посмотрите, что API может сделать с вашими собственными файлами PPTX." button="Открыть Aspose.Slides Redaction" note="[Все бесплатные приложения](https://products.aspose.app/slides/family)" >}}
- Работает в браузере, ничего не нужно устанавливать.
- Посмотрите, как Aspose.Slides находит и заменяет текст, ещё до написания кода.
- Находите и заменяйте текст в файле PPTX, в том числе с помощью регулярных выражений.
- Скачайте обработанный файл.
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Другие поддерживаемые форматы для скрытия данных" subTitle="С помощью C++ можно также скрывать данные в следующих форматах." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ru/cpp/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
