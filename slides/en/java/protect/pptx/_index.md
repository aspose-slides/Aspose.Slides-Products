---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Protect PPTX Presentation Files using Java
url: /java/protect/pptx/
keywords: Write Protection PPTX, Encrypt a PPTX, Lock PPTX Presentation, Protect PPTX
description: Protect PPTX presentations in Java. Use Aspose.Slides for Java to encrypt presentation files and set write protection.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Lock or Password Protect PPTX using Java" h2="Build Java applications that protect presentation files using server-side APIs." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Protecting a PPTX Presentation via Java" variant="code" %}}

Using [Aspose.Slides for Java](/slides/java/), you can protect a PPTX presentation from opening or modification by setting a password. Use the `ProtectionManager` object from the `Presentation` class to call methods such as `encrypt` and `setWriteProtection`.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Encrypt a PPTX Presentation using Java" >}}
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
{{< blocks/products/pf/slides-design-update-10-2026/code title="Set Write Protection for a PPTX Presentation using Java" >}}
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

{{< blocks/products/pf/slides-design-update-10-2026/steps title="How to Password Protect PPTX via Java" intro="Follow these steps to protect a PPTX presentation." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Load the PPTX file with the `Presentation` class.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Call the `encrypt` method or the `setWriteProtection` method from the `ProtectionManager` object.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save the protected file with `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Other Supported Protection Formats" subTitle="Using Java, you can also protect the following formats." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/java/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
