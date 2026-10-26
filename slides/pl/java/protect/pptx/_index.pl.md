---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ochrona plików prezentacji PPTX za pomocą Javy
url: /pl/java/protect/pptx/
description: Chroń prezentacje PPTX w Javie. Użyj Aspose.Slides for Java, aby szyfrować pliki prezentacji i ustawiać ochronę przed zapisem.
keywords: Ochrona przed zapisem PPTX, szyfrowanie pliku PPTX, blokowanie prezentacji PPTX, ochrona PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Blokowanie lub ochrona hasłem pliku PPTX za pomocą Javy" h2="Twórz aplikacje Java, które chronią pliki prezentacji za pomocą interfejsów API po stronie serwera." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ochrona prezentacji PPTX za pomocą Javy" variant="code" %}}

Dzięki [Aspose.Slides for Java](/slides/pl/java/) możesz chronić prezentację PPTX przed otwarciem lub modyfikacją, ustawiając hasło. Użyj obiektu `ProtectionManager` z klasy `Presentation`, aby wywołać metody takie jak `encrypt` i `setWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Szyfrowanie prezentacji PPTX za pomocą Javy" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Ustawianie ochrony przed zapisem prezentacji PPTX za pomocą Javy" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-presentation.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak chronić plik PPTX hasłem za pomocą Javy" intro="Wykonaj poniższe kroki, aby chronić prezentację PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik PPTX za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę `encrypt` lub metodę `setWriteProtection` obiektu `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz chroniony plik za pomocą `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Zbudowano z Aspose.Slides" title="Ochrona plików PPTX hasłem online" description="Bezpłatna aplikacja Aspose.Slides Lock została zbudowana z użyciem [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami PPTX." button="Otwórz Aspose.Slides Lock" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides chroni prezentacje, zanim napiszesz kod.
- Ustaw hasło do otwierania lub edycji pliku PPTX.
- Pobierz chroniony plik.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty ochrony" subTitle="Za pomocą Javy możesz chronić także następujące formaty." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
