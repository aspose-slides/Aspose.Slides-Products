---
title: Converter POTM para JPG em Python
weight: 1160
url: /pt/python-net/conversion/potm-to-jpg/ 
keywords: "Convert, PowerPoint, POTM, JPG, Presentation, Python"
description: Código de exemplo para conversão de POTM para JPG Python. Use a API Python do PowerPoint para arquivos POTM de conversão em lote para arquivos JPG.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter POTM para JPG em Python" h2="Poderosa biblioteca Python do PowerPoint para converter POTM para JPG" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="SVG" fileiconsmall5="PPT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/python-net/" installationsDocsLink="https://docs.aspose.com/slides/python-net/installation/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/python-net" learnAsLink="https://docs.aspose.com/slides/python-net/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Converter POTM para JPG em Python" %}}

Precisa converter arquivos POTM para JPG programaticamente? Usando o [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/pt/python-net/) qualquer desenvolvedor pode converter o formato POTM para JPG com apenas algumas linhas de código Python.

Como uma API de processamento de apresentação moderna, o Aspose.Slides for Python cria JPG a partir do POTM rapidamente. Teste a qualidade da conversão de POTM para JPG diretamente no seu [navegador](https://products.aspose.app/slides/conversion/ppt-to-jpg). A biblioteca Aspose PowerPoint PPTX permite converter arquivos POTM para muitos formatos populares.

Você pode instalar a biblioteca de [PyPI](https://pypi.org/project/Aspose.Slides/) usando o seguinte comando pip:

{{% blocks/products/pf/agp/code-block title="Console/Terminal" offSpacer="true" %}}

```console
> pip install aspose.slides

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/agp/feature-section-col title="Como converter POTM para JPG em Python" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Estas são as etapas para converter um arquivo POTM em JPG usando Python." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Carregar arquivo POTM com uma instância da classe Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chame o método `save` enquanto especifica o caminho do arquivo de saída e SaveFormat.JPG como parâmetros
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
O arquivo POTM será salvo no caminho especificado
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código-fonte da amostra de conversão do Python, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- SO baseado em Microsoft Windows ou Linux (veja [mais](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 ou posterior
- Aspose.Slides para Python referenciado em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de amostra mostra a conversão de POTM para JPG Python" offSpacer="" %}}

```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.potm") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.jpg".format(str(slide.slide_number)), drawing.imaging.ImageFormat.jpeg)

```
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 
{{% blocks/products/pf/agp/content h2="Salvar POTM como JPG em Python" %}}
Use o aplicativo gratuito para ver uma demonstração do processo de conversão de POTM para JPG. 
{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Aplicativo gratuito para converter POTM para JPG" 
        sectionDescription="[Experimente nosso aplicativo gratuito para converter PPT para JPG](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Você também pode converter POTM para muitos outros formatos de arquivo. Veja outras conversões compatíveis abaixo" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-bmp/" name="POTM TO BMP" description="Imagem em formato bitmap" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-emf/" name="POTM TO EMF" description="Formato de metarquivo aprimorado" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-fodp/" name="POTM TO FODP" description="Apresentação XML Plana OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-gif/" name="POTM TO GIF" description="Formato de intercâmbio gráfico" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-html/" name="POTM TO HTML" description="Linguagem de marcação de hipertexto" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-odp/" name="POTM TO ODP" description="Formato de apresentação do OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-otp/" name="POTM TO OTP" description="Formato padrão do OpenDocument" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-pdf/" name="POTM TO PDF" description="Formato de Documento Portátil" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-png/" name="POTM TO PNG" description="Gráficos Portáteis de Rede" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-pot/" name="POTM TO POT" description="Arquivos de modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-potx/" name="POTM TO POTX" description="Apresentação do modelo do Microsoft PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-pps/" name="POTM TO PPS" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Apresentação de slides habilitada para macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="Apresentação de slides do PowerPoint" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Arquivo de apresentação habilitado para macro" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Formato de apresentação XML aberto" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-svg/" name="POTM TO SVG" description="Gráficos vetoriais escalonáveis" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-swf/" name="POTM TO SWF" description="Formato SWF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Formato de imagem marcada" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/pt/python-net/conversion/potm-to-xps/" name="POTM TO XPS" description="Especificações do papel XML" >}}  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}