---
description: This operator tests if one reference time is less than or equal to another.
ms.assetid: ae7449b7-d319-4e76-892f-0f9ae63ddf94
title: COARefTime.operator>= method (Ctlutil.h)
ms.topic: reference
ms.date: 4/26/2023
topic_type: 
- APIRef
- kbSyntax
api_name: 
- COARefTime.operator>=
api_type: 
- COM
api_location: 
- Strmbase.lib
- Strmbase.dll
- Strmbasd.lib
- Strmbasd.dll
ms.custom: UpdateFrequency5
---

# COARefTime.operator>= method

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

This operator tests if one reference time is less than or equal to another.

## Syntax


```C++
BOOL operator>=(
  [ref] const COARefTime &rt
);
```



## Parameters

<dl> <dt>

*rt* \[ref\]
</dt> <dd>

Reference to the **COARefTime** object to compare.

</dd> </dl>

## Return value

Returns **TRUE** if this object is less than or equal to *rt*. Otherwise, returns **FALSE**.

## Requirements



| Requirement | Value |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Ctlutil.h (include Streams.h)</dt> </dl>                                                                                   |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



## See also

<dl> <dt>

[**COARefTime Class**](coareftime.md)
</dt> </dl>

 

 




