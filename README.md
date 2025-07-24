<img width="200px" src="public/icon.svg" align="left"/>

# Pot (A cute translator)

<br/>
<hr/>
<div align="center">
<table>
<tr>
    <td> <img src="asset/1.png">
    <td> <img src="asset/2.png">
    <td> <img src="asset/3.png">
</table>

# Table of Contents

</div>

-   [Usage](#usage)
-   [Features](#features)
-   [Supported Services](#supported-services)

<div align="center">

# Usage

</div>

| Translation by selection                        | Translate by input                                                    | External calls                                                                           |
| ----------------------------------------------- | --------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Select text and press the shortcut to translate | Press shortcut to open translation window, translate by hitting Enter | More efficient workflow by integrating other apps, see [External Calls](#external-calls) |
| <img src="asset/eg1.gif"/>                      | <img src="asset/eg2.gif"/>                                            | <img src="asset/eg3.gif"/>                                                               |

| Clipboard Listening                                                                                                          | Screenshot OCR                     | Screenshot Translation                   |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- | ---------------------------------------- |
| Click the top left icon on any translation panel to start clipboard listening. Copied text will be translated automatically. | Press shortcut, select area to OCR | Press shortcut, select area to translate |
| <img src="asset/eg4.gif"/>                                                                                                   | <img src="asset/eg5.gif"/>         | <img src="asset/eg6.gif"/>               |

<div align="center">

# Features

</div>

-   [x] Parallel translations with multiple services ([Supported Services](#supported-services))
-   [x] OCR with multiple services ([Supported Services](#supported-services))
-   [x] Text-to-Speech with multiple services ([Supported Services](#supported-services))
-   [x] Export to vocabulary apps ([Supported Services](#supported-services))
-   [x] External calls ([External Calls](#external-calls))
-   [x] Plugin system ([Plugin System](#plugin-system))
-   [x] Support Windows, macOS and Linux
-   [x] Support Wayland (Tested on KDE, Gnome and Hyprland)
-   [x] Multi-language support

<div align="center">

# Supported Services

</div>

## Translation

-   [x] [OpenAI](https://platform.openai.com/)
-   [x] [ChatGLM](https://www.zhipuai.cn/)
-   [x] [Gemini Pro](https://gemini.google.com/)
-   [x] [Ollama](https://www.ollama.com/) (Offline)
-   [x] [Ali Translate](https://www.aliyun.com/product/ai/alimt)
-   [x] [Baidu Translate](https://fanyi.baidu.com/)
-   [x] [Caiyun](https://fanyi.caiyunapp.com/)
-   [x] [Tencent Transmart](https://fanyi.qq.com/)
-   [x] [Tencent Interactive Translate](https://transmart.qq.com/)
-   [x] [Volcengine Translate](https://translate.volcengine.com/)
-   [x] [NiuTrans](https://niutrans.com/)
-   [x] [Google Translate](https://translate.google.com)
-   [x] [Bing Translate](https://learn.microsoft.com/zh-cn/azure/cognitive-services/translator/)
-   [x] [Bing Dictionary](https://www.bing.com/dict)
-   [x] [DeepL](https://www.deepl.com/)
-   [x] [Youdao](https://ai.youdao.com/)
-   [x] [Cambridge Dictionary](https://dictionary.cambridge.org/)
-   [x] [Yandex](https://translate.yandex.com/)
-   [x] [Lingva](https://github.com/TheDavidDelta/lingva-translate) ([Plugin](https://github.com/pot-app/pot-app-translate-plugin-template))
-   [x] [Tatoeba](https://tatoeba.org/) ([Plugin](https://github.com/pot-app/pot-app-translate-plugin-tatoeba))
-   [x] [ECDICT](https://github.com/skywind3000/ECDICT) ([Plugin](https://github.com/pot-app/pot-app-translate-plugin-ecdict))

More Services see [Plugin System](#plugin-system)

## Text Recognize

-   [x] System OCR (Offline)
    -   [x] [Windows.Media.OCR](https://learn.microsoft.com/en-us/uwp/api/windows.media.ocr.ocrengine?view=winrt-22621) on Windows
    -   [x] [Apple Vision Framework](https://developer.apple.com/documentation/vision/recognizing_text_in_images) on MacOS
    -   [x] [Tesseract OCR](https://github.com/tesseract-ocr) on Linux
-   [x] [Tesseract.js](https://tesseract.projectnaptha.com/) (Offline)
-   [x] [Baidu](https://ai.baidu.com/tech/ocr/general)
-   [x] [Tencent](https://cloud.tencent.com/product/ocr-catalog)
-   [x] [Volcengine](https://www.volcengine.com/product/OCR)
-   [x] [iflytek](https://www.xfyun.cn/services/common-ocr)
-   [x] [Tencent Image Translate](https://cloud.tencent.com/document/product/551/17232)
-   [x] [Baidu Image Translate](https://fanyi-api.baidu.com/product/22)
-   [x] [Simple LaTeX](https://simpletex.cn/)
-   [x] [OCRSpace](https://ocr.space/) ([Plugin](https://github.com/pot-app/pot-app-recognize-plugin-template))
-   [x] [Rapid](https://github.com/RapidAI/RapidOcrOnnx) (Offline [Plugin](https://github.com/pot-app/pot-app-recognize-plugin-rapid))
-   [x] [Paddle](https://github.com/hiroi-sora/PaddleOCR-json) (Offline [Plugin](https://github.com/pot-app/pot-app-recognize-plugin-paddle))

More Services see [Plugin System](#plugin-system)

## Text-to-Speech

-   [x] [Lingva](https://github.com/thedaviddelta/lingva-translate)

More Services see [Plugin System](#plugin-system)

## Collection

-   [x] [Anki](https://apps.ankiweb.net/)
-   [x] [Eudic](https://dict.eudic.net/)
-   [x] [Youdao](https://www.youdao.com/) ([Plugin](https://github.com/pot-app/pot-app-collection-plugin-youdao))
-   [x] [ShanBay](https://web.shanbay.com/web/main) ([Plugin](https://github.com/pot-app/pot-app-collection-plugin-shanbay))

More Services see [Plugin System](#plugin-system)
