---

title: Language support and guidelines for Viva Insights
description: Describes the privacy and data access controls available in Microsoft Viva Insights 
author: madehmer
ms.author: helayne
ms.topic: article
ms.collection: 
- viva-insights-advanced
- viva-insights-leader
ms.localizationpriority: medium 
ms.service: viva 
ms.subservice: viva-insights 
manager: scott.ruble
audience: Admin

---

# Advanced insights language support and guidelines

The user interface in Microsoft Viva Insights in Workplace Analytics is currently available in Chinese (Simplified), Chinese (Traditional), French (France), German (Germany), Italian (Italy), Japanese, Korean, Portuguese (Brazil), Russian (Russia), Spanish (Spain), and English (United States).

The Workplace Analytics app automatically uses your language identifier (language and region) setting, as specified in one of the following sources:

* Windows
* Your web browser
* Location that's set for your Exchange Online mailbox

You can override this setting. To do so, replace language identifier ("en-us" is for US English) with a different language identifier. The table under [Supported languages](#supported-languages) lists all of the supported languages for Workplace Analytics.

For example, you'd replace '/en-us/' with '/ja-jp/' to indicate Japanese as the language to open the app in: 'https://workplaceanalytics.office.com/ja-jp/'

## Supported languages

Language and region | Language identifier
------ | ------
Chinese (Simplified) | zh-cn
Chinese (Traditional) | zh-tw
French (France) | fr-fr
German (Germany) | de-de
Italian (Italy) | it-it
Japanese | ja-jp
Korean | ko-kr
Portuguese (Brazil) | pt-br
Russian (Russia) | ru-ru
Spanish (Spain) | es-es
English (United States) | en-us

## Use of data other than English

In certain circumstances, you can use Workplace Analytics with _data_ that is in other languages. Follow these guidelines:

* Query names and descriptions must be in English, Japanese, or French.

   ![Query names and descriptions.](../Images/WpA/Overview/query-name-description.png)

* Column headers for the organizational data when you [prepare the organizational data](../Setup/Prepare-organizational-data.md) must be in English.

* When an analyst selects metrics while building a [query](../tutorials/query-basics.md), the metric names they choose can be in the language of their choice. See [Supported languages for column headers](../use/view-download-and-export-query-results.md?branch=pas-pd-other-char-sets#supported-languages-for-column-headers).

* For content within organizational data, you can use languages other than English.

## Privacy settings

In [Privacy settings](../use/privacy-settings.md), when adding the subject line terms to exclude from analysis, Workplace Analytics might not recognize uncommon compound words, especially those in other languages such as Japanese or Chinese. For best results, use single words, separated by a semicolon.

![Exclude terms from subject line.](../Images/WpA/Overview/exclude-terms-from-subject-line.png)

We appreciate all your feedback. To report any language-related issues, use the **Send feedback** button.

## Related topics

* [Supported languages in meeting exclusion rules](../tutorials/meeting-exclusion-concept.md#supported-languages)
* [Control settings](../use/settings.md)
* [Privacy settings considerations](../Privacy/privacy-considerations.md)
