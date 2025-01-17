---
UID: NC:d3d12umddi.PFND3D12DDI_CREATEBLENDSTATE_0010
title: PFND3D12DDI_CREATEBLENDSTATE_0010 (d3d12umddi.h)
description: Creates a blend state.
ms.date: 10/19/2018
keywords: ["PFND3D12DDI_CREATEBLENDSTATE_0010 callback function"]
req.header: d3d12umddi.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.irql: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
tech.root: display
ms.custom: RS5
f1_keywords:
 - PFND3D12DDI_CREATEBLENDSTATE_0010
 - d3d12umddi/PFND3D12DDI_CREATEBLENDSTATE_0010
topic_type:
 - apiref
api_type:
 - UserDefined
api_location:
 - d3d12umddi.h
api_name:
 - PFND3D12DDI_CREATEBLENDSTATE_0010
product:
 - Windows
dev_langs:
 - c++
---

# PFND3D12DDI_CREATEBLENDSTATE_0010 callback function


## -description

Creates a blend state.

## -parameters

### -param unnamedParam1

A handle to the display device (graphics context).

### -param unnamedParam2

Pointer to a D3D12DDI_BLEND_DESC_0010 structure.

### -param unnamedParam3

A blend state handle.

## -prototype

```cpp
//Declaration

PFND3D12DDI_CREATEBLENDSTATE_0010 Pfnd3d12ddiCreateblendstate0010; 

// Definition

VOID Pfnd3d12ddiCreateblendstate0010 
(
	 D3D12DDI_HDEVICE
	CONST D3D12DDI_BLEND_DESC_0010 *
	 D3D12DDI_HBLENDSTATE
)
{...}

PFND3D12DDI_CREATEBLENDSTATE_0010 


```

