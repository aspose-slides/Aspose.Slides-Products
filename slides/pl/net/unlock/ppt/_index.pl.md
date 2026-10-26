---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Odblokowywanie plików prezentacji PPT za pomocą .NET
url: /pl/net/unlock/ppt/
description: Kod źródłowy C# do usuwania ochrony hasłem z prezentacji PPT.
keywords: Usuwanie ochrony przed zapisem PPT, odszyfrowanie PPT, odblokowanie prezentacji PPT, zdjęcie ochrony z PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Odblokowywanie plików PPT za pomocą C#" h2="Twórz aplikacje .NET, które usuwają szyfrowanie i ochronę przed zapisem z prezentacji za pomocą interfejsów API po stronie serwera." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Usuwanie ochrony z prezentacji PPT za pomocą C#" variant="code" %}}

Dzięki [Aspose.Slides for .NET](/slides/pl/net/) możesz usunąć szyfrowanie lub ochronę przed zapisem z prezentacji PPT. Aby usunąć szyfrowanie, wczytaj prezentację z prawidłowym hasłem i wywołaj `ProtectionManager.RemoveEncryption`. Aby usunąć ochronę przed zapisem, wywołaj `ProtectionManager.RemoveWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Usuwanie szyfrowania z prezentacji PPT za pomocą C#" >}}
```cs
var loadOptions = new LoadOptions { Password = "password" };
using var presentation = new Presentation("encrypted-presentation.ppt", loadOptions);

presentation.ProtectionManager.RemoveEncryption();
presentation.Save("unencrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Usuwanie ochrony przed zapisem z prezentacji PPT za pomocą C#" >}}
```cs
using var presentation = new Presentation("write-protected-presentation.ppt");

presentation.ProtectionManager.RemoveWriteProtection();
presentation.Save("unprotected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak usunąć ochronę z prezentacji PPT za pomocą C#" intro="Wykonaj poniższe kroki, aby usunąć ochronę z prezentacji PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPT za pomocą `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}W przypadku zaszyfrowanego pliku podaj hasło przez `LoadOptions.Password` przed jego wczytaniem.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj `ProtectionManager.RemoveEncryption` lub `ProtectionManager.RemoveWriteProtection`, zależnie od zastosowanej ochrony.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz odblokowaną prezentację za pomocą `SaveFormat.Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Zbudowano z Aspose.Slides" title="Odblokowywanie plików PPT online" description="Bezpłatna aplikacja Aspose.Slides Unlock została zbudowana z użyciem [Aspose.Slides for .NET](https://products.aspose.com/slides/pl/net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPT." button="Otwórz Aspose.Slides Unlock" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides usuwa ochronę, zanim napiszesz kod.
- Usuń hasło lub ochronę przed zapisem z pliku PPT.
- Pobierz odblokowany plik.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty odblokowywania" subTitle="Za pomocą C# możesz usunąć ochronę także z następujących formatów." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
