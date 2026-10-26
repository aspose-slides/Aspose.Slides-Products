---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Desbloquear arquivos de apresentação PPTX usando Java
url: /pt/java/unlock/pptx/
description: Remova senhas e proteção contra gravação de apresentações PPTX em Java com o Aspose.Slides for Java.
keywords: Remover proteção contra gravação PPTX, descriptografar PPTX, desbloquear apresentação PPTX, desproteger PPTX
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Desbloquear PPTX usando Java" h2="Crie aplicativos Java que removem senhas e proteção contra gravação de arquivos de apresentação com APIs do lado do servidor." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Remover a proteção de uma apresentação PPTX com Java" variant="code" %}}

Com o [Aspose.Slides for Java](/slides/pt/java/), você pode remover a criptografia ou a proteção contra gravação de uma apresentação PPTX. Use `LoadOptions.setPassword` para abrir uma apresentação criptografada e os métodos `removeEncryption` e `removeWriteProtection` do `ProtectionManager` para remover as configurações de proteção.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Remover a proteção por senha de PPTX usando Java" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.pptx", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Remover a proteção contra gravação de uma apresentação PPTX usando Java" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como remover a senha de PPTX com Java" intro="Siga estas etapas para remover a proteção de uma apresentação PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregue o arquivo PPTX com a classe `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use `LoadOptions.setPassword` quando a apresentação estiver criptografada.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame `removeEncryption` ou `removeWriteProtection` do objeto `ProtectionManager`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve a apresentação desbloqueada com `SaveFormat.Pptx`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Criado com Aspose.Slides" title="Desbloquear arquivos PPTX online" description="O aplicativo gratuito Aspose.Slides Unlock é criado com [Aspose.Slides for Java](https://products.aspose.com/slides/pt/java/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPTX." button="Abrir Aspose.Slides Unlock" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides remove a proteção antes de escrever código.
- Remova a senha ou a proteção contra gravação do seu arquivo PPTX.
- Baixe o arquivo desbloqueado.
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com desbloqueio" subTitle="Com Java, você também pode remover a proteção dos seguintes formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/java/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
