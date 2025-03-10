---
description: The DefaultAudioLanguage property retrieves the default audio language.
ms.assetid: 7ab7760c-110a-4b0d-919a-32244144467f
title: DefaultAudioLanguage Property
ms.topic: reference
ms.date: 4/26/2023
ms.custom: UpdateFrequency5
---

# DefaultAudioLanguage Property

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

> [!Note]  
> This component is available for use in the Microsoft Windows 2000, Windows XP, and Windows Server 2003 operating systems. It may be altered or unavailable in subsequent versions.

 

The `DefaultAudioLanguage` property retrieves the default audio language.

``` syntax
[ iLang = ] MSWebDVD.DefaultAudioLanguage
```

## Return Value

Returns an LCID value containing the primary language ID for the default audio language.

## Remarks

This property is read-only with no default value.

## See also

<dl> <dt>

[**SelectDefaultAudioLanguage**](selectdefaultaudiolanguage-method.md)
</dt> </dl>

 

 



