---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Converter PPSM para EMF em Python
weight: 1780
url: /pt/python-net/conversion/ppsm-to-emf/ 
keywords: "Convert, PowerPoint, PPSM, EMF, Presentation, Python"
description: Código de exemplo para conversão de PPSM para EMF Python. Use a API Python do PowerPoint para arquivos PPSM de conversão em lote para arquivos EMF.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Converter PPSM para EMF em Python" h2="Poderosa biblioteca Python do PowerPoint para converter PPSM para EMF"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Converter PPSM para EMF em Python" %}}

Precisa converter arquivos PPSM para EMF programaticamente? Usando [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/pt/python-net/) qualquer desenvolvedor pode converter PPSM para o formato EMF com apenas algumas linhas de código Python.

Como uma API de processamento de apresentação moderna, o Aspose.Slides for Python cria EMF a partir do PPSM rapidamente. Teste a qualidade da conversão de PPSM para EMF diretamente no seu [navegador](https://products.aspose.app/slides/conversion). A biblioteca Aspose PowerPoint PPTX permite converter arquivos PPSM para muitos formatos populares.

Você pode instalar a biblioteca de [PyPI](https://pypi.org/project/Aspose.Slides/) usando o seguinte comando pip:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Console/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Salvar PPSM como EMF em Python" %}}

Use o aplicativo gratuito para ver uma demonstração do processo de conversão de PPSM para EMF.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Este código de amostra mostra a conversão de PPSM para EMF Python" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.ppsm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.emf".format(str(slide.slide_number)), drawing.imaging.ImageFormat.emf)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Como converter PPSM para EMF em Python" intro="Estas são as etapas para converter um arquivo PPSM em EMF usando Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Carregar arquivo PPSM com uma instância da classe Presentation{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Chame o método `save` enquanto especifica o caminho do arquivo de saída e SaveFormat.EMF como parâmetros{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}O arquivo PPSM será salvo no caminho especificado{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos de sistema" intro="Antes de executar o código-fonte da amostra de conversão do Python, verifique se você tem os seguintes pré-requisitos." %}}

- SO baseado em Microsoft Windows ou Linux (veja [mais](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 ou posterior
- Aspose.Slides para Python referenciado em seu projeto.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Criado com Aspose.Slides" title="Converter PPSM para EMF online" description="O aplicativo gratuito Aspose.Slides Conversion é criado com [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/pt/python-net/), a mesma API do código acima. Abra-o e veja o que a API pode fazer com seus próprios arquivos PPSM." button="Abrir Aspose.Slides Conversion" note="[Todos os aplicativos gratuitos](https://products.aspose.app/slides/family)" upload="Arraste ou envie seu arquivo" saveAs="Salvar como" convert="Converter" >}}
- Funciona no seu navegador, sem instalar nada.
- Veja como o Aspose.Slides converte arquivos antes de escrever código.
- Envie arquivos PPSM e salve-os como EMF.
- Baixe o resultado ou converta mais arquivos.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Outras conversões compatíveis" subTitle="Você também pode converter PPSM para muitos outros formatos de arquivo. Veja outras conversões compatíveis abaixo" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="Imagem em formato bitmap" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-fodp/" name="PPSM TO FODP" description="Apresentação XML Plana OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Formato de intercâmbio gráfico" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Linguagem de marcação de hipertexto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-jpg/" name="PPSM TO JPG" description="Imagem JPEG" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="Formato de apresentação do OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="Formato padrão do OpenDocument" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Formato de Documento Portátil" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-png/" name="PPSM TO PNG" description="Gráficos Portáteis de Rede" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Arquivo de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Arquivo de apresentação habilitado para macro" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Formato de apresentação XML aberto" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="Gráficos vetoriais escalonáveis" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Formato de imagem marcada" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/pt/python-net/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="Especificações do papel XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
