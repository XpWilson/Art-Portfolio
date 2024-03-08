---
title: "Simple Scrolling Texture Shader"
date: 2023-05-06T16:16:10-04:00
draft: false
cover.responsiveImages: true
cover:
    image: images/Scroll/arrow2.webp
ShowBreadCrumbs: true
showtoc: true
---

## Summary 
This shader demonstrates a simple yet versatile scrolling texture shader. This shader was used in both games I helped create Fate’s Twisted Tower and Fate’s Twisted Mountain. This shader was created using Shadergraph for Unity as with all shader utilities these principles can be transferred to most programs.

The shader works by tiling a provided texture across an object’s UV index. The movement of the surface is done by inputting a time-related node to affect an object’s UV offset input. This can be further controlled by adding a multiplier to the time function so there is finer granularity in terms of controlling the speed of the scroll. 

This shader can prove useful in a variety of contexts such as bodies of water, lava, and boost panels as well. This shader can get the job done in any place that appears to need a scrolling texture.

## Example use cases:

#### Lava waterfalls
{{< figure src="/images/Scroll/lavafall.webp" title="" >}}

#### Bodies of liquid
{{< figure src="/images/Scroll/lavatrail.webp" title="" >}}
Above example shows a lava lake.

#### Boost panels 
{{< figure src="/images/Scroll/arrow2.webp" title="" >}}

#### Backgrounds 
{{< youtube ft1tTasdPlY >}}

## Tech used
Shader
| ------ | ----------- |
| Game Engine   | Unity Engine |
| Tool   | URP Shader Graph |
| Development Timeframe | 1 month |
