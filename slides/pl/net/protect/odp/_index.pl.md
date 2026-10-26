---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ochrona plików prezentacji ODP za pomocą .NET
url: /pl/net/protect/odp/
description: Kod źródłowy C# do ochrony prezentacji ODP hasłem.
keywords: Ochrona przed zapisem ODP, szyfrowanie ODP, blokowanie prezentacji ODP, ochrona ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Blokowanie lub ochrona hasłem plików ODP za pomocą C#" h2="Twórz aplikacje .NET, które szyfrują prezentacje i ograniczają ich modyfikację za pomocą interfejsów API po stronie serwera." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ochrona prezentacji ODP za pomocą C#" variant="code" %}}

Dzięki [Aspose.Slides for .NET](/slides/pl/net/) możesz zaszyfrować prezentację ODP lub ograniczyć jej modyfikację hasłem. Otwarcie prezentacji zaszyfrowanej metodą `ProtectionManager.Encrypt` wymaga podania hasła. Użyj `ProtectionManager.SetWriteProtection`, aby zezwolić na otwieranie prezentacji, ale ograniczyć wprowadzanie zmian.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szyfrowanie prezentacji ODP za pomocą C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ustawianie ochrony przed zapisem prezentacji ODP za pomocą C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.odp", SaveFormat.Odp);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak chronić prezentację ODP hasłem za pomocą C#" intro="Wykonaj poniższe kroki, aby zabezpieczyć prezentację ODP hasłem." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik ODP za pomocą `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zaszyfruj prezentację za pomocą `ProtectionManager.Encrypt` lub ogranicz zmiany za pomocą `ProtectionManager.SetWriteProtection`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz chroniony plik za pomocą `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Zbudowano z Aspose.Slides" title="Ochrona plików ODP hasłem online" description="Bezpłatna aplikacja Aspose.Slides Lock została zbudowana z użyciem [Aspose.Slides for .NET](https://products.aspose.com/slides/pl/net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami ODP." button="Otwórz Aspose.Slides Lock" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides chroni prezentacje, zanim napiszesz kod.
- Ustaw hasło do otwierania lub edycji pliku ODP.
- Pobierz chroniony plik.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty ochrony" subTitle="Za pomocą C# możesz chronić także następujące formaty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
