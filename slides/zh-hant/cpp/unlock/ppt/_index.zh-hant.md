---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C++ 解除鎖定 PPT 簡報
url: /zh-hant/cpp/unlock/ppt/
description: 在 C++ 中解除鎖定 PPT 簡報。使用 Aspose.Slides for C++ 移除簡報檔案的加密與防寫保護。
keywords: 移除 PPT 防寫保護, 解密 PPT, 解除鎖定 PPT 簡報, 取消 PPT 保護
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 解除鎖定 PPT" h2="使用 Aspose.Slides for C++ 移除簡報檔案的加密與防寫保護，無需 Microsoft PowerPoint。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 C++ 移除 PPT 簡報的保護" variant="code" %}}

Aspose.Slides for C++ 可移除 PPT 簡報的加密或防寫保護。使用 `LoadOptions` 開啟加密檔案，然後使用 `Presentation` 類別中的 `ProtectionManager` 物件呼叫 `RemoveEncryption` 或 `RemoveWriteProtection`。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 移除 PPT 的密碼保護" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.ppt", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 移除 PPT 簡報的防寫保護" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.ppt");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何透過 C++ 移除 PPT 的密碼" intro="依照下列步驟移除 PPT 簡報的保護。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 PPT 檔案，需要密碼時一併使用 `LoadOptions`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `ProtectionManager` 物件移除保護。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}對加密檔案呼叫 `RemoveEncryption`，對防寫保護檔案呼叫 `RemoveWriteProtection`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat::Ppt` 儲存已解除鎖定的檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="以 Aspose.Slides 建置" title="線上解除鎖定 PPT 檔案" description="免費的 Aspose.Slides Unlock 應用程式以 [Aspose.Slides for C++](https://products.aspose.com/slides/zh-hant/cpp/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Unlock" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何移除保護。
- 移除 PPT 檔案的密碼或防寫保護。
- 下載已解除鎖定的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援解除鎖定的格式" subTitle="使用 C++，您也可以移除下列格式的保護。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
