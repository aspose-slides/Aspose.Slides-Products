---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Konvertieren Sie OTP in Python in PNG
weight: 530
url: /de/python-net/conversion/otp-to-png/ 
keywords: "Convert, PowerPoint, OTP, PNG, Presentation, Python"
description: Beispielcode für die OTP-zu-PNG-Python-Konvertierung. Verwenden Sie die PowerPoint-Python-API für die Stapelkonvertierung von OTP-Dateien in PNG-Dateien.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Konvertieren Sie OTP in Python in PNG" h2="Leistungsstarke PowerPoint-Python-Bibliothek zum Konvertieren von OTP in PNG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/python-net"
  learnLink="https://docs.aspose.com/slides/python-net/"
  pricingLink="https://purchase.aspose.com/pricing/slides/python-net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Konvertieren Sie OTP in Python in PNG" %}}

Müssen Sie OTP-Dateien programmgesteuert in PNG konvertieren? Mit [*Aspose.Slides for Python via .NET*](https://products.aspose.com/slides/de/python-net/) kann jeder Entwickler OTP mit nur wenigen Zeilen Python-Code in das PNG-Format konvertieren.

Als moderne Präsentationsverarbeitungs-API erstellt Aspose.Slides für Python schnell PNG aus OTP. Testen Sie die Qualität der Konvertierung von OTP in PNG direkt in Ihrem [Browser](https://products.aspose.app/slides/conversion). Mit der Aspose PowerPoint PPTX-Bibliothek können Sie OTP-Dateien in viele gängige Formate konvertieren.

Sie können die Bibliothek von [PyPI](https://pypi.org/project/Aspose.Slides/) mit dem folgenden Pip-Befehl installieren:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Konsole/Terminal" >}}
```console
> pip install aspose.slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Speichern Sie OTP als PNG in Python" %}}

Verwenden Sie die kostenlose App, um eine Demonstration des OTP-zu-PNG-Konvertierungsprozesses zu sehen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="Dieser Beispielcode zeigt die OTP-zu-PNG-Python-Konvertierung" >}}
```py

import aspose.slides as slides
import aspose.pydrawing as drawing

with slides.Presentation("presentation.otp") as presentation:
    for slide in presentation.slides:
        slide.get_thumbnail(2, 2).save("presentation_slide_{0}.png".format(str(slide.slide_number)), drawing.imaging.ImageFormat.png)

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="So konvertieren Sie OTP in PNG in Python" intro="Dies sind die Schritte zum Konvertieren einer OTP-Datei in PNG mit Python." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die OTP-Datei mit einer Instanz der Präsentationsklasse{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Rufen Sie die Methode „save“ auf, während Sie den Pfad der Ausgabedatei und SaveFormat.PNG als Parameter angeben{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Die OTP-Datei wird unter dem angegebenen Pfad gespeichert{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="System Anforderungen" intro="Stellen Sie vor dem Ausführen des Beispielquellcodes für die Python-Konvertierung sicher, dass die folgenden Voraussetzungen erfüllt sind." %}}

- Microsoft Windows- oder Linux-basiertes Betriebssystem (siehe [mehr](https://docs.aspose.com/slides/python-net/system-requirements/)).
- Python 3.5 oder höher
- Aspose.Slides für Python, auf die in Ihrem Projekt verwiesen wird.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Entwickelt mit Aspose.Slides" title="OTP online in PNG konvertieren" description="Die kostenlose App Aspose.Slides Conversion basiert auf [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/de/python-net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen OTP-Dateien leisten kann." button="Aspose.Slides Conversion öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" upload="Datei ablegen oder hochladen" saveAs="Speichern als" convert="Konvertieren" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Dateien konvertiert, bevor Sie Code schreiben.
- Laden Sie OTP-Dateien hoch und speichern Sie sie als PNG.
- Laden Sie das Ergebnis herunter oder konvertieren Sie weitere Dateien.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Andere unterstützte Konvertierungen" subTitle="Sie können OTP auch in viele andere Dateiformate konvertieren. Weitere unterstützte Konvertierungen finden Sie weiter unten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-bmp/" name="OTP TO BMP" description="Bitmap-Bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-emf/" name="OTP TO EMF" description="Verbessertes Metafile-Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-fodp/" name="OTP TO FODP" description="OpenDocument Flat XML-Präsentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-gif/" name="OTP TO GIF" description="Grafisches Austauschformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-html/" name="OTP TO HTML" description="Hypertext-Auszeichnungssprache" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-jpg/" name="OTP TO JPG" description="JPEG-Bild" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-odp/" name="OTP TO ODP" description="OpenDocument-Präsentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-pdf/" name="OTP TO PDF" description="Portables Dokumentenformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-pot/" name="OTP TO POT" description="Microsoft PowerPoint-Vorlagendateien" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-potm/" name="OTP TO POTM" description="Microsoft PowerPoint-Vorlagendatei" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-potx/" name="OTP TO POTX" description="Microsoft PowerPoint-Vorlagenpräsentation" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-pps/" name="OTP TO PPS" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="Makrofähige Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="PowerPoint-Diashow" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-ppt/" name="OTP TO PPT" description="Microsoft PowerPoint 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-pptm/" name="OTP TO PPTM" description="Makrofähige Präsentationsdatei" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-pptx/" name="OTP TO PPTX" description="Offenes XML-Präsentationsformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-svg/" name="OTP TO SVG" description="Skalierbare Vektorgrafiken" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-swf/" name="OTP TO SWF" description="SWF-Format" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-tiff/" name="OTP TO TIFF" description="Markiertes Bildformat" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/python-net/conversion/otp-to-xps/" name="OTP TO XPS" description="XML-Papierspezifikationen" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
