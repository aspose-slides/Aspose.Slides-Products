---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Wyświetlanie i edycja metadanych plików FODP w Javie
url: /pl/java/metadata/fodp/
description: Wyświetlaj i edytuj metadane FODP w Javie. Użyj Aspose.Slides for Java, aby aktualizować wbudowane i niestandardowe właściwości prezentacji.
keywords: edycja metadanych FODP, wyświetlanie metadanych FODP, edycja właściwości FODP, wyświetlanie właściwości FODP
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Edycja właściwości FODP w Javie" h2="Twórz aplikacje Java, które modyfikują wbudowane i niestandardowe właściwości plików prezentacji za pomocą serwerowych API." related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Modyfikacja właściwości FODP w Javie" variant="code" %}}

Dzięki [Aspose.Slides for Java](/slides/pl/java/) programiści mogą odczytywać i modyfikować wbudowane i niestandardowe właściwości prezentacji. Użyj metody `getDocumentProperties` obiektu `Presentation`, aby uzyskać obiekt `IDocumentProperties` pliku prezentacji.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Modyfikacja wbudowanych właściwości FODP – Java" >}}
```java
Presentation presentation = new Presentation("Presentation.fodp");
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.setAuthor("Aspose.Slides for Java");
    documentProperties.setTitle("Modifying Presentation Properties");
    documentProperties.setSubject("Aspose Subject");
    documentProperties.setComments("Aspose Description");
    documentProperties.setManager("Aspose Manager");

    presentation.save("DocProps.fodp", SaveFormat.Fodp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Dodawanie niestandardowych właściwości do FODP – Java" >}}
```java
Presentation presentation = new Presentation();
try {
    IDocumentProperties documentProperties = presentation.getDocumentProperties();

    documentProperties.set_Item("New Custom", 12);
    documentProperties.set_Item("My Name", "Aspose Metadata Editor");
    documentProperties.set_Item("Custom", 124);

    String customPropertyName = documentProperties.getCustomPropertyName(2);
    documentProperties.removeCustomProperty(customPropertyName);

    presentation.save("CustomDemo.fodp", SaveFormat.Fodp);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Jak wyświetlić lub edytować metadane FODP w Javie" intro="Wykonaj poniższe kroki, aby wyświetlić lub edytować metadane FODP." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wczytaj plik `FODP` za pomocą klasy `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Wywołaj metodę `getDocumentProperties`, aby pobrać obiekt `IDocumentProperties`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Odczytaj lub zaktualizuj wbudowane właściwości, takie jak `Author`, `Title`, `Subject` i `Comments`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Odczytuj i modyfikuj właściwości niestandardowe za pomocą `set_Item`, `getCustomPropertyName` i `removeCustomProperty`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/metadata-app label="Zbudowano z Aspose.Slides" title="Wyświetlaj i edytuj metadane FODP online" description="Bezpłatna aplikacja Aspose.Slides Metadata została zbudowana z użyciem [Aspose.Slides for Java](https://products.aspose.com/slides/pl/java/), tego samego API co w powyższym kodzie. Otwórz ją i zobacz, co API potrafi zrobić z Twoimi plikami FODP." button="Otwórz Aspose.Slides Metadata" note="[Wszystkie bezpłatne aplikacje](https://products.aspose.app/slides/family)" >}}
- Działa w przeglądarce, nie trzeba niczego instalować.
- Zobacz, jak Aspose.Slides odczytuje i zapisuje właściwości, zanim napiszesz kod.
- Wyświetlaj i edytuj wbudowane i niestandardowe właściwości pliku FODP.
- Zapisz i pobierz zaktualizowany plik.
{{< /blocks/products/pf/slides-design-update-10-2026/metadata-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Inne obsługiwane formaty metadanych" subTitle="W Javie możesz też zarządzać metadanymi następujących formatów." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pl/java/metadata/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
