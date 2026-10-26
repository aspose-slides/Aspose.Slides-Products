---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Odblokowywanie prezentacji PPT za pomocą Pythona
url: /pl/python-net/unlock/ppt/
description: Usuwaj szyfrowanie i ochronę przed zapisem z prezentacji PPT za pomocą Pythona.
keywords: odblokowanie PPT, usunięcie hasła z PPT, usunięcie szyfrowania PPT, usunięcie ochrony przed zapisem z PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Odblokowywanie prezentacji PPT za pomocą Pythona" h2="Twórz aplikacje w Pythonie, które usuwają hasła otwarcia i ochronę przed zapisem z prezentacji PPT za pomocą Aspose.Slides." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Usuwanie szyfrowania i ochrony przed zapisem z pliku PPT za pomocą Pythona" variant="code" %}}

Dzięki [Aspose.Slides for Python via .NET](/slides/pl/python-net/) możesz usunąć szyfrowanie, które wymaga hasła do otwarcia prezentacji PPT, lub wyłączyć jej ochronę przed zapisem. Aby otworzyć zaszyfrowany plik, podaj bieżące hasło przez `LoadOptions`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Usuwanie szyfrowania z prezentacji PPT – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.ppt", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Usuwanie ochrony przed zapisem z prezentacji PPT – Python" >}}
```py
with slides.Presentation("write-protected-presentation.ppt") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.ppt", slides.export.SaveFormat.PPT)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak usunąć ochronę z pliku PPT za pomocą Pythona" intro="Wykonaj poniższe kroki, aby usunąć ochronę z prezentacji PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}W przypadku zaszyfrowanego pliku PPT ustaw bieżące hasło w `LoadOptions`, a następnie otwórz plik za pomocą `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj `ProtectionManager.remove_encryption`, aby usunąć hasło otwarcia, lub `ProtectionManager.remove_write_protection`, aby wyłączyć ochronę przed zapisem.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz wynikową prezentację za pomocą `SaveFormat.PPT`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Zbudowano z Aspose.Slides" title="Odblokowywanie plików PPT online" description="Bezpłatna aplikacja Aspose.Slides Unlock została zbudowana z użyciem [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pl/python-net/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPT." button="Otwórz Aspose.Slides Unlock" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides usuwa ochronę, zanim napiszesz kod.
- Usuń hasło lub ochronę przed zapisem z pliku PPT.
- Pobierz odblokowany plik.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty odblokowywania" subTitle="Użyj Pythona, aby usunąć ochronę z innych obsługiwanych formatów prezentacji." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/python-net/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
