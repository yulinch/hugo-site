---
title: "Test post"
date: 2022-04-20T16:14:15+08:00
description: "Test post"
featured_image: "img/cover.jpeg"
showReadTime: false
draft: true
tags:
sitemap_ignore: true
---

[Neat]({{< ref "cook/20220427.md" >}})
{{< highlight go >}} A bunch of code here {{< /highlight >}}
{{< gist spf13 7896402 >}}
{{< figure src="/img/plant.jpeg" attr="attr" title="title" caption="caption" >}}{{< figure >}}
{{< youtube -XewmmAQBow >}}

![alt text](/img/plant.jpeg)

<img src="/img/plant.jpeg">

{{< highlight go >}}
func GetTitleFunc(style string) func(s string) string {
switch strings.ToLower(style) {
case "go":
return strings.Title
case "chicago":
return transform.NewTitleConverter(transform.ChicagoStyle)
default:
return transform.NewTitleConverter(transform.APStyle)
}
}
{{< /highlight >}}
change the name after 'chat'

<div>{{< chat cactus-comments >}}</div>
