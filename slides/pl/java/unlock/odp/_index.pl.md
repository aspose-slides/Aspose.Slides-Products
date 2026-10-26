---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Odblokowywanie plików prezentacji ODP za pomocą Javy
url: /pl/java/unlock/odp/
description: Usuwaj hasła i ochronę przed zapisem z prezentacji ODP w Javie za pomocą Aspose.Slides for Java.
keywords: Usuwanie ochrony przed zapisem ODP, odszyfrowanie ODP, odblokowanie prezentacji ODP, zdjęcie ochrony z ODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Odblokowywanie pliku ODP za pomocą Javy" h2="Twórz aplikacje Java, które usuwają hasła i ochronę przed zapisem z plików prezentacji za pomocą interfejsów API po stronie serwera." related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Usuwanie ochrony z prezentacji ODP za pomocą Javy" variant="code" %}}

Dzięki [Aspose.Slides for Java](/slides/pl/java/) możesz usunąć szyfrowanie lub ochronę przed zapisem z prezentacji ODP. Użyj `LoadOptions.setPassword`, aby otworzyć zaszyfrowaną prezentację, oraz metod `removeEncryption` i `removeWriteProtection` obiektu `ProtectionManager`, aby usunąć ustawienia ochrony.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Usuwanie ochrony hasłem z pliku ODP za pomocą Javy" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.odp", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Usuwanie ochrony przed zapisem z prezentacji ODP za pomocą Javy" >}}
```java
Presentation presentation = new Presentation("presentation.odp");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.odp", SaveFormat.Odp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak usunąć hasło z pliku ODP za pomocą Javy" intro="Wykonaj poniższe kroki, aby usunąć ochronę z prezentacji ODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik ODP za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Użyj `LoadOptions.setPassword`, gdy prezentacja jest zaszyfrowana.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj `removeEncryption` lub `removeWriteProtection` obiektu `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Zapisz odblokowaną prezentację za pomocą `SaveFormat.Odp`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Zbudowano z Aspose.Slides" title="Odblokowywanie plików ODP online" description="Bezpłatna aplikacja Aspose.Slides Unlock została zbudowana z użyciem [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami ODP." button="Otwórz Aspose.Slides Unlock" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides usuwa ochronę, zanim napiszesz kod.
- Usuń hasło lub ochronę przed zapisem z pliku ODP.
- Pobierz odblokowany plik.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty odblokowywania" subTitle="Za pomocą Javy możesz usunąć ochronę także z następujących formatów." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/unlock/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
