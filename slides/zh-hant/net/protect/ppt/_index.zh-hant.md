---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 .NET 保護 PPT 簡報檔案
url: /zh-hant/net/protect/ppt/
description: 以密碼保護 PPT 簡報的 C# 原始程式碼。
keywords: PPT 防寫保護, 加密 PPT, 鎖定 PPT 簡報, 保護 PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 鎖定 PPT 檔案或以密碼保護" h2="建置 .NET 應用程式，透過伺服器端 API 加密簡報並限制修改。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C# 保護 PPT 簡報" variant="code" %}}

透過 [Aspose.Slides for .NET](/slides/zh-hant/net/)，您可以加密 PPT 簡報，或以密碼限制其修改。開啟以 `ProtectionManager.Encrypt` 加密的簡報時需要輸入密碼。使用 `ProtectionManager.SetWriteProtection` 可允許開啟簡報，同時限制變更。

{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 加密 PPT 簡報" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="使用 C# 為 PPT 簡報設定防寫保護" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 以密碼保護 PPT 簡報" intro="依照下列步驟以密碼保護 PPT 簡報。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 載入 PPT 檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `ProtectionManager.Encrypt` 加密簡報，或使用 `ProtectionManager.SetWriteProtection` 限制變更。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Ppt` 儲存受保護的檔案。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="以 Aspose.Slides 建置" title="線上以密碼保護 PPT 檔案" description="免費的 Aspose.Slides Lock 應用程式以 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net/) 建置，與上方程式碼使用的是同一個 API。開啟它，看看 API 能如何處理您自己的 PPT 檔案。" button="開啟 Aspose.Slides Lock" note="[所有免費應用程式](https://products.aspose.app/slides/family)" >}}
- 在瀏覽器中執行，無需安裝任何軟體。
- 在撰寫程式碼之前，先了解 Aspose.Slides 如何保護簡報。
- 設定開啟或編輯 PPT 檔案所需的密碼。
- 下載受保護的檔案。
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支援保護的格式" subTitle="使用 C#，您也可以保護下列格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/zh-hant/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
