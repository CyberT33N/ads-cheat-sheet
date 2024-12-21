# Ads Cheat Sheet






<br><br>




# Ads Definitions

<br><br>

## Video

<details><summary>Click to expand..</summary>

# Sample Tags
- https://developers.google.com/interactive-media-ads/docs/sdks/html5/client-side/tags








## Max amount of ads VAST
- https://pubads.g.doubleclick.net/gampad/ads?sz=640x480&iu=/124319096/external/ad_rule_samples&ciu_szs=300x250&ad_rule=1&impl=s&gdfp_req=1&env=vp&output=vmap&unviewed_position_start=1&cust_params=deployment%3Ddevsite%26sample_ar%3Dpremidpostpodbumper&cmsid=496&vid=short_onecue&correlator=
```xml
 <vmap:VMAP xmlns:vmap="http://www.iab.net/videosuite/vmap" version="1.0">
 <vmap:AdBreak timeOffset="start" breakType="linear" breakId="preroll">
  <vmap:AdSource id="preroll-ad-1" allowMultipleAds="false" followRedirects="true">
   <vmap:AdTagURI templateType="vast3"><![CDATA[https://pubads.g.doubleclick.net/gampad/ads?slotname=/124319096/external/ad_rule_samples&sz=640x480&ciu_szs=300x250&cust_params=deployment%3Ddevsite%26sample_ar%3Dpremidpostpodbumper&url=&unviewed_position_start=1&output=xml_vast3&impl=s&env=vp&gdfp_req=1&ad_rule=0&useragent=Mozilla/5.0+(X11%3B+Ubuntu%3B+Linux+x86_64%3B+rv:132.0)+Gecko/20100101+Firefox/132.0,gzip(gfe)&vad_type=linear&vpos=preroll&pod=1&ppos=1&lip=true&min_ad_duration=0&max_ad_duration=30000&vrid=6496&cmsid=496&video_doc_id=short_onecue&kfa=0&tfcd=0]]></vmap:AdTagURI>
  </vmap:AdSource>
 </vmap:AdBreak>
 <vmap:AdBreak timeOffset="start" breakType="linear" breakId="preroll">
  <vmap:AdSource id="preroll-post-bumper" allowMultipleAds="false" followRedirects="true">
   <vmap:AdTagURI templateType="vast3"><![CDATA[https://pubads.g.doubleclick.net/gampad/ads?slotname=/124319096/external/ad_rule_samples&sz=640x480&ciu_szs=300x250&cust_params=deployment%3Ddevsite%26sample_ar%3Dpremidpostpodbumper&url=&unviewed_position_start=1&output=xml_vast3&impl=s&env=vp&gdfp_req=1&ad_rule=0&useragent=Mozilla/5.0+(X11%3B+Ubuntu%3B+Linux+x86_64%3B+rv:132.0)+Gecko/20100101+Firefox/132.0,gzip(gfe)&vad_type=linear&vpos=preroll&pod=1&bumper=after&min_ad_duration=0&max_ad_duration=10000&vrid=6496&sb=1&cmsid=496&video_doc_id=short_onecue&kfa=0&tfcd=0]]></vmap:AdTagURI>
  </vmap:AdSource>
  <vmap:Extensions>
   <vmap:Extension type="bumper" suppress_bumper="true"/>
  </vmap:Extensions>
 </vmap:AdBreak>
 <vmap:AdBreak timeOffset="00:00:15.000" breakType="linear" breakId="midroll-1">
  <vmap:AdSource id="midroll-1-pre-bumper" allowMultipleAds="false" followRedirects="true">
   <vmap:AdTagURI templateType="vast3"><![CDATA[https://pubads.g.doubleclick.net/gampad/ads?slotname=/124319096/external/ad_rule_samples&sz=640x480&ciu_szs=300x250&cust_params=deployment%3Ddevsite%26sample_ar%3Dpremidpostpodbumper&url=&unviewed_position_start=1&output=xml_vast3&impl=s&env=vp&gdfp_req=1&ad_rule=0&cue=15000&useragent=Mozilla/5.0+(X11%3B+Ubuntu%3B+Linux+x86_64%3B+rv:132.0)+Gecko/20100101+Firefox/132.0,gzip(gfe)&vad_type=linear&vpos=midroll&pod=2&mridx=1&rmridx=1&bumper=before&min_ad_duration=0&max_ad_duration=10000&vrid=6496&sb=1&cmsid=496&video_doc_id=short_onecue&kfa=0&tfcd=0]]></vmap:AdTagURI>
  </vmap:AdSource>
  <vmap:Extensions>
   <vmap:Extension type="bumper" suppress_bumper="true"/>
  </vmap:Extensions>
 </vmap:AdBreak>
 <vmap:AdBreak timeOffset="00:00:15.000" breakType="linear" breakId="midroll-1">
  <vmap:AdSource id="midroll-1-ad-1" allowMultipleAds="false" followRedirects="true">
   <vmap:AdTagURI templateType="vast3"><![CDATA[https://pubads.g.doubleclick.net/gampad/ads?slotname=/124319096/external/ad_rule_samples&sz=640x480&ciu_szs=300x250&cust_params=deployment%3Ddevsite%26sample_ar%3Dpremidpostpodbumper&url=&unviewed_position_start=1&output=xml_vast3&impl=s&env=vp&gdfp_req=1&ad_rule=0&cue=15000&useragent=Mozilla/5.0+(X11%3B+Ubuntu%3B+Linux+x86_64%3B+rv:132.0)+Gecko/20100101+Firefox/132.0,gzip(gfe)&vad_type=linear&vpos=midroll&pod=2&mridx=1&rmridx=1&ppos=1&min_ad_duration=0&max_ad_duration=30000&vrid=6496&cmsid=496&video_doc_id=short_onecue&kfa=0&tfcd=0]]></vmap:AdTagURI>
  </vmap:AdSource>
 </vmap:AdBreak>
 <vmap:AdBreak timeOffset="00:00:15.000" breakType="linear" breakId="midroll-1">
  <vmap:AdSource id="midroll-1-ad-2" allowMultipleAds="false" followRedirects="true">
   <vmap:AdTagURI templateType="vast3"><![CDATA[https://pubads.g.doubleclick.net/gampad/ads?slotname=/124319096/external/ad_rule_samples&sz=640x480&ciu_szs=300x250&cust_params=deployment%3Ddevsite%26sample_ar%3Dpremidpostpodbumper&url=&unviewed_position_start=1&output=xml_vast3&impl=s&env=vp&gdfp_req=1&ad_rule=0&cue=15000&useragent=Mozilla/5.0+(X11%3B+Ubuntu%3B+Linux+x86_64%3B+rv:132.0)+Gecko/20100101+Firefox/132.0,gzip(gfe)&vad_type=linear&vpos=midroll&pod=2&mridx=1&rmridx=1&ppos=2&min_ad_duration=0&max_ad_duration=30000&vrid=6496&cmsid=496&video_doc_id=short_onecue&kfa=0&tfcd=0]]></vmap:AdTagURI>
  </vmap:AdSource>
 </vmap:AdBreak>
 <vmap:AdBreak timeOffset="00:00:15.000" breakType="linear" breakId="midroll-1">
  <vmap:AdSource id="midroll-1-ad-3" allowMultipleAds="false" followRedirects="true">
   <vmap:AdTagURI templateType="vast3"><![CDATA[https://pubads.g.doubleclick.net/gampad/ads?slotname=/124319096/external/ad_rule_samples&sz=640x480&ciu_szs=300x250&cust_params=deployment%3Ddevsite%26sample_ar%3Dpremidpostpodbumper&url=&unviewed_position_start=1&output=xml_vast3&impl=s&env=vp&gdfp_req=1&ad_rule=0&cue=15000&useragent=Mozilla/5.0+(X11%3B+Ubuntu%3B+Linux+x86_64%3B+rv:132.0)+Gecko/20100101+Firefox/132.0,gzip(gfe)&vad_type=linear&vpos=midroll&pod=2&mridx=1&rmridx=1&ppos=3&lip=true&min_ad_duration=0&max_ad_duration=30000&vrid=6496&cmsid=496&video_doc_id=short_onecue&kfa=0&tfcd=0]]></vmap:AdTagURI>
  </vmap:AdSource>
 </vmap:AdBreak>
 <vmap:AdBreak timeOffset="00:00:15.000" breakType="linear" breakId="midroll-1">
  <vmap:AdSource id="midroll-1-post-bumper" allowMultipleAds="false" followRedirects="true">
   <vmap:AdTagURI templateType="vast3"><![CDATA[https://pubads.g.doubleclick.net/gampad/ads?slotname=/124319096/external/ad_rule_samples&sz=640x480&ciu_szs=300x250&cust_params=deployment%3Ddevsite%26sample_ar%3Dpremidpostpodbumper&url=&unviewed_position_start=1&output=xml_vast3&impl=s&env=vp&gdfp_req=1&ad_rule=0&cue=15000&useragent=Mozilla/5.0+(X11%3B+Ubuntu%3B+Linux+x86_64%3B+rv:132.0)+Gecko/20100101+Firefox/132.0,gzip(gfe)&vad_type=linear&vpos=midroll&pod=2&mridx=1&rmridx=1&bumper=after&min_ad_duration=0&max_ad_duration=10000&vrid=6496&sb=1&cmsid=496&video_doc_id=short_onecue&kfa=0&tfcd=0]]></vmap:AdTagURI>
  </vmap:AdSource>
  <vmap:Extensions>
   <vmap:Extension type="bumper" suppress_bumper="true"/>
  </vmap:Extensions>
 </vmap:AdBreak>
 <vmap:AdBreak timeOffset="end" breakType="linear" breakId="postroll">
  <vmap:AdSource id="postroll-pre-bumper" allowMultipleAds="false" followRedirects="true">
   <vmap:AdTagURI templateType="vast3"><![CDATA[https://pubads.g.doubleclick.net/gampad/ads?slotname=/124319096/external/ad_rule_samples&sz=640x480&ciu_szs=300x250&cust_params=deployment%3Ddevsite%26sample_ar%3Dpremidpostpodbumper&url=&unviewed_position_start=1&output=xml_vast3&impl=s&env=vp&gdfp_req=1&ad_rule=0&useragent=Mozilla/5.0+(X11%3B+Ubuntu%3B+Linux+x86_64%3B+rv:132.0)+Gecko/20100101+Firefox/132.0,gzip(gfe)&vad_type=linear&vpos=postroll&pod=3&bumper=before&min_ad_duration=0&max_ad_duration=10000&vrid=6496&sb=1&cmsid=496&video_doc_id=short_onecue&kfa=0&tfcd=0]]></vmap:AdTagURI>
  </vmap:AdSource>
  <vmap:Extensions>
   <vmap:Extension type="bumper" suppress_bumper="true"/>
  </vmap:Extensions>
 </vmap:AdBreak>
 <vmap:AdBreak timeOffset="end" breakType="linear" breakId="postroll">
  <vmap:AdSource id="postroll-ad-1" allowMultipleAds="false" followRedirects="true">
   <vmap:AdTagURI templateType="vast3"><![CDATA[https://pubads.g.doubleclick.net/gampad/ads?slotname=/124319096/external/ad_rule_samples&sz=640x480&ciu_szs=300x250&cust_params=deployment%3Ddevsite%26sample_ar%3Dpremidpostpodbumper&url=&unviewed_position_start=1&output=xml_vast3&impl=s&env=vp&gdfp_req=1&ad_rule=0&useragent=Mozilla/5.0+(X11%3B+Ubuntu%3B+Linux+x86_64%3B+rv:132.0)+Gecko/20100101+Firefox/132.0,gzip(gfe)&vad_type=linear&vpos=postroll&pod=3&ppos=1&lip=true&min_ad_duration=0&max_ad_duration=30000&vrid=6496&cmsid=496&video_doc_id=short_onecue&kfa=0&tfcd=0]]></vmap:AdTagURI>
  </vmap:AdSource>
 </vmap:AdBreak>
</vmap:VMAP>
```









Hier ist eine Erklärung zu den Begriffen, die du genannt hast, inklusive ihrer Funktionen und Einsatzgebiete:

---

# **1. VAST (Video Ad Serving Template)**  
**Definition:**  
VAST ist ein standardisiertes Protokoll der IAB (Interactive Advertising Bureau), das die Kommunikation zwischen einem Video-Player und einem Ad-Server ermöglicht. Es definiert, wie Videoanzeigen (z. B. Pre-Rolls, Mid-Rolls) ausgeliefert und getrackt werden.  

**Anwendung:**  
- VAST-Dateien (XML-basiert) enthalten alle notwendigen Informationen für die Auslieferung einer Anzeige: Videodatei-URL, Tracking-Links (Impression, Klicks), Ad-Dauer und Kreativ-Metadaten.  
- Wird für **In-Stream Video Ads** wie Pre-Roll, Mid-Roll oder Post-Roll verwendet.

**Beispiel:**  
Ein Nutzer startet ein Video, und der Player lädt eine VAST-Ad von einem Werbenetzwerk. Diese Ad wird dann abgespielt, bevor der eigentliche Inhalt erscheint.


<br><br>

## Example Code (Video.js)
- https://github.com/CyberT33N/video.js-cheat-sheet/blob/main/README.md#example-code

<br><br>
<br><br>

## VAST 3.0 vs VAST 4.3

<details><summary>Click to expand..</summary>

Hier ist ein detaillierter Vergleich zwischen **VAST 3.0** und **VAST 4.3**, zwei Versionen des IAB-Standards, der für die Auslieferung und das Tracking von Videoanzeigen genutzt wird:

---

# **VAST 3.0** (2012)  
**Einführung:**  
VAST 3.0 wurde entwickelt, um einige Einschränkungen von VAST 2.0 zu beheben, insbesondere bei der Flexibilität und der Unterstützung moderner Videoplayer. Es war jahrelang der Standard für Videoanzeigen.  

#### **Hauptmerkmale:**  
1. **Skippable Ads:**  
   - Einführung von **„skip buttons“**: Es ermöglicht dem Nutzer, Anzeigen nach einer bestimmten Zeit zu überspringen.  
   - Ermöglicht das Tracking von Skippable-Ad-Events (z. B. „Ad skipped“).  

2. **Linear vs. Non-Linear Ads:**  
   - Verbesserte Unterstützung für **Linear (Video)** und **Non-Linear Ads** (z. B. Overlay-Anzeigen).

3. **Wrapper-Ads (Kaskadierende Anzeigen):**  
   - Unterstützt mehrere Wrapper-Ads. Ad-Server können zusätzliche Informationen hinzufügen und die Anzeige an nachgelagerte Server weiterleiten.  
   - Problem: Wrapper-Kaskaden können zu **langen Ladezeiten** führen.

4. **Companion Ads:**  
   - **Companion Ads** (z. B. Banner neben dem Video) sind besser integriert, um das Gesamterlebnis zu verbessern.  

5. **Tracking-Events:**  
   - Mehrere neue Tracking-Möglichkeiten für Ad-Impressionen und -Events: „Start“, „Complete“, „Pause“ usw.

## **Limitierungen:**  
- Keine Unterstützung für **serverseitige Ad-Insertion (SSAI)**.  
- Schlechte Performance bei **Multi-Screen**-Erfahrungen (Desktop vs. Mobile).  
- Wrapper-Ads können ineffizient sein und die Ladezeit der Anzeigen verlängern.

---

# **VAST 4.3** (2019)  
**Einführung:**  
VAST 4.3 ist die neueste und modernste Version des Standards, entwickelt, um die Anforderungen der heutigen programmatischen und Multi-Screen-Welt zu erfüllen. Sie behebt viele Schwächen älterer Versionen und bietet zusätzliche Funktionen für Effizienz und Transparenz.  

## **Hauptmerkmale:**  
1. **Unterstützung für serverseitige Ad-Insertion (SSAI):**  
   - SSAI ermöglicht die nahtlose Integration von Anzeigen in Videostreams auf Server-Ebene, was Ad-Blocker umgeht und Ladezeiten reduziert.  

2. **Ad Buffers & Readiness:**  
   - Ermöglicht die **vorzeitige Anzeigevorbereitung** (Preloading), um Verzögerungen zu reduzieren.  

3. **Verbesserte Wrapper-Ads:**  
   - Wrapper-Ads sind effizienter: Es gibt **Fallback-Mechanismen**, um Fehler in der Ad-Lieferung zu vermeiden.  
   - Reduzierte Kaskadierung, was Ladezeiten drastisch verringert.  

4. **UniversalAdId:**  
   - Einführung der **UniversalAdId**, die jeder Anzeige eine eindeutige Kennung zuweist. Dies verbessert die Nachverfolgbarkeit und die Transparenz für Werbetreibende.  

5. **Interaktivität & Mehrformat-Unterstützung:**  
   - **Unterstützung von neuen Formaten:** z. B. interaktive Anzeigen, 360°-Videos und VR-Content.  
   - Verbesserte **Mobile- und Connected-TV-Unterstützung.**  

6. **Verbessertes Tracking:**  
   - Erweiterte Tracking-Möglichkeiten, z. B. für feiner abgestimmte Viewability-Metriken.  
   - Unterstützt **Ad Verification Codes**, um Missbrauch und Invalid Traffic zu vermeiden.  

7. **Ad Pods (Anzeigegruppen):**  
   - Unterstützung für **Ad Pods**, also mehrere Anzeigen, die in einer definierten Reihenfolge ausgespielt werden können (z. B. ähnlich wie TV-Werbung).  

8. **Mezzanine-Dateien:**  
   - **Mezzanine-Dateien** (hochqualitative Videoquellen) können bereitgestellt werden, um automatisch herunterskalierte Varianten für verschiedene Geräte zu erstellen.  

## **Vorteile gegenüber 3.0:**  
- **Weniger Ad-Ladeprobleme:** Dank effizienterer Wrapper-Mechanismen.  
- **Bessere Transparenz:** Universelle IDs und bessere Tracking-Optionen.  
- **Mobile und TV optimiert:** Für die heutige, geräteübergreifende Nutzung.  
- **SSAI-Unterstützung:** Nahtlose und blockierungsresistente Ad-Insertion.

---

## **Vergleichstabelle: VAST 3.0 vs. 4.3**

| **Feature**                  | **VAST 3.0**                     | **VAST 4.3**                    |
|-------------------------------|-----------------------------------|----------------------------------|
| **Skippable Ads**             | Unterstützt                     | Unterstützt                    |
| **Wrapper-Effizienz**         | Ineffizient, kaskadierend        | Effizient, reduzierte Kaskaden  |
| **Serverseitige Ad-Insertion**| Nicht unterstützt               | Vollständig unterstützt         |
| **Tracking-Möglichkeiten**    | Grundlegendes Tracking          | Erweiterte Viewability-Metriken |
| **Interaktive Ads**           | Eingeschränkt                   | Voll unterstützt               |
| **Ad Pods**                   | Nicht unterstützt               | Unterstützt                    |
| **Multi-Screen-Unterstützung**| Eingeschränkt                   | Optimiert                      |
| **Ad Verification Codes**     | Nicht unterstützt               | Unterstützt                    |
| **Videoqualität (Mezzanine)** | Nicht unterstützt               | Unterstützt                    |

---

# **Fazit: Was solltest du verwenden?**

- **Für moderne Websites/Apps:** VAST **4.3** ist die klare Wahl, da es effizienter, flexibler und besser auf heutige Geräte und Anforderungen abgestimmt ist. Besonders, wenn du serverseitige Ad-Insertion, bessere Viewability-Messungen oder interaktive Formate möchtest.  
- **Wenn du auf ältere Systeme angewiesen bist:** VAST 3.0 funktioniert weiterhin, hat jedoch Performance-Einschränkungen und ist veraltet.  

Falls du planst, mit modernen Ad-Netzwerken oder programmatischen Plattformen zu arbeiten (z. B. Google Ad Manager, SpotX, FreeWheel), wirst du fast immer mit VAST 4.x arbeiten müssen.




<br><br>

## Autoplay



Ob ein **autoplay**-Video in Kombination mit VAST-Anzeigen (z. B. Pre-Roll) **für Monetarisierung zählt** (also ob Du Geld dafür bekommst), hängt von den folgenden Faktoren ab:

---

### **1. Viewability und User Interaction (IAB-Richtlinien)**
- Laut den **IAB-Richtlinien** (Interactive Advertising Bureau), die die Standards für digitale Anzeigen festlegen, muss eine Anzeige **sichtbar sein** und **eine gewisse User-Interaktion aufweisen**, um monetarisiert werden zu können.  
  - **Viewability**: Mindestens **50% der Anzeige muss für mindestens 2 Sekunden sichtbar** sein, damit sie zählt.
  - **User Interaction**: Viele Werbetreibende fordern, dass der Nutzer das Video aktiv startet (kein "Muted Autoplay").

---

### **2. Autoplay und Muted Videos**
Wenn Dein Player so konfiguriert ist, dass er ein Video automatisch abspielt:
- **Mit Ton**: Autoplay **kann monetarisiert werden**, wenn die Anzeige sichtbar bleibt und abgespielt wird.
- **Ohne Ton** (muted autoplay): Viele Ad-Server und Werbetreibende **blockieren die Monetarisierung** von Anzeigen, wenn das Video ohne Ton läuft, da dies als "Low Engagement" gilt.

---

### **3. Pre-Roll-Anzeigen bei Autoplay**
- **Ohne Nutzer-Interaktion (z. B. Klick)**:  
  Einige VAST-Ad-Systeme (wie Google Ad Manager) behandeln Anzeigen, die bei Autoplay ohne Nutzer-Interaktion starten, **nicht als validiert**, weil kein "Intent" vom Nutzer gezeigt wurde. In diesem Fall bekommst Du kein Geld.

- **Mit Nutzer-Interaktion (z. B. Klick oder Tap)**:  
  Wenn Du den Nutzer zwingst, zu interagieren (z. B. ein Klick oder Tap, um das Video abzuspielen), dann zählt die Anzeige und wird monetarisiert.

---

### **4. Autoplay in Kombination mit `requestAds()`**
Wenn Du mit `requestAds()` arbeitest:
- Die Anzeige wird erst angefordert, wenn die Methode explizit aufgerufen wird.  
- Falls Dein Autoplay-Video zu früh abgespielt wird, bevor die Anzeige geladen ist, könnte die Anzeige übersprungen werden und Du verlierst Monetarisierung.

Um sicherzugehen:
- Initialisiere `ima.requestAds()` korrekt **vor** dem Abspielen des Videos.
- Nutze eine Nutzer-Interaktion (z. B. ein Klick) für den ersten `play()`-Befehl.

---

### **Empfehlung für maximale Monetarisierung**
1. **Kein Autoplay bei der ersten Anzeige:**  
   Stelle sicher, dass die Pre-Roll-Werbung nur startet, nachdem der Nutzer das Video absichtlich gestartet hat.

2. **Viewability sicherstellen:**  
   Der Player muss sichtbar sein und darf nicht minimiert oder ausgeblendet werden.

3. **Fallback für muted autoplay:**  
   Wenn Dein Video muted autoplay nutzt, zeige einen Hinweis wie "Zum Starten klicken" und initialisiere die Anzeige erst, nachdem der Nutzer klickt.

---

### **Zusammenfassung**
Wenn Du **Autoplay** ohne Interaktion verwendest, könnten VAST-Anzeigen **nicht für die Monetarisierung zählen**, besonders wenn sie stumm abgespielt werden. Für sichere Einnahmen:
- Fordere eine Nutzer-Interaktion (z. B. Klick).
- Stelle sicher, dass die Anzeige sichtbar bleibt.
- Initialisiere `requestAds()` und das Abspielen erst nach einem Event.










 
</details>













---

### **2. Video Slider**  
**Definition:**  
Ein Video Slider ist ein **Bannerformat**, das ein Video als Anzeige verwendet und beim Scrollen der Webseite am unteren Bildschirmrand oder in einer Ecke erscheint.  

**Merkmale:**  
- **Interaktiv und unaufdringlich:** Es bleibt sichtbar, während der Nutzer scrollt, ohne den Content komplett zu blockieren.  
- **Position:** Meistens **sticky** am Rand (unten rechts/links).  
- Unterstützt sowohl automatische Wiedergabe (autoplay) als auch manuelles Abspielen.  

**Vorteil:**  
Es sorgt für eine hohe Sichtbarkeit (Viewability) bei gleichzeitig geringer Nutzerstörung, weshalb es bei Advertisern beliebt ist.

---

### **3. Outstream Video**  
**Definition:**  
Outstream Video Ads sind Videoanzeigen, die **außerhalb von klassischen Video-Content** erscheinen – z. B. in einem Artikeltext, zwischen Absätzen oder in einem Sidebar-Widget.

**Merkmale:**  
- **Kein eigener Videoinhalt nötig:** Sie sind unabhängig von Video-Content, was sie für Publisher ohne Videoplattform attraktiv macht.  
- **Autoplay bei Sichtbarkeit:** Die Videos starten automatisch, wenn sie im sichtbaren Bereich des Nutzers sind, und pausieren, wenn sie aus dem Bildschirm scrollen.  
- **Formate:** Native In-Text-Videos, Sticky Videos oder interaktive Ads.

**Vorteil:**  
Outstream-Ads monetarisieren Content-Webseiten, die keinen eigenen Videoplayer betreiben.

---

### **4. RTB In-Stream Video Supply**  
**Definition:**  
Real-Time Bidding (RTB) für **In-Stream Video Ads** bezieht sich auf die **programmatische Auktion von Videoanzeigen**, die in einem Video-Player abgespielt werden (z. B. Pre-Roll, Mid-Roll, Post-Roll).  

**Merkmale:**  
- **In-Stream:** Video-Ads erscheinen **innerhalb eines Videoinhalts**, wie auf YouTube oder anderen Video-Plattformen.  
- **Auktionsbasiert:** Advertiser bieten in Echtzeit auf Ad-Impressions basierend auf Zielgruppe, CPM und Ad-Performance.  
- **Beispiele:** YouTube Pre-Roll-Ads oder Videoanzeigen auf Streaming-Seiten.  

**Vorteil:**  
Hochwertige Werbeplätze, da In-Stream-Ads meist einen hohen View-Through-Rate (VTR) und starke Zielgruppentreffer haben.

---

### **5. RTB Video Slider Supply**  
**Definition:**  
Dies ist ein programmatisches Format, bei dem Videoanzeigen als **Slider Ads** ausgespielt werden, wobei der Ad-Inventar über **Real-Time Bidding (RTB)** gehandelt wird.  

**Merkmale:**  
- Slider erscheinen beim Scrollen und sind **sticky** positioniert (z. B. unten rechts auf der Seite).  
- **RTB-Auktion:** Werbetreibende bieten in Echtzeit auf diesen Werbeplatz basierend auf Nutzerverhalten und Segmentdaten.  

**Vorteil:**  
Es kombiniert die hohen Interaktionsraten eines Sliders mit der Effizienz des RTB-Systems.

---

### **6. RTB Outstream Video Supply**  
**Definition:**  
Programmatische Auktionen für **Outstream Video Ads**, die außerhalb von klassischen Videoinhalten geschaltet werden, z. B. zwischen Absätzen eines Artikels oder in Widgets.

**Merkmale:**  
- Video startet nur, wenn es im sichtbaren Bereich des Nutzers erscheint (Viewability-optimiert).  
- **RTB-Steuerung:** Ad-Inventar wird in Echtzeit über DSPs (Demand-Side Platforms) und SSPs (Supply-Side Platforms) gehandelt.  

**Vorteil:**  
Outstream ermöglicht es Publishern, Videoanzeigen auch ohne Videocontent zu monetarisieren, während Advertiser Nutzer in neuen Kontexten erreichen.

---

### **Zusammenfassung:**  
- **VAST:** Technisches Protokoll zur Auslieferung von Videoanzeigen.  
- **Video Slider:** Sticky Video-Ad, die während des Scrollens sichtbar bleibt.  
- **Outstream Video:** Videoanzeigen, die nicht an Video-Content gebunden sind (z. B. im Text oder Sidebar).  
- **RTB In-Stream Video Supply:** Auktionen für Anzeigen in einem Video-Player (klassische Video-Ads wie Pre-Rolls).  
- **RTB Video Slider Supply:** Auktionsbasiertes Handeln von Slider Video-Anzeigen.  
- **RTB Outstream Video Supply:** Echtzeit-Auktionen für Outstream Videoanzeigen auf Nicht-Video-Plattformen.

Alle Formate haben ihre eigene Stärke, je nachdem, ob du Video-Content besitzt oder einfach nur Werbeflächen auf deiner Website monetarisieren willst.

</details>


























<br><br>
<br><br>

<br><br>
<br><br>

## Types

<details><summary>Click to expand..</summary>
   
<br><br>
<br><br>


### **1. CPA (Cost Per Action)**  
- **What it is:**  
  **CPA** refers to the **Cost per Action** model, where advertisers pay only when a specific action is taken by a user. This could be a purchase, a form submission, or an email sign-up.  
- **Why it’s useful:**  
  CPA is often used when advertisers want to focus on actual conversions (actions) rather than just clicks or impressions. It’s particularly effective for performance-driven campaigns.
  
---

### **2. CPM (Cost Per Mille)**  
- **What it is:**  
  **CPM** stands for **Cost per Mille** (with "Mille" being Latin for thousand). In this model, advertisers pay a fixed amount for every 1,000 impressions (views) their ad receives, regardless of whether users click on it.  
- **Why it’s useful:**  
  CPM is great for branding and awareness campaigns where the goal is to reach a large number of people rather than generating immediate actions.

---

### **3. CPI (Cost Per Install)**  
- **What it is:**  
  **CPI** refers to **Cost per Install**, an advertising model where advertisers pay each time a user installs their app as a result of clicking on an ad.  
- **Why it’s useful:**  
  CPI is often used by mobile app developers to acquire new users. It focuses on generating installs, which is critical for app growth.

---

### **4. CPL (Cost Per Lead)**  
- **What it is:**  
  **CPL** stands for **Cost per Lead**. In this model, advertisers pay for each lead generated, which typically means a user expressing interest in a product or service, such as filling out a contact form or signing up for a newsletter.  
- **Why it’s useful:**  
  CPL is ideal for businesses that want to build a list of potential customers to follow up on, often used in B2B marketing, financial services, and other industries with longer sales cycles.

---

### **5. RTB (Real-Time Bidding)**  
- **What it is:**  
  **RTB** is an auction-based system where advertisers bid in real-time for ad space, typically through ad exchanges. The highest bidder gets their ad shown to the user.  
- **Why it’s useful:**  
  RTB allows for dynamic pricing based on user data and other factors, enabling more efficient use of advertising budgets. It’s widely used in display and video advertising.

---

### **6. CPC (Cost Per Click)**  
- **What it is:**  
  **CPC** refers to **Cost per Click**, where advertisers pay each time a user clicks on their ad.  
- **Why it’s useful:**  
  CPC is ideal when the goal is to drive traffic to a website or landing page, as it’s performance-based. It's popular in search engine advertising (e.g., Google Ads) and can be very effective for campaigns focused on direct response.

---

### Summary of the Models:
- **CPA:** Focuses on paying for specific actions like a sale or registration.
- **CPM:** Pays per 1,000 ad views or impressions.
- **CPI:** Pays when an app is installed.
- **CPL:** Pays for generating leads, like email sign-ups.
- **RTB:** Advertisers bid for impressions in real-time.
- **CPC:** Pays when a user clicks on an ad.

Each model has its strengths depending on your advertising goals—whether it’s awareness (CPM), engagement (CPC), conversion (CPA, CPL), or app installs (CPI).


</details>
































<br><br>
<br><br>
_________________________________
_________________________________
<br><br>
<br><br>



# Revenue Order

<details><summary>Click to expand..</summary>

Hier ist eine sortierte Liste mit den gängigsten Ad-Formaten und ihrer typischen Monetarisierungsleistung, sortiert nach den höchsten Einnahmen **pro Impression, View oder Klick** (je nach Format). Die Einnahmen können je nach Zielgruppe, Traffic-Qualität und Region stark variieren, aber das Ranking gibt dir eine allgemeine Orientierung:  

---

### **1. Pre-Roll Video Ads (In-Stream Video)**  
- **Was:** Videoanzeigen, die vor einem Videoinhalt abgespielt werden.  
- **Bezahlung:** CPM (Cost per Mille – pro 1.000 Aufrufe).  
- **Einnahmenpotenzial:** **$20–$50 CPM** (je nach Traffic und Zielgruppe, z. B. in den USA höher).  
- **Warum so hoch?**  
  - Hohe Engagement-Rate, da die Anzeige vor dem eigentlichen Content abgespielt wird.  
  - Hohe Viewability und VTR (View-Through-Rate).  
- **Bestes Einsatzgebiet:** Streaming-Websites, Videoplattformen wie YouTube.

---

### **2. Mid-Roll Video Ads (In-Stream Video)**  
- **Was:** Anzeigen, die in der Mitte eines Videoinhalts abgespielt werden.  
- **Bezahlung:** CPM.  
- **Einnahmenpotenzial:** **$15–$40 CPM**.  
- **Warum?**  
  - Noch höhere Engagement-Rate, da der Zuschauer mitten im Video ist und weniger schnell abspringt.  
- **Bestes Einsatzgebiet:** Längere Videos, z. B. Podcasts oder Tutorials.

---

### **3. Outstream Video Ads**  
- **Was:** Videoanzeigen, die in Textbereichen oder außerhalb eines Videoplayers erscheinen.  
- **Bezahlung:** CPM, oft Viewability-optimiert (z. B. nur gezählt, wenn die Anzeige wirklich im sichtbaren Bereich abgespielt wurde).  
- **Einnahmenpotenzial:** **$10–$30 CPM**.  
- **Warum?**  
  - Geringere Abhängigkeit von Videocontent.  
  - Hohe Viewability durch autoplay bei Sichtbarkeit.  
- **Bestes Einsatzgebiet:** Content-Websites mit wenig eigenem Video.

---

### **4. Interstitial Ads (Fullscreen Pop-Up Ads)**  
- **Was:** Vollbildanzeigen, die zwischen Seitenwechseln oder als Übergang geschaltet werden.  
- **Bezahlung:** CPC (Cost per Click) oder CPM.  
- **Einnahmenpotenzial:** **$5–$25 CPM oder $0.50–$5 CPC**.  
- **Warum?**  
  - Hohe Klick- und Conversion-Raten durch maximale Sichtbarkeit.  
  - Kann nervig wirken, deshalb sparsam einsetzen.  
- **Bestes Einsatzgebiet:** Mobile Apps oder Gaming-Websites.

---

### **5. Sticky Video Slider Ads**  
- **Was:** Videos, die beim Scrollen sticky am Rand sichtbar bleiben.  
- **Bezahlung:** CPM.  
- **Einnahmenpotenzial:** **$5–$20 CPM**.  
- **Warum?**  
  - Sichtbar während der gesamten User-Session.  
  - Perfekt für Content- oder News-Seiten.  

---

### **6. Banner Ads mit RTB (Programmatic Display Ads)**  
- **Was:** Klassische Displayanzeigen (728x90, 300x250 usw.), die über Real-Time Bidding gehandelt werden.  
- **Bezahlung:** CPM oder CPC.  
- **Einnahmenpotenzial:**  
  - **CPC:** $0.10–$1 pro Klick.  
  - **CPM:** **$1–$10**, abhängig von der Qualität und Nische des Traffics.  
- **Warum?**  
  - Leicht einzubauen, aber niedrige Engagement-Rate, da Banner oft ignoriert werden (Banner-Blindness).  

---

### **7. Native Ads (Empfohlene Inhalte, Content-Werbung)**  
- **Was:** Anzeigen, die aussehen wie empfohlene Inhalte oder Teil des Website-Designs sind (z. B. „Weitere Artikel lesen“).  
- **Bezahlung:** CPC.  
- **Einnahmenpotenzial:** **$0.10–$5 CPC**.  
- **Warum?**  
  - Wird oft geklickt, da es wie ein regulärer Inhalt aussieht.  
  - Aber Klicks können zu geringeren Conversion-Raten führen.  

---

### **8. Affiliate Marketing (z. B. Amazon-Links)**  
- **Was:** Provisionen für Verkäufe, die durch Klicks auf Partnerlinks entstehen.  
- **Bezahlung:** Prozentsatz des Verkaufswerts.  
- **Einnahmenpotenzial:**  
  - **2–10 %** pro Verkauf.  
  - Kann sehr lukrativ sein, wenn die Zielgruppe kauffreudig ist.  
- **Warum?**  
  - Direkte Monetarisierung, kein Ad-Blocker-Problem.  

---

### **Zusammenfassung – Monetarisierungspotenzial (absteigend):**

1. **Pre-Roll Video Ads (In-Stream)**: $20–$50 CPM  
2. **Mid-Roll Video Ads (In-Stream)**: $15–$40 CPM  
3. **Outstream Video Ads**: $10–$30 CPM  
4. **Interstitial Ads (Fullscreen Pop-Ups)**: $5–$25 CPM oder $0.50–$5 CPC  
5. **Sticky Video Slider Ads**: $5–$20 CPM  
6. **Banner Ads (RTB)**: $1–$10 CPM oder $0.10–$1 CPC  
7. **Native Ads**: $0.10–$5 CPC  
8. **Affiliate Marketing**: Variabel (2–10 % Provision pro Sale)  

---

### **Empfehlung für maximale Einnahmen:**  
- **Videocontent erstellen:** Fokus auf **Pre-Roll** und **Mid-Roll Video Ads**, da diese die höchsten CPMs bieten.  
- **Outstream-Ads einbauen**, wenn du keine eigenen Videos hast.  
- Zusätzliche Einnahmen durch Sticky Sliders und Affiliate-Links maximieren.  

Hast du bestimmte Traffic-Quellen oder eine Zielgruppe im Kopf? Damit können wir deine Strategie noch weiter verfeinern! 😊

</details>


































<br><br>
<br><br>
_________________________________
_________________________________
<br><br>
<br><br>


# Ratings CPM - Companies
- https://www.adspyglass.com/best-ad-networks





<br><br>

# Banner

<br><br>

## Adult

<br><br>

### USA


| **Ad Network**       | **Ads Types**      | **Min Payout** | **Frequency**              | **Payment Systems**   | **CPM for the USA** |
|-----------------------|--------------------|----------------|----------------------------|-----------------------|---------------------|
| **AdSpyglass**        | Popunders          | $10            | Bi-weekly                 | Multiple options      | $0.24              |
| **AdsTerra**          | Popunders          | $5             | Bi-weekly                 | Multiple options      | $0.24              |
| **Adnium**            | Popunders          | $100           | On request                | Multiple options      | $0.06              |
| **Evadav**            | Popunders          | $25            | Weekly                    | Multiple options      | $0.04              |
| **TrafficForce**      | Popunders          | $100           | Weekly                    | Multiple options      | $0.03              |
| **ExoClick**          | Popunders          | $20            | Weekly                    | Multiple options      | $0.02              |
| **HilltopAds**        | Popunders          | $10            | Weekly                    | Multiple options      | $0.02              |
| **TrafficStars**      | Popunders          | $100           | Weekly                    | Multiple options      | $0.01              |
| **TwinRed**           | Popunders          | $50            | Monthly                   | Multiple options      | $0.01              |
| **Clickadu**          | Popunders          | $10            | Weekly, Bi-weekly, Monthly| Multiple options      | $0.01              |
| **Kadam**             | Popunders          | $15            | Weekly                    | Multiple options      | $0.01              |
| **ClickAdilla**       | Popunders          | $50            | On request                | Multiple options      | $0.00              |
| **Ero-Advertising**   | Popunders          | €10            | Weekly                    | Multiple options      | $0.00              |
| **TrafficShop**       | Popunders          | $50            | On request                | Multiple options      | $0.00              |
| **Clickaine**         | Popunders          | $50            | On request                | Multiple options      | $0.00              |
| **Media Modern DSP**  | Popunders          | -              | Daily                     | Multiple options      | -                  |

Let me know if you’d like any further refinements!









<br><br>
<br><br>

# VAST

<br><br>

## Adult

<br><br>

### USA


| **Ad Network**      | **Ads Types**      | **Min Payout** | **Frequency**             | **Payment Systems** | **CPM for the USA** |
|----------------------|--------------------|----------------|---------------------------|----------------------|---------------------|
| **AdSpyglass**       | Popunders          | $10            | Bi-weekly                | Multiple options     | $1.23              |
| **HilltopAds**       | Popunders          | $10            | Weekly                   | Multiple options     | $1.23              |
| **TrafficStars**     | Popunders          | $100           | Weekly                   | Multiple options     | $0.59              |
| **TwinRed**          | Popunders          | $50            | Monthly                  | Multiple options     | $0.58              |
| **ClickAdilla**      | Popunders          | $50            | On request               | Multiple options     | $0.47              |
| **ExoClick**         | Popunders          | $20            | Weekly                   | Multiple options     | $0.39              |
| **Tubecorporate**    | Popunders          | $50            | Bi-weekly                | Multiple options     | $0.22              |
| **BuyMedia.biz**     | Popunders          | $8             | On request               | Multiple options     | $0.16              |
| **Rivertraffic**     | Popunders          | $100           | Bi-weekly                | Multiple options     | $0.13              |
| **Adnium**           | Popunders          | $100           | On request               | Multiple options     | $0.10              |
| **Clickadu**         | Popunders          | $10            | Weekly, Bi-weekly, Monthly | Multiple options  | $0.09              |
| **Clickaine**        | Popunders          | $50            | On request               | Multiple options     | $0.03              |

Let me know if there’s anything more you’d like to adjust!





<br><br>
<br><br>

# POPUNDER

## Adult

### USA

| **Ad Network**     | **Ads Types**      | **Min Payout** | **Frequency**             | **Payment Systems** | **CPM for the USA** |
|---------------------|--------------------|----------------|---------------------------|----------------------|---------------------|
| **AdSpyglass**      | Popunders          | $10            | Bi-weekly                | Multiple options     | $2.34              |
| **AdsTerra**        | Popunders          | $5             | Bi-weekly                | Multiple options     | $2.34              |
| **TrafficShop**     | Popunders          | $50            | On request               | Multiple options     | $1.52              |
| **JuicyAds**        | Popunders          | $25            | On request               | Multiple options     | $1.45              |
| **TwinRed**         | Popunders          | $50            | Monthly                  | Multiple options     | $1.34              |
| **Evadav**          | Popunders          | $25            | Weekly                   | Multiple options     | $1.21              |
| **HilltopAds**      | Popunders          | $10            | Weekly                   | Multiple options     | $1.11              |
| **TrafficStars**    | Popunders          | $100           | Weekly                   | Multiple options     | $1.08              |
| **ExoClick**        | Popunders          | $20            | Weekly                   | Multiple options     | $1.06              |
| **Clickadu**        | Popunders          | $10            | Weekly, Bi-weekly, Monthly | Multiple options  | $0.68              |
| **PopCash**         | Popunders          | $10            | On request               | Multiple options     | $0.67              |
| **TrafficOX**       | Popunders          | $10            | Weekly                   | Multiple options     | $0.60              |
| **ClickAdilla**     | Popunders          | $50            | On request               | Multiple options     | $0.57              |
| **Rivertraffic**    | Popunders          | $100           | Bi-weekly                | Multiple options     | $0.56              |
| **Kadam**           | Popunders          | $15            | Weekly                   | Multiple options     | $0.53              |
| **Plugrush**        | Popunders          | $25            | On request               | Multiple options     | $0.46              |
| **Clickaine**       | Popunders          | $50            | On request               | Multiple options     | $0.43              |
| **Tubecorporate**   | Popunders          | $50            | Bi-weekly                | Multiple options     | $0.12              |
| **TrafficForce**    | Popunders          | $100           | Weekly                   | Multiple options     | $0.06              |
| **Adnium**          | Popunders          | $100           | On request               | Multiple options     | $0.06              |
| **Popunder DSP**    | Popunders          | $10            | Weekly                   | Multiple options     | Data not provided  |

Let me know if you’d like me to add more details or tweak the formatting!






















<br><br>
<br><br>
_________________________________
_________________________________
<br><br>
<br><br>

# Traffic Blocking Guide



Lass uns die Optionen, warum du sie blockieren solltest (oder nicht), im Detail analysieren. Ziel ist, die Traffic-Qualität zu optimieren, um bessere Monetarisierung zu gewährleisten. Gleichzeitig solltest du echten Traffic nicht verlieren.  

---

### **1. Block returned traffic**  
**Definition:** Verhindert wiederholte Zugriffe von demselben Nutzer in kurzer Zeit.  
- **Warum blockieren?**  
  - Wiederholter Traffic bringt oft keine Monetarisierung. Ad Networks erkennen, dass derselbe Nutzer keine neuen Anzeigen sieht, und zahlen weniger.
  - Schützt vor Bots, die eine Seite wiederholt aufrufen.  
- **Warum nicht blockieren?**  
  - Wiederkehrende Besucher können echte Nutzer sein (z. B. Stammkunden).  
  - Bei Seiten mit hohem Engagement, wie Foren oder Blogs, könnten echte Nutzer blockiert werden.  
- **Empfehlung:** Blockieren, wenn dein Traffic-Volumen stark von Bots geprägt ist. Testweise blockieren und die Einnahmen überwachen.  

---

### **2. Block noref traffic**  
**Definition:** Blockiert Traffic ohne Referrer-Daten (z. B. direkt eingegebene URLs oder aus unbekannten Quellen).  
- **Warum blockieren?**  
  - Referrer-Daten sind ein Indikator für legitime Besucher.  
  - Traffic ohne Referrer kommt oft von Bots, Spam oder unseriösen Quellen, die keine Einnahmen bringen.  
- **Warum nicht blockieren?**  
  - Viele echte Nutzer (z. B. aus Social Media Apps oder privaten Links) könnten blockiert werden.  
  - Mobile Geräte schicken manchmal keine Referrer-Daten (besonders iOS).  
- **Empfehlung:** Blockieren, wenn dein Ad Network spezifisch Referrer verlangt. Ansonsten vorsichtig sein, besonders bei mobilen Nutzern.

---

### **3. Block nocookie traffic**  
**Definition:** Blockiert Nutzer, die keine Cookies akzeptieren (z. B. wegen Browser-Einstellungen oder Adblockern).  
- **Warum blockieren?**  
  - Ad Networks brauchen Cookies für Targeting, Tracking und Optimierung. Ohne Cookies sinkt die CPM.  
  - Nutzer mit deaktivierten Cookies könnten Bots sein.  
- **Warum nicht blockieren?**  
  - Datenschutzgesetze (wie DSGVO) haben zu einem Anstieg von Cookie-freundlichem Traffic geführt. Das Blockieren könnte legalen EU-Traffic ausschließen.  
  - Mobile Nutzer oder Browser mit hohen Datenschutzstandards könnten ebenfalls ausgeschlossen werden.  
- **Empfehlung:** Blockiere, wenn dein Traffic nicht stark aus der EU kommt und du auf Targeting angewiesen bist. Testweise blockieren und Ergebnisse beobachten.  

---

### **4. Block WebView traffic**  
**Definition:** Blockiert Traffic aus WebViews (z. B. In-App-Browser von Facebook, Instagram, Telegram, etc.).  
- **Warum blockieren?**  
  - WebViews werden oft von Bots missbraucht.  
  - CPM-Werte für WebView-Traffic sind niedrig, da Ad Networks oft keine präzisen Daten aus WebViews sammeln können.  
- **Warum nicht blockieren?**  
  - Viele Nutzer greifen von sozialen Netzwerken auf Inhalte zu. Dieser Traffic könnte echt sein, aber schlechter monetarisiert werden.  
- **Empfehlung:** Blockiere WebViews, wenn der Großteil deines Traffics nicht von sozialen Netzwerken kommt.

---

### **5. Block nonunique traffic**  
**Definition:** Blockiert Traffic von Nutzern, die wiederholt dieselbe Seite besuchen, ohne einzigartig zu sein (z. B. durch IPs).  
- **Warum blockieren?**  
  - Ad Networks erkennen wiederholten Traffic und senken die Vergütung.  
  - Bots oder automatisierte Klicks erzeugen non-unique Traffic.  
- **Warum nicht blockieren?**  
  - Echte Besucher, die regelmäßig dieselbe Seite aufrufen, könnten fälschlicherweise ausgeschlossen werden.  
- **Empfehlung:** Blockieren, wenn du merkst, dass der Großteil deines Traffics Bots sind.  

---

### **6. Block search engine crawlers**  
**Definition:** Verhindert Zugriffe von Suchmaschinen-Bots wie Google, Bing, etc.  
- **Warum blockieren?**  
  - Suchmaschinen-Crawler klicken keine Anzeigen und bringen keinen Umsatz.  
  - Sie können deinen Server belasten, besonders bei hohem Traffic-Volumen.  
- **Warum nicht blockieren?**  
  - Crawler sind wichtig für SEO und die Indexierung deiner Seite. Ohne sie könnte deine Seite weniger sichtbar sein.  
- **Empfehlung:** Blockiere sie nur in Ad-Placements (nicht auf der ganzen Seite). AdSpyglass hat Optionen, um Crawler vom Ad-Bereich fernzuhalten.

---

### **7. Block proxy types (VPN, Tor, Proxies)**  
**Definition:** Blockiert Traffic über VPNs, Tor-Netzwerke, oder Proxies.  
- **Warum blockieren?**  
  - Proxy-Traffic wird oft von Bots oder illegitimem Traffic genutzt.  
  - Ad Networks stufen VPN-Traffic häufig als minderwertig ein, wodurch CPM-Werte sinken.  
- **Warum nicht blockieren?**  
  - Echte Nutzer (z. B. in Ländern mit Zensur oder hohen Datenschutzanforderungen) verwenden oft VPNs.  
  - Ein zu aggressives Blockieren könnte Traffic aus legitimen Ländern ausschließen.  
- **Empfehlung:** Blockiere verdächtige Proxy-Typen (z. B. Tor oder öffentliche Proxies). Whiteliste vertrauenswürdige VPNs, wenn möglich.

---

### **8. Direct/Non Proxy**  
**Definition:** Blockiert Traffic ohne Proxy oder VPN.  
- **Warum blockieren?**  
  - Hier gibt es keinen klaren Grund zum Blockieren. Echte Nutzer greifen direkt zu.  
- **Warum nicht blockieren?**  
  - Du würdest normalen Traffic verlieren.  
- **Empfehlung:** Niemals blockieren. Echte Nutzer kommen oft direkt.  

---

### **Fazit: Was solltest du blockieren?**
1. **Immer blockieren:**  
   - WebView-Traffic  
   - Search Engine Crawlers  
   - Offensichtliche Proxy-Typen (z. B. Tor, öffentliche Proxies)  

2. **Optional blockieren:**  
   - NoRef Traffic  
   - NoCookie Traffic  
   - NonUnique Traffic  

3. **Nicht blockieren:**  
   - Direct/Non Proxy Traffic  
   - Echte VPN-Nutzer (nach Überprüfung).  

**Strategie:** Blockiere schrittweise und überprüfe deine CPM und Einnahmen. Ziel ist, die Qualität des Traffics zu verbessern, ohne legitime Besucher auszuschließen.

































<br><br>
<br><br>
_________________________________
_________________________________
<br><br>
<br><br>

# Ad Networks

<details><summary>Click to expand..</summary>





# Manager
- Analyse all your ad companies where you are publisher

## adspyglass






<br><br>
<br><br>



# Advertiser

<details><summary>Click to expand..</summary>


# Traffic Junky

<br><br>

# push.house

<br><br>

# onclicka

<br><br>


# trafficfactory

</details>









<br><br>
<br><br>



# Embed Publisher

<details><summary>Click to expand..</summary>

# tubecorporate

</details>
















<br><br>
<br><br>



# Publisher

<details><summary>Click to expand..</summary>

# twinred **HOT** [ADULT]
- [Adult Ads] -  Yes
- [Verify Time] - 1 Business day
- [POPUNDER] - Yes
- [BANNER] - Yes
- [VAST] - Yes

<br><br>
<br><br>

# bidvertiser
- [Verify Time] - 1 Business day
- [Adult Ads] - nO

<br><br>
<br><br>

# trafficstars
- [Verify Time] - 1 Business day
- [Adult Ads] - Yes

<br><br>
<br><br>

# clickadilla **HOT**
- [Adult Ads] - Yes
- [Verify Level]
  - Easy (Mainstream Content with Adult Ads)
  - Easy (Adult Content)
- [Verify Time] - INSTANT
- [POPUNDER] - Yes
- [BANNER] - Yes
- [VAST] - Yes
  
<br><br>
<br><br>

# adnium
- [Verify Time] - 1 Business day

  
<br><br>
<br><br>


# kadam
- [Verify Time] - 1 Business day

<br><br>
<br><br>

# plugrush
- [Verify Level]
  - Easy (Mainstream Content with Adult Ads)
  - Easy (Adult Content)
- [Adult Ads] -  Yes
- [Verify Time] - Instant
- [POPUNDER] - Yes
- [BANNER] - Yes
- [VAST] - No

<br><br>
<br><br>


# reacheffect
- [Adult Ads] -  Yes
- [Verify Time] - 24 hours
- [POPUNDER] - Yes
- [BANNER] - Yes
- [VAST] - Yes




<br><br>


<br><br>
<br><br>

# HilltopAds
- [Verify Level]
  - Easy (Mainstream Content with Adult Ads)
  - Easy (Adult Content)
- [Adult Ads] - Yes
- [Verify Time] - Instant
- [POPUNDER] - Yes
- [BANNER] - Yes
- [VAST] - Yes


<br><br>
<br><br>

# JuicyAds
- [Verify Level]
  - Hard (Mainstream Content with Adult Ads)
  - Easy (Adult Content)
- [Adult Ads] - Yes
- [Verify Time] - 24 hours
- [POPUNDER] - Yes
- [BANNER] - Yes
- [VAST] - NO
  
<br><br>
<br><br>

# exoclick
- **Make sure to use subdomain e.g. https://www.example.com/**
- **Once you verified an website you can not remove it and add again. You are only able to archieve it or change the website genre**

- [Verify Level]
  - Easy (Mainstream Content)
  - HARD (Mainstream Content with Adult Ads)
    - **Your website can not be under construction and must provide working content that the review team can work with**
  - Easy (Adult Content)
- [Adult Ads] - Yes
- [Verify Time] - 24 hours
- [VAST] - Yes
- [POPUNDER] - Yes
- [BANNER] - Yes

<br><br>

# Mondiad
- [Verify Level]
  - Easy (Mainstream Content with Adult Ads)
  - Easy (Adult Content)
- [Adult Ads] - Yes
- [Verify Time] - Instant
- [POPUNDER] - No
- [BANNER] - Yes
- [VAST] - NO



<br><br>

# ad-maven
- [Verify Level]
  - Easy (Mainstream Content with Adult Ads)
  - Easy (Adult Content)
- [Adult Ads] - Yes
- [Verify Time] - Instant
- [POPUNDER] - Yes
- [BANNER] - Yes
- [VAST] - NO


<br><br>

# Popads **HOT**
- [Verify Level]
  - Easy (Mainstream Content with Adult Ads)
  - Easy (Adult Content)
- [Verify Time] - 2-3 Dys
- [Adult Ads] - Yes
- [POPUNDER] - Yes
- [BANNER] - No
- [VAST] - NO

I verified my website with:
- https://www.example.com

And I used this Domain Advanced DNS Settings:
```
# This is for root domain example.com
Type: CNAME Record
Host: wwww
Value: your digital ocean app link
TTL: automatic

# This is for sub domain www.example.com
Type: ALIAS Record
Host: @
Value: your digital ocean app link
TTL: automatic
```



  
<br><br>
  
# Popcash
- [Verify Level]
  - Easy (Mainstream Content with Adult Ads)
  - Easy (Adult Content)
- [Verify Time] - Minutes
- [Adult Ads on mainstream site] - Yes
- [Adult Ads] - Yes
- [POPUNDER] - Yes
- [BANNER] - No
- [VAST] - NO

<br><br>

# Adsterra
- [Verify Level]
  - Easy (Mainstream Content with Adult Ads)
  - Easy (Adult Content)
- [Verify Time] - Instant
- [Adult Ads on mainstream site] - Yes
- [Adult Ads] - Yes
- [POPUNDER] - Yes
- [BANNER] - Yes
- [VAST] - NO

</details>

</details>
