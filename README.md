[![Banners](docs/images/banner1.png)](https://github.com/xinnan-tech/xiaozhi-esp32-server)

<h1 align="center">Xiaozhi Backend-Service xiaozhi-esp32-server</h1>

<p align="center">
Dieses Projekt basiert auf der Theorie und Technologie der symbiotischen Mensch-Maschine-Intelligenz und entwickelt ein intelligentes Terminal-Software- und Hardware-System<br/>
Es stellt Backend-Dienste für das Open-Source-Intelligent-Hardware-Projekt bereit
<a href="https://github.com/78/xiaozhi-esp32">xiaozhi-esp32</a><br/>
Implementiert mit Python, Java und Vue gemäß dem <a href="https://ccnphfhqs21z.feishu.cn/wiki/M0XiwldO9iJwHikpXD5cEx71nKh">Xiaozhi-Kommunikationsprotokoll</a><br/>
Unterstützt MQTT+UDP-Protokoll, Websocket-Protokoll, MCP-Zugriffspunkte und Sprecherkennung
</p>

<p align="center">
<a href="./README_en.md">English</a>
· <a href="./docs/FAQ.md">Häufig gestellte Fragen</a>
· <a href="https://github.com/xinnan-tech/xiaozhi-esp32-server/issues">Probleme melden</a>
· <a href="./README.md#bereitstellungsdokumentation">Bereitstellungsdokumentation</a>
· <a href="https://github.com/xinnan-tech/xiaozhi-esp32-server/releases">Änderungsprotokoll</a>
</p>
<p align="center">
  <a href="https://github.com/xinnan-tech/xiaozhi-esp32-server/releases">
    <img alt="GitHub Contributors" src="https://img.shields.io/github/v/release/xinnan-tech/xiaozhi-esp32-server?logo=docker" />
  </a>
  <a href="https://github.com/xinnan-tech/xiaozhi-esp32-server/graphs/contributors">
    <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/xinnan-tech/xiaozhi-esp32-server?logo=github" />
  </a>
  <a href="https://github.com/xinnan-tech/xiaozhi-esp32-server/issues">
    <img alt="Issues" src="https://img.shields.io/github/issues/xinnan-tech/xiaozhi-esp32-server?color=0088ff" />
  </a>
  <a href="https://github.com/xinnan-tech/xiaozhi-esp32-server/pulls">
    <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/xinnan-tech/xiaozhi-esp32-server?color=0088ff" />
  </a>
  <a href="https://github.com/xinnan-tech/xiaozhi-esp32-server/blob/main/LICENSE">
    <img alt="GitHub pull requests" src="https://img.shields.io/badge/license-MIT-white?labelColor=black" />
  </a>
  <a href="https://github.com/xinnan-tech/xiaozhi-esp32-server">
    <img alt="stars" src="https://img.shields.io/github/stars/xinnan-tech/xiaozhi-esp32-server?color=ffcb47&labelColor=black" />
  </a>
</p>

<p align="center">
Geleitet vom Team von Professor Siyuan Liu (South China University of Technology)
</br>
刘思源教授团队主导研发(华南理工大学)
</br>
<img src="./docs/images/hnlg.jpg" alt="华南理工大学" width="50%">
</p>

---

## Zielgruppe 👥

Dieses Projekt muss in Verbindung mit ESP32-Hardwaregeräten verwendet werden. Wenn Sie bereits ESP32-bezogene Hardware erworben haben und erfolgreich mit dem von Xiage bereitgestellten Backend-Service verbunden haben und nun Ihren eigenen unabhängigen `xiaozhi-esp32`-Backend-Service aufbauen möchten, ist dieses Projekt perfekt für Sie geeignet.

Möchten Sie die Nutzungseffekte sehen? Bitte schauen Sie sich die Videos an 🎥

<table>
  <tr>
    <td>
        <a href="https://www.bilibili.com/video/BV1FMFyejExX" target="_blank">
         <picture>
           <img alt="Reaktionsgeschwindigkeit erleben" src="docs/images/demo9.png" />
         </picture>
        </a>
    </td>
    <td>
        <a href="https://www.bilibili.com/video/BV1vchQzaEse" target="_blank">
         <picture>
           <img alt="Geheimnis der Geschwindigkeitsoptimierung" src="docs/images/demo6.png" />
         </picture>
        </a>
    </td>
    <td>
        <a href="https://www.bilibili.com/video/BV1C1tCzUEZh" target="_blank">
         <picture>
           <img alt="Komplexe medizinische Szenarien" src="docs/images/demo1.png" />
         </picture>
        </a>
    </td>
    <td>
        <a href="https://www.bilibili.com/video/BV1zUW5zJEkq" target="_blank">
         <picture>
           <img alt="MQTT-Befehlsausgabe" src="docs/images/demo4.png" />
         </picture>
        </a>
    </td>
    <td>
        <a href="https://www.bilibili.com/video/BV1Exu3zqEDe" target="_blank">
         <picture>
           <img alt="Sprecherkennung" src="docs/images/demo14.png" />
         </picture>
        </a>
    </td>
  </tr>
  <tr>
    <td>
        <a href="https://www.bilibili.com/video/BV1pNXWYGEx1" target="_blank">
         <picture>
           <img alt="Haushaltsgeräte steuern" src="docs/images/demo5.png" />
         </picture>
        </a>
    </td>
    <td>
        <a href="https://www.bilibili.com/video/BV1ZQKUzYExM" target="_blank">
         <picture>
           <img alt="MCP-Zugriffspunkt" src="docs/images/demo13.png" />
         </picture>
        </a>
    </td>
    <td>
      <a href="https://www.bilibili.com/video/BV1TJ7WzzEo6" target="_blank">
         <picture>
           <img alt="Multi-Befehls-Aufgaben" src="docs/images/demo11.png" />
         </picture>
        </a>
    </td>
    <td>
        <a href="https://www.bilibili.com/video/BV1VC96Y5EMH" target="_blank">
         <picture>
           <img alt="Musik abspielen" src="docs/images/demo7.png" />
         </picture>
        </a>
    </td>
    <td>
        <a href="https://www.bilibili.com/video/BV1Z8XuYZEAS" target="_blank">
         <picture>
           <img alt="Wetter-Plugin" src="docs/images/demo8.png" />
         </picture>
        </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://www.bilibili.com/video/BV12J7WzBEaH" target="_blank">
         <picture>
           <img alt="Echtzeit-Unterbrechung" src="docs/images/demo10.png" />
         </picture>
        </a>
    </td>
    <td>
      <a href="https://www.bilibili.com/video/BV1Co76z7EvK" target="_blank">
         <picture>
           <img alt="Objekte fotografieren" src="docs/images/demo12.png" />
         </picture>
        </a>
    </td>
    <td>
        <a href="https://www.bilibili.com/video/BV1CDKWemEU6" target="_blank">
         <picture>
           <img alt="Benutzerdefinierte Stimme" src="docs/images/demo2.png" />
         </picture>
        </a>
    </td>
    <td>
        <a href="https://www.bilibili.com/video/BV12yA2egEaC" target="_blank">
         <picture>
           <img alt="Kommunikation auf Kantonesisch" src="docs/images/demo3.png" />
         </picture>
        </a>
    </td>
    <td>
        <a href="https://www.bilibili.com/video/BV17LXWYvENb" target="_blank">
         <picture>
           <img alt="Nachrichten vorlesen" src="docs/images/demo0.png" />
         </picture>
        </a>
    </td>
  </tr>
</table>

---

## Warnung ⚠️

1. Dieses Projekt ist Open-Source-Software. Diese Software hat keine kommerzielle Kooperationsbeziehung mit verbundenen Drittanbieter-API-Diensten (einschließlich, aber nicht beschränkt auf Spracherkennung, große Modelle, Sprachsynthese und andere Plattformen) und bietet keine Garantie für deren Servicequalität und finanzielle Sicherheit.
Es wird empfohlen, dass Benutzer vorrangig Dienstanbieter mit entsprechenden Geschäftslizenzen wählen und deren Servicevereinbarungen und Datenschutzrichtlinien sorgfältig lesen. Diese Software hostet keine Kontoschlüssel, nimmt nicht an Geldtransfers teil und übernimmt keine Risiken für Verluste von aufgeladenen Geldern.

2. Die Funktionen dieses Projekts sind nicht vollständig und haben keine Netzwerksicherheitsbewertung bestanden. Bitte verwenden Sie es nicht in einer Produktionsumgebung. Wenn Sie dieses Projekt in einer öffentlichen Netzwerkumgebung zu Lernzwecken bereitstellen, stellen Sie bitte sicher, dass Sie die erforderlichen Schutzmaßnahmen ergreifen.

---

## Bereitstellungsdokumentation

![Banners](docs/images/banner2.png)

Dieses Projekt bietet zwei Bereitstellungsmethoden. Bitte wählen Sie entsprechend Ihren spezifischen Anforderungen:

#### 🚀 Auswahl der Bereitstellungsmethode
| Bereitstellungsmethode | Merkmale | Anwendungsszenarien | Bereitstellungsdokumentation | Konfigurationsanforderungen | Video-Tutorial |
|---------|------|---------|---------|---------|---------|
| **Minimale Installation** | Intelligente Dialoge, IOT, MCP, visuelle Wahrnehmung | Umgebungen mit niedriger Konfiguration, Datenspeicherung in Konfigurationsdateien, keine Datenbank erforderlich | [①Docker-Version](./docs/Deployment.md#%E6%96%B9%E5%BC%8F%E4%B8%80docker%E5%8F%AA%E8%BF%90%E8%A1%8Cserver) / [②Quellcode-Bereitstellung](./docs/Deployment.md#%E6%96%B9%E5%BC%8F%E4%BA%8C%E6%9C%AC%E5%9C%B0%E6%BA%90%E7%A0%81%E5%8F%AA%E8%BF%90%E8%A1%8Cserver)| Bei Verwendung von `FunASR` 2 Kerne 4G, bei vollständiger API 2 Kerne 2G | - |
| **Vollständige Modulinstallation** | Intelligente Dialoge, IOT, MCP-Zugriffspunkte, Sprecherkennung, visuelle Wahrnehmung, OTA, intelligente Konsole | Vollständige Funktionserfahrung, Datenspeicherung in Datenbank |[①Docker-Version](./docs/Deployment_all.md#%E6%96%B9%E5%BC%8F%E4%B8%80docker%E8%BF%90%E8%A1%8C%E5%85%A8%E6%A8%A1%E5%9D%97) / [②Quellcode-Bereitstellung](./docs/Deployment_all.md#%E6%96%B9%E5%BC%8F%E4%BA%8C%E6%9C%AC%E5%9C%B0%E6%BA%90%E7%A0%81%E8%BF%90%E8%A1%8C%E5%85%A8%E6%A8%A1%E5%9D%97) / [③Quellcode-Bereitstellung Auto-Update-Tutorial](./docs/dev-ops-integration.md) | Bei Verwendung von `FunASR` 4 Kerne 8G, bei vollständiger API 2 Kerne 4G| [Tutorial für lokalen Quellcode-Start](https://www.bilibili.com/video/BV1wBJhz4Ewe) |

Häufig gestellte Fragen und verwandte Tutorials finden Sie unter [diesem Link](./docs/FAQ.md)

> 💡 Tipp: Im Folgenden finden Sie die Testplattform, die nach dem neuesten Code bereitgestellt wurde. Bei Bedarf können Sie sie zum Testen flashen. Die Gleichzeitigkeit beträgt 6, die Daten werden täglich gelöscht.

```
Intelligente Konsolenadresse: https://2662r3426b.vicp.fun
Intelligente Konsole (h5-Version): https://2662r3426b.vicp.fun/h5/index.html

Service-Testtool: https://2662r3426b.vicp.fun/test/
OTA-Schnittstelle: https://2662r3426b.vicp.fun/xiaozhi/ota/
Websocket-Schnittstelle: wss://2662r3426b.vicp.fun/xiaozhi/v1/
```

#### 🚩 Konfigurationsbeschreibung und Empfehlungen
> [!Note]
> Dieses Projekt bietet zwei Konfigurationsschemata:
>
> 1. `Einstieg - komplett kostenlos` Konfiguration: Geeignet für den persönlichen und häuslichen Gebrauch, alle Komponenten verwenden kostenlose Lösungen, keine zusätzlichen Gebühren erforderlich.
>
> 2. `Streaming-Konfiguration`: Geeignet für Demos, Schulungen, mehr als 2 gleichzeitige Zugriffe usw., verwendet Streaming-Verarbeitungstechnologie, schnellere Reaktionsgeschwindigkeit, bessere Erfahrung.
>
> Ab Version `0.5.2` unterstützt das Projekt Streaming-Konfiguration. Im Vergleich zu früheren Versionen verbessert sich die Reaktionsgeschwindigkeit um etwa `2,5 Sekunden`, was die Benutzererfahrung erheblich verbessert.

| Modulname | Einstieg - komplett kostenlos | Streaming-Konfiguration |
|:---:|:---:|:---:|
| ASR(Spracherkennung) | FunASR(lokal) | 👍FunASR(lokaler GPU-Modus) |
| LLM(Großes Modell) | ChatGLMLLM(Zhipu glm-4-flash) | 👍AliLLM(qwen3-235b-a22b-instruct-2507) oder 👍DoubaoLLM(doubao-1-5-pro-32k-250115) |
| VLLM(Visuelles großes Modell) | ChatGLMVLLM(Zhipu glm-4v-flash) | 👍QwenVLVLM(Qwen qwen2.5-vl-3b-instructh) |
| TTS(Sprachsynthese) | ✅LinkeraiTTS(Lingxi-Streaming) | 👍HuoshanDoubleStreamTTS(Huoshan-Dual-Stream-Sprachsynthese) oder 👍AliyunStreamTTS(Aliyun-Streaming-Sprachsynthese) |
| Intent(Absichtserkennung) | function_call(Funktionsaufruf) | function_call(Funktionsaufruf) |
| Memory(Speicherfunktion) | mem_local_short(lokales Kurzzeitgedächtnis) | mem_local_short(lokales Kurzzeitgedächtnis) |

Wenn Sie sich um die Zeit der einzelnen Komponenten kümmern, lesen Sie bitte den [Xiaozhi-Komponenten-Leistungstest-Bericht](https://github.com/xinnan-tech/xiaozhi-performance-research). Sie können die Testmethode im Bericht in Ihrer eigenen Umgebung tatsächlich testen.

#### 🔧 Testwerkzeuge
Dieses Projekt bietet die folgenden Testwerkzeuge, um Ihnen bei der Überprüfung des Systems und der Auswahl geeigneter Modelle zu helfen:

| Werkzeugname | Standort | Verwendungsmethode | Funktionsbeschreibung |
|:---:|:---|:---:|:---:|
| Audio-Interaktions-Testtool | main》xiaozhi-server》test》test_page.html | Direkt mit Google Chrome öffnen | Testen Sie Audio-Wiedergabe und -Empfang, überprüfen Sie, ob die Python-seitige Audioverarbeitung normal funktioniert |
| Modell-Antwort-Testtool | main》xiaozhi-server》performance_tester.py | Führen Sie `python performance_tester.py` aus | Testen Sie die Reaktionsgeschwindigkeit der drei Kernmodule ASR(Spracherkennung), LLM(Großes Modell), VLLM(Visuelles Modell), TTS(Sprachsynthese) |

> 💡 Tipp: Beim Testen der Modellgeschwindigkeit werden nur die Modelle getestet, für die Schlüssel konfiguriert wurden.

---
## Funktionsliste ✨
### Implementiert ✅
![Siehe - Architekturdiagramm für vollständige Modulinstallation](docs/images/deploy2.png)
| Funktionsmodul | Beschreibung |
|:---:|:---|
| Kernarchitektur | Basierend auf [MQTT+UDP-Gateway](https://github.com/xinnan-tech/xiaozhi-esp32-server/blob/main/docs/mqtt-gateway-integration.md), WebSocket, HTTP-Server, bietet vollständige Konsolen-Verwaltung und Authentifizierungssystem |
| Sprachinteraktion | Unterstützt Streaming-ASR(Spracherkennung), Streaming-TTS(Sprachsynthese), VAD(Sprachaktivitätserkennung), unterstützt mehrsprachige Erkennung und Sprachverarbeitung |
| Sprecherkennung | Unterstützt Multi-User-Sprecher-Registrierung, Verwaltung und Erkennung, parallele Verarbeitung mit ASR, Echtzeit-Identifizierung der Sprecher-Identität und Übergabe an LLM für personalisierte Antworten |
| Intelligenter Dialog | Unterstützt verschiedene LLM(Große Sprachmodelle), realisiert intelligente Dialoge |
| Visuelle Wahrnehmung | Unterstützt verschiedene VLLM(Visuelle große Modelle), realisiert multimodale Interaktion |
| Absichtserkennung | Unterstützt LLM-Absichtserkennung, Funktionsaufruf, bietet Plugin-Absichtsverarbeitungsmechanismus |
| Speichersystem | Unterstützt lokales Kurzzeitgedächtnis, mem0ai-Schnittstellenspeicher, verfügt über Speicher-Zusammenfassungsfunktion |
| Werkzeugaufruf | Unterstützt Client-IOT-Protokoll, Client-MCP-Protokoll, Server-MCP-Protokoll, MCP-Zugriffspunkt-Protokoll, benutzerdefinierte Werkzeugfunktionen |
| Befehlsausgabe | Basierend auf MQTT-Protokoll, unterstützt die Ausgabe von MCP-Befehlen von der intelligenten Konsole an ESP32-Geräte |
| Verwaltungsbackend | Bietet Web-Verwaltungsoberfläche, unterstützt Benutzerverwaltung, Systemkonfiguration und Geräteverwaltung; Oberfläche unterstützt vereinfachtes Chinesisch, traditionelles Chinesisch, englische Anzeige |
| Testwerkzeuge | Bietet Leistungstest-Tools, visuelle Modelltest-Tools und Audio-Interaktionstest-Tools |
| Bereitstellungsunterstützung | Unterstützt Docker-Bereitstellung und lokale Bereitstellung, bietet vollständiges Konfigurationsdateiverwaltung |
| Plugin-System | Unterstützt Funktions-Plugin-Erweiterung, benutzerdefinierte Plugin-Entwicklung und Plugin-Hot-Loading |

### In Entwicklung 🚧

Möchten Sie den spezifischen Entwicklungsplan kennenlernen? [Klicken Sie bitte hier](https://github.com/users/xinnan-tech/projects/3). Häufig gestellte Fragen und verwandte Tutorials finden Sie unter [diesem Link](./docs/FAQ.md)

Wenn Sie Softwareentwickler sind, gibt es hier einen [《Offenen Brief an Entwickler》](docs/contributor_open_letter.md), willkommen zum Mitmachen!

---

## Produktökosystem 👬
Xiaozhi ist ein Ökosystem. Wenn Sie dieses Produkt verwenden, können Sie auch andere [hervorragende Projekte](https://github.com/78/xiaozhi-esp32?tab=readme-ov-file#%E7%9B%B8%E5%85%B3%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE) in diesem Ökosystem ansehen.

---

## Liste der von diesem Projekt unterstützten Plattformen/Komponenten 📋
### LLM Sprachmodelle

| Verwendungsweise | Unterstützte Plattformen | Kostenlose Plattformen |
|:---:|:---:|:---:|
| openai-Schnittstellenaufruf | Alibaba Bailian, Huoshan Engine Doubao, DeepSeek, Zhipu ChatGLM, Gemini | Zhipu ChatGLM, Gemini |
| ollama-Schnittstellenaufruf | Ollama | - |
| dify-Schnittstellenaufruf | Dify | - |
| fastgpt-Schnittstellenaufruf | Fastgpt | - |
| coze-Schnittstellenaufruf | Coze | - |
| xinference-Schnittstellenaufruf | Xinference | - |
| homeassistant-Schnittstellenaufruf | HomeAssistant | - |

Tatsächlich kann jedes LLM, das die openai-Schnittstellenaufruf unterstützt, integriert und verwendet werden.

---

### VLLM Visuelle Modelle

| Verwendungsweise | Unterstützte Plattformen | Kostenlose Plattformen |
|:---:|:---:|:---:|
| openai-Schnittstellenaufruf | Alibaba Bailian, Zhipu ChatGLMVLLM | Zhipu ChatGLMVLLM |

Tatsächlich kann jedes VLLM, das die openai-Schnittstellenaufruf unterstützt, integriert und verwendet werden.

---

### TTS Sprachsynthese

| Verwendungsweise | Unterstützte Plattformen | Kostenlose Plattformen |
|:---:|:---:|:---:|
| Schnittstellenaufruf | EdgeTTS, Huoshan Engine Doubao TTS, Tencent Cloud, Aliyun TTS, Aliyun Streaming TTS, CosyVoiceSiliconflow, TTS302AI, CozeCnTTS, GizwitsTTS, ACGNTTS, OpenAITTS, Lingxi Streaming TTS, MinimaxTTS, Huoshan Dual Stream TTS | Lingxi Streaming TTS, EdgeTTS, CosyVoiceSiliconflow(teilweise) |
| Lokaler Service | FishSpeech, GPT_SOVITS_V2, GPT_SOVITS_V3, Index-TTS, PaddleSpeech | Index-TTS, PaddleSpeech, FishSpeech, GPT_SOVITS_V2, GPT_SOVITS_V3 |

---

### VAD Sprachaktivitätserkennung

| Typ  |   Plattformname    | Verwendungsweise | Gebührenmodell | Bemerkungen |
|:---:|:---------:|:----:|:----:|:--:|
| VAD | SileroVAD | Lokale Verwendung |  Kostenlos  |    |

---

### ASR Spracherkennung

| Verwendungsweise | Unterstützte Plattformen | Kostenlose Plattformen |
|:---:|:---:|:---:|
| Lokale Verwendung | FunASR, SherpaASR | FunASR, SherpaASR |
| Schnittstellenaufruf | DoubaoASR, Doubao Streaming ASR, FunASRServer, TencentASR, AliyunASR, Aliyun Streaming ASR, Baidu ASR, OpenAI ASR | FunASRServer |

---

### Voiceprint Sprecherkennung

| Verwendungsweise | Unterstützte Plattformen | Kostenlose Plattformen |
|:---:|:---:|:---:|
| Lokale Verwendung | 3D-Speaker | 3D-Speaker |

---

### Memory Gedächtnisspeicher

|   Typ   |      Plattformname       | Verwendungsweise |   Gebührenmodell    | Bemerkungen |
|:------:|:---------------:|:----:|:---------:|:--:|
| Memory |     mem0ai      | Schnittstellenaufruf | 1000 Mal/Monat Kontingent |    |
| Memory | mem_local_short | Lokale Zusammenfassung |    Kostenlos     |    |
| Memory |     nomem       | Kein Speichermodus |    Kostenlos     |    |

---

### Intent Absichtserkennung

|   Typ   |     Plattformname      | Verwendungsweise |  Gebührenmodell   |          Bemerkungen           |
|:------:|:-------------:|:----:|:-------:|:---------------------:|
| Intent |  intent_llm   | Schnittstellenaufruf | Gemäß LLM-Gebühr |    Absichtserkennung durch großes Modell, starke Allgemeingültigkeit     |
| Intent | function_call | Schnittstellenaufruf | Gemäß LLM-Gebühr | Absichtsvervollständigung durch Funktionsaufruf des großen Modells, schnell und effektiv |
| Intent |    nointent   | Kein Absichtsmodus |    Kostenlos     |    Keine Absichtserkennung, direkte Rückgabe des Dialogergebnisses     |

---

## Danksagungen 🙏

| Logo | Projekt/Unternehmen | Beschreibung |
|:---:|:---:|:---|
| <img src="./docs/images/logo_bailing.png" width="160"> | [Bailing Sprach-Dialog-Roboter](https://github.com/wwbin2017/bailing) | Dieses Projekt wurde vom [Bailing Sprach-Dialog-Roboter](https://github.com/wwbin2017/bailing) inspiriert und auf dessen Grundlage implementiert |
| <img src="./docs/images/logo_tenclass.png" width="160"> | [Shifang Ronghai](https://www.tenclass.com/) | Dank an [Shifang Ronghai](https://www.tenclass.com/) für die Festlegung standardisierter Kommunikationsprotokolle, Multi-Geräte-Kompatibilitätslösungen und Best Practices für High-Concurrency-Szenarien für das Xiaozhi-Ökosystem; für die Bereitstellung vollständiger technischer Dokumentationsunterstützung für dieses Projekt |
| <img src="./docs/images/logo_xuanfeng.png" width="160"> | [Xuanfeng Technology](https://github.com/Eric0308) | Dank an [Xuanfeng Technology](https://github.com/Eric0308) für den Beitrag des Funktionsaufruf-Frameworks, des MCP-Kommunikationsprotokolls und der Implementierungscode für den Plugin-Aufrufmechanismus, die durch ein standardisiertes Befehlsplanungssystem und dynamische Erweiterungsfähigkeiten die Interaktionseffizienz und Funktionserweiterbarkeit von Frontend-Geräten (IoT) erheblich verbessern |
| <img src="./docs/images/logo_junsen.png" width="160"> | [huangjunsen](https://github.com/huangjunsen0406) | Dank an [huangjunsen](https://github.com/huangjunsen0406) für den Beitrag des `intelligenten Konsolen-Mobilmoduls`, das eine effiziente Steuerung und Echtzeit-Interaktion plattformübergreifender mobiler Geräte realisiert und die Bedienungsfreundlichkeit und Verwaltungseffizienz des Systems in mobilen Szenarien erheblich verbessert |
| <img src="./docs/images/logo_huiyuan.png" width="160"> | [Huiyuan Design](http://ui.kwd988.net/) | Dank an [Huiyuan Design](http://ui.kwd988.net/) für die Bereitstellung professioneller visueller Lösungen für dieses Projekt und die Stärkung der Benutzererfahrung dieses Projekts mit seiner Designerfahrung, die über tausend Unternehmen bedient hat |
| <img src="./docs/images/logo_qinren.png" width="160"> | [Xi'an Qinren Information Technology](https://www.029app.com/) | Dank an [Xi'an Qinren Information Technology](https://www.029app.com/) für die Vertiefung des visuellen Systems dieses Projekts und die Gewährleistung der Konsistenz und Erweiterbarkeit des gesamten Designstils in Multi-Szenario-Anwendungen |
| <img src="./docs/images/logo_contributors.png" width="160"> | [Code-Mitwirkende](https://github.com/xinnan-tech/xiaozhi-esp32-server/graphs/contributors) | Dank an [alle Code-Mitwirkenden](https://github.com/xinnan-tech/xiaozhi-esp32-server/graphs/contributors). Ihr Einsatz macht das Projekt robuster und leistungsfähiger. |


<a href="https://star-history.com/#xinnan-tech/xiaozhi-esp32-server&Date">

 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=xinnan-tech/xiaozhi-esp32-server&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=xinnan-tech/xiaozhi-esp32-server&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=xinnan-tech/xiaozhi-esp32-server&type=Date" />
 </picture>
</a>
