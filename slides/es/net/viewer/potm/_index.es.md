---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Ver POTM en C#
keywords: Ver POTM, Abrir POTM, Visor de POTM, POTM, PowerPoint, API de C#, Biblioteca .NET
weight: 3310
url: /es/net/viewer/potm/ 
description: Vea archivos POTM en C#. Use Aspose.Slides for .NET para abrir archivos de presentación y guardarlos como HTML.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Ver POTM en C#" h2="API de C# para abrir archivos POTM y guardarlos como HTML adaptable."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Ver POTM con Aspose.Slides" %}}

Para ver archivos POTM, use la API [Aspose.Slides for .NET](https://products.aspose.com/slides/es/net/), una API para C# potente, completa y fácil de usar. Abra el administrador de paquetes [NuGet](https://www.nuget.org/packages/aspose.slides.net), busque **Aspose.Slides** e instálelo. También puede ejecutar el siguiente comando en la Consola del Administrador de paquetes.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Comando de la Consola del Administrador de paquetes" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

Con [**Aspose.Slides for .NET**](/slides/es/net/), puede cargar un archivo POTM y guardarlo como HTML adaptable con unas pocas líneas de código.

{{< blocks/products/pf/slides-design-update-10-2026/code title="Código C# para ver POTM" >}}
```cs
using var presentation = new Presentation("presentation.potm");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Cómo ver POTM en C#" intro="Aspose.Slides permite a los desarrolladores ver archivos POTM con solo unas pocas líneas de código." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Instale **Aspose.Slides for .NET**. Consulte [**Instalación**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Agregue la biblioteca como referencia en su proyecto.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cargue el archivo `POTM` con la clase `Presentation`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cree un objeto `ResponsiveHtmlController` para obtener una salida HTML adaptable.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Cree un objeto `HtmlOptions` y establezca la propiedad `HtmlFormatter`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Guarde el archivo POTM como HTML con `SaveFormat.Html`.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Requisitos del sistema" intro="Aspose.Slides for .NET es compatible con los principales sistemas operativos. Asegúrese de cumplir los siguientes requisitos previos." %}}

- Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Windows Azure, Mono o Xamarin
- Un entorno de desarrollo como Microsoft Visual Studio
- Una referencia a Aspose.Slides for .NET en su proyecto

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Creado con Aspose.Slides" title="Vea archivos POTM en línea" description="La aplicación gratuita Aspose.Slides Viewer está creada con [Aspose.Slides for .NET](https://products.aspose.com/slides/es/net/), la misma API que el código anterior. Ábrala y descubra lo que la API puede hacer con sus propios archivos POTM." button="Abrir Aspose.Slides Viewer" note="[Todas las aplicaciones gratuitas](https://products.aspose.app/slides/family)" >}}
- Funciona en su navegador, sin instalar nada.
- Vea cómo Aspose.Slides representa sus archivos antes de escribir código.
- Cargue su archivo POTM y vea sus diapositivas al instante.
- Funciona en ordenadores y móviles, sin necesidad de PowerPoint.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="POTM" readMoreLink="https://docs.fileformat.com/presentation/potm/" %}}

Los archivos con la extensión `.POTM` son plantillas de Microsoft PowerPoint compatibles con macros, introducidas con PowerPoint 2007. Pueden almacenar configuraciones de presentación reutilizables, como diseños, estilos, fondos, paletas de colores, fuentes, formato predeterminado y macros de VBA. PowerPoint 2007 y versiones posteriores pueden abrir y editar archivos POTM.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Ver otros archivos" subTitle="También puede abrir y ver presentaciones en otros formatos." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/viewer/odp/" name="ODP" description="Presentación OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/viewer/otp/" name="OTP" description="Plantilla de presentación OpenDocument" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/viewer/pot/" name="POT" description="Plantilla de PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/viewer/potx/" name="POTX" description="Plantilla de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/viewer/pps/" name="PPS" description="Presentación con diapositivas de PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/viewer/ppsm/" name="PPSM" description="Presentación con diapositivas de PowerPoint habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/viewer/ppsx/" name="PPSX" description="Presentación con diapositivas de PowerPoint" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/viewer/ppt/" name="PPT" description="Presentación de PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/viewer/pptm/" name="PPTM" description="Presentación de PowerPoint habilitada para macros" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/es/net/viewer/pptx/" name="PPTX" description="Presentación de PowerPoint" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
