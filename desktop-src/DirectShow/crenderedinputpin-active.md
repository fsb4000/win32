---
description: CRenderedInputPin.Active method - The Active method notifies the pin that the filter is now active. This method overrides the CBasePin::Active method.
ms.assetid: e98ca947-df2f-41a7-9785-b35bd1dde1e6
title: CRenderedInputPin.Active method (Amextra.h)
ms.topic: reference
ms.date: 4/26/2023
topic_type: 
- APIRef
- kbSyntax
api_name: 
- CRenderedInputPin.Active
api_type: 
- COM
api_location: 
- Strmbase.lib
- Strmbase.dll
- Strmbasd.lib
- Strmbasd.dll
ms.custom: UpdateFrequency5
---

# CRenderedInputPin.Active method

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The `Active` method notifies the pin that the filter is now active. This method overrides the [**CBasePin::Active**](cbasepin-active.md) method.

## Syntax


```C++
HRESULT Active();
```



## Parameters

This method has no parameters.

## Return value

Returns S\_OK if successful, or an error code otherwise.

## Requirements



| Requirement | Value |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Amextra.h (include Streams.h)</dt> </dl>                                                                                   |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



## See also

<dl> <dt>

[**CRenderedInputPin Class**](crenderedinputpin.md)
</dt> </dl>

 

 




