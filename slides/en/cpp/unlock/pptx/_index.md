---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Unlock PPTX Presentations using C++
url: /cpp/unlock/pptx/
keywords: Remove Write Protection PPTX, Decrypt PPTX, Unlock PPTX Presentation, Unprotect PPTX
description: Unlock PPTX presentations in C++. Use Aspose.Slides for C++ to remove encryption and write protection from presentation files.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Unlock PPTX using C++" h2="Use Aspose.Slides for C++ to remove encryption and write protection from presentation files without Microsoft PowerPoint." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Removing Protection from a PPTX Presentation via C++" variant="code" %}}

Aspose.Slides for C++ lets you remove encryption or write protection from PPTX presentations. Use `LoadOptions` to open an encrypted file, then use the `ProtectionManager` object from the `Presentation` class to call `RemoveEncryption` or `RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Removing Password Protection from PPTX using C++" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Removing Write Protection from a PPTX Presentation using C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Remove a Password from PPTX via C++" intro="Follow these steps to remove protection from a PPTX presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPTX file with the `Presentation` class and `LoadOptions` when a password is required.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use the `ProtectionManager` object to remove protection.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call `RemoveEncryption` for encrypted files or `RemoveWriteProtection` for write-protected files.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the unlocked file with `SaveFormat::Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Unlocking Formats" subTitle="Using C++, you can also remove protection from the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/cpp/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
