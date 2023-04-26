---
title: Защитите файлы презентаций PPTX с помощью Python
url: /ru/python-net/protect/pptx/
keywords: Защита от записи PPTX, шифрование PPTX, блокировка презентации PPTX, защита PPTX
description: Исходный код Python для защиты презентации PPTX.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Заблокируйте или защитите паролем PPTX с помощью Python" h2="Создавайте собственные приложения Python для защиты файлов презентаций с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Защита презентации PPTX через Python" %}}
Используя Aspose.Slides for Python via .NET, вы можете защитить свою презентацию PPTX от открытия или изменения, установив пароль. Затем, чтобы открыть или изменить заблокированную презентацию, пользователь должен ввести пароль.
{{% blocks/products/pf/agp/code-block title="Шифрование презентации PPTX с использованием Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Установка защиты от записи для презентации PPTX с использованием Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как защитить паролем PPTX через Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для защиты файлов PPTX." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите PPTX с экземпляром Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Защитите презентацию с помощью класса ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат в формате PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы защиты" subTitle="Используя Python, Вы также можете защитить следующие форматы:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}