---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie PDF in PPSM in Python
weight: 800
url: /de/python-net/conversion/pdf-to-ppsm/ 
keywords: "Convert, PowerPoint, PDF, PPSM, Presentation, Python"
description: Beispielcode für die PDF-zu-PPSM-Python-Konvertierung. Verwenden Sie die PowerPoint-Python-API für die Stapelkonvertierung von PDF-Dateien in PPSM-Dateien.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie PDF in PPSM in Python" h2="Leistungsstarke PowerPoint-Python-Bibliothek zum Konvertieren von PDF in PPSM"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie PDF in PPSM in Python" %}}

Müssen Sie PDF-Dateien programmgesteuert in PPSM konvertieren? Mit [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/de/python-net/) kann jeder Entwickler mit nur wenigen Zeilen Python-Code PDF in das PPSM-Format konvertieren.

Als moderne Präsentationsverarbeitungs-API erstellt Aspose.Slides für Python schnell PPSM aus PDF. Testen Sie die Qualität der Konvertierung von PDF in PPSM direkt in Ihrem [Browser](https://products.aspose.app/slides/conversion). Mit der Aspose PowerPoint PPTX-Bibliothek können Sie PDF-Dateien in viele gängige Formate konvertieren.

Sie können die Bibliothek von [PyPI](https://pypi.org/project/Aspose.Slides/) mit dem folgenden Pip-Befehl installieren:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsole/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PDF als PPSM in Python speichern" %}}

Verwenden Sie die kostenlose App, um eine Demonstration des PDF-zu-PPSM-Konvertierungsprozesses zu sehen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Dieser Beispielcode zeigt die PDF-zu-PPSM-Python-Konvertierung" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation() as presentation:
    presentation.slides.remove_at(0)
    presentation.slides.add_from_pdf("document.pdf")
    presentation.save("presentation.ppsm", slides.export.SaveFormat.PPSM)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie PDF in PPSM in Python" intro="Dies sind die Schritte zum Konvertieren einer PDF-Datei in PPSM mit Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie eine PDF-Datei mit einer Instanz der Presentation-Klasse{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Methode „save“ auf, während Sie den Pfad der Ausgabedatei und SaveFormat.PPSM als Parameter angeben{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Die PDF-Datei wird unter dem angegebenen Pfad gespeichert{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Anforderungen" intro="Stellen Sie vor dem Ausführen des Beispielquellcodes für die Python-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind." %}}

- Microsoft Windows- oder Linux-basiertes Betriebssystem (siehe [mehr](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 oder höher
- Aspose.Slides für Python, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Entwickelt mit Aspose.Slides" title="PDF online in PPSM konvertieren" description="Die kostenlose App Aspose.Slides Conversion basiert auf [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PDF-Dateien leisten kann." button="Aspose.Slides Conversion öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" upload="Datei ablegen oder hochladen" saveAs="Speichern als" convert="Konvertieren" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Dateien konvertiert, bevor Sie Code schreiben.
- Laden Sie PDF-Dateien hoch und speichern Sie sie als PPSM.
- Laden Sie das Ergebnis herunter oder konvertieren Sie weitere Dateien.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Konvertierungen" subTitle="Sie können PDF auch in viele andere Dateiformate konvertieren. Weitere unterstützte Konvertierungen finden Sie weiter unten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-bmp/" name="PDF TO BMP" description="Bitmap-Bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-emf/" name="PDF TO EMF" description="Verbessertes Metafile-Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-fodp/" name="PDF TO FODP" description="OpenDocument Flat XML-Präsentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-gif/" name="PDF TO GIF" description="Grafisches Austauschformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-html/" name="PDF TO HTML" description="Hypertext-Auszeichnungssprache" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-jpg/" name="PDF TO JPG" description="JPEG-Bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-odp/" name="PDF TO ODP" description="OpenDocument-Präsentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-otp/" name="PDF TO OTP" description="OpenDocument-Standardformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-png/" name="PDF TO PNG" description="Portable Netzwerkgrafiken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-pot/" name="PDF TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-potm/" name="PDF TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-potx/" name="PDF TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-pps/" name="PDF TO PPS" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-ppsx/" name="PDF TO PPSX" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-ppt/" name="PDF TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-pptm/" name="PDF TO PPTM" description="Makrofähige Präsentationsdatei" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-pptx/" name="PDF TO PPTX" description="Offenes XML-Präsentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-svg/" name="PDF TO SVG" description="Skalierbare Vektorgrafiken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-swf/" name="PDF TO SWF" description="SWF-Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-tiff/" name="PDF TO TIFF" description="Markiertes Bildformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/pdf-to-xps/" name="PDF TO XPS" description="XML-Papierspezifikationen" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
