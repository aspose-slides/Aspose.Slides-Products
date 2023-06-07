---
title: Разблокируйте файлы презентаций ODP с помощью Python
url: /ru/python-net/unlock/odp/
keywords: Снять защиту от записи ODP, расшифровать ODP, разблокировать презентацию ODP, снять защиту ODP
description: Исходный код Python для снятия защиты с презентации ODP.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Разблокируйте ODP с помощью Python" h2="Создавайте собственные приложения Python, чтобы удалять пароли из PowerPoint и расшифровывать файлы презентаций с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Удаление шифрования из презентации ODP через Python" %}}
Используя Aspose.Slides for Python via .NET, вы можете удалить шифрование или защиту паролем в презентации ODP. Таким образом, пользователи могут без ограничений получать доступ к презентации ODP или изменять ее.
{{% blocks/products/pf/agp/code-block title="Отключение защиты паролем от ODP с помощью Python" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.odp", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Снятие защиты от записи с презентации ODP с использованием Python" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.odp") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.odp", slides.export.SaveFormat.ODP)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как удалить пароль из ODP через Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для снятия защиты с файлов ODP." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите ODP с экземпляром Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Удалить защиту от записи с помощью класса ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат в формате ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы" subTitle="С помощью Python Вы также можете снять защиту со следующих форматов:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}