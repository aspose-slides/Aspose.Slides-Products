---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C++ 保護 ODP 簡報
url: /zh-hant/cpp/protect/odp/
description: 在 C++ 中保護 ODP 簡報。使用 Aspose.Slides for C++ 加密檔案並設定防寫保護。
keywords: ODP 防寫保護, 加密 ODP, 鎖定 ODP 簡報, 保護 ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C++ 鎖定 ODP 或以密碼保護" h2="使用 Aspose.Slides for C++ 加密簡報並設定防寫保護，無需 Microsoft PowerPoint。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="透過 C++ 保護 ODP 簡報" variant="code" %}}

Aspose.Slides for C++ 可防止 ODP 簡報被開啟或修改。使用 `Presentation` 類別中的 `ProtectionManager` 物件，以 `Encrypt` 加密檔案，或以 `SetWriteProtection` 限制編輯。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 加密 ODP 簡報" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C++ 為 ODP 簡報設定防寫保護" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何透過 C++ 以密碼保護 ODP" intro="依照下列步驟保護 ODP 簡報。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 類別載入 ODP 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `ProtectionManager` 物件保護簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Encrypt` 進行密碼保護，或使用 `SetWriteProtection` 進行防寫保護。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat::Odp` 儲存受保護的檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="以 Aspose.Slides 建置" title="線上以密碼保護 ODP 檔案" description="免費的 Aspose.Slides Lock 應用程式以 [Aspose.Slides for C++](https://products.aspose.com/slides/zh-hant/cpp/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 ODP 檔案。" button="開啟 Aspose.Slides Lock" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何保護簡報。
- 設定開啟或編輯 ODP 檔案所需的密碼。
- 下載受保護的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援保護的格式" subTitle="使用 C++，您也可以保護下列格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
