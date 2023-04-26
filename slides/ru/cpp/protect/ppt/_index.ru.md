---
title: Защитите файлы презентаций PPT с помощью C++
url: /ru/cpp/protect/ppt/
keywords: Защита от записи PPT, шифрование PPT, блокировка презентации PPT, защита PPT
description: Исходный код C++ для защиты презентации PPT.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Заблокируйте или защитите паролем PPT с помощью C++" h2="Создавайте собственные приложения C++ для защиты файлов презентаций с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Защита презентации PPT через C++" %}}
Используя Aspose.Slides for C++, вы можете защитить свою презентацию PPT от открытия или изменения, установив пароль. Затем, чтобы открыть или изменить заблокированную презентацию, пользователь должен ввести пароль.
{{% blocks/products/pf/agp/code-block title="Шифрование презентации PPT с использованием C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.ppt");

presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Установка защиты от записи для презентации PPT с использованием C++" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"pres.ppt");

presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Как защитить паролем PPT через C++" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Это шаги для защиты файлов PPT." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Загрузите PPT с экземпляром Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Защитите презентацию с помощью класса ProtectionManager
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Сохранить результат в формате PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы защиты" subTitle="Используя C++, Вы также можете защитить следующие форматы:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ru/cpp/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}