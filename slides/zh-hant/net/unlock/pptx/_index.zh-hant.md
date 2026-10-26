---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 .NET 解除鎖定 PPTX 簡報檔案
url: /zh-hant/net/unlock/pptx/
description: 移除 PPTX 簡報密碼保護的 C# 原始程式碼。
keywords: 移除 PPTX 防寫保護, 解密 PPTX, 解除鎖定 PPTX 簡報, 取消 PPTX 保護
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 解除鎖定 PPTX 檔案" h2="建置 .NET 應用程式，透過伺服器端 API 移除簡報的加密與防寫保護。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C# 移除 PPTX 簡報的保護" variant="code" %}}

透過 [Aspose.Slides for .NET](/slides/zh-hant/net/)，您可以移除 PPTX 簡報的加密或防寫保護。若要移除加密，請以正確的密碼載入簡報並呼叫 `ProtectionManager.RemoveEncryption`。若要移除防寫保護，請呼叫 `ProtectionManager.RemoveWriteProtection`。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 移除 PPTX 簡報的加密" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.pptx", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 移除 PPTX 簡報的防寫保護" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.pptx");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 移除 PPTX 簡報的保護" intro="依照下列步驟移除 PPTX 簡報的保護。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 載入 PPTX 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}若為加密檔案，請在載入前透過 `LoadOptions.Password` 提供密碼。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}依照所套用的保護類型，呼叫 `ProtectionManager.RemoveEncryption` 或 `ProtectionManager.RemoveWriteProtection`。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Pptx` 儲存已解除鎖定的簡報。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="以 Aspose.Slides 建置" title="線上解除鎖定 PPTX 檔案" description="免費的 Aspose.Slides Unlock 應用程式以 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPTX 檔案。" button="開啟 Aspose.Slides Unlock" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何移除保護。
- 移除 PPTX 檔案的密碼或防寫保護。
- 下載已解除鎖定的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援解除鎖定的格式" subTitle="使用 C#，您也可以移除下列格式的保護。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
