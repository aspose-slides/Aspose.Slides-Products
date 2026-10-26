---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ochrona prezentacji PPT za pomocą C++
url: /pl/cpp/protect/ppt/
description: Chroń prezentacje PPT w C++. Użyj Aspose.Slides for C++, aby szyfrować pliki i ustawiać ochronę przed zapisem.
keywords: Ochrona przed zapisem PPT, szyfrowanie PPT, blokowanie prezentacji PPT, ochrona PPT
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Blokowanie lub ochrona hasłem pliku PPT za pomocą C++" h2="Użyj Aspose.Slides for C++, aby szyfrować prezentacje i ustawiać ochronę przed zapisem bez Microsoft PowerPoint." related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ochrona prezentacji PPT za pomocą C++" variant="code" %}}

Aspose.Slides for C++ pozwala chronić prezentacje PPT przed otwarciem lub modyfikacją. Użyj obiektu `ProtectionManager` z klasy `Presentation`, aby zaszyfrować plik metodą `Encrypt` lub ograniczyć edycję metodą `SetWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szyfrowanie prezentacji PPT za pomocą C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ustawianie ochrony przed zapisem prezentacji PPT za pomocą C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak chronić plik PPT hasłem za pomocą C++" intro="Wykonaj poniższe kroki, aby chronić prezentację PPT." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPT za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zabezpiecz prezentację za pomocą obiektu `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Użyj `Encrypt` do ochrony hasłem lub `SetWriteProtection` do ochrony przed zapisem.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz chroniony plik za pomocą `SaveFormat::Ppt`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Zbudowano z Aspose.Slides" title="Ochrona plików PPT hasłem online" description="Bezpłatna aplikacja Aspose.Slides Lock została zbudowana z użyciem [Aspose.Slides for C++](https://products.aspose.com/slides/pl/cpp/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPT." button="Otwórz Aspose.Slides Lock" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides chroni prezentacje, zanim napiszesz kod.
- Ustaw hasło do otwierania lub edycji pliku PPT.
- Pobierz chroniony plik.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty ochrony" subTitle="Za pomocą C++ możesz chronić także następujące formaty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
