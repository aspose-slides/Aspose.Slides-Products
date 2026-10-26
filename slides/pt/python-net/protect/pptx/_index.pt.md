---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Proteger arquivos de apresentação PPTX com Python
url: /pt/python-net/protect/pptx/
description: Criptografe apresentações PPTX ou defina proteção contra gravação com Python.
keywords: proteção contra gravação PPTX, criptografar PPTX com Python, bloquear apresentação PPTX, proteger PPTX com Python
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Proteger apresentações PPTX com Python" h2="Crie aplicativos Python que criptografam apresentações ou definem proteção contra gravação com o Aspose.Slides." related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Proteger uma apresentação PPTX com Python" variant="code" %}}

O [**Aspose.Slides for Python via .NET**](/slides/pt/python-net/) oferece dois mecanismos de proteção distintos. Chame `ProtectionManager.encrypt` para criptografar uma apresentação PPTX e exigir uma senha para abri-la. Como alternativa, chame `ProtectionManager.set_write_protection` para desencorajar modificações sem criptografar o arquivo. O usuário ainda pode abrir uma apresentação protegida contra gravação e salvar as alterações em outro arquivo.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Criptografar uma apresentação PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.encrypt("123123")
    presentation.save("encrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Definir proteção contra gravação em uma apresentação PPTX – Python" >}}
```python
with slides.Presentation("presentation.pptx") as presentation:
    presentation.protection_manager.set_write_protection("123123")
    presentation.save("write-protected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como proteger PPTX com Python" intro="Siga estas etapas para proteger um arquivo PPTX." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Abra o arquivo PPTX com `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Use `ProtectionManager.encrypt` para exigir uma senha na abertura ou `ProtectionManager.set_write_protection` para desencorajar alterações.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Salve a apresentação protegida como PPTX com `SaveFormat.PPTX`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Criado com Aspose.Slides" title="Proteger arquivos PPTX com senha online" description="O aplicativo gratuito Aspose.Slides Lock é criado com [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pt/python-net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPTX." button="Abrir Aspose.Slides Lock" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides protege apresentações antes de escrever código.
- Defina uma senha para abrir ou editar seu arquivo PPTX.
- Baixe o arquivo protegido.
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outros formatos compatíveis com proteção" subTitle="Use Python para proteger outros formatos de apresentação compatíveis." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/pt/python-net/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
