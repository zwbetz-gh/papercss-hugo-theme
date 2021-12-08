---
title: "Papercss Shortcodes"
date: 2019-02-26T13:50:01-06:00
tags: [shortcodes]
show_summary: false
---

## collapsible

```
{{</* collapsible "First" */>}}
Bacon ipsum dolor sit amet beef venison beef ribs kielbasa.
{{</* /collapsible */>}}

{{</* collapsible "Second" */>}}
Bacon ipsum dolor sit amet landjaeger sausage brisket.
{{</* /collapsible */>}}
```

{{< collapsible "First" >}}
Bacon ipsum dolor sit amet beef venison beef ribs kielbasa.
{{< /collapsible >}}

{{< collapsible "Second" >}}
Bacon ipsum dolor sit amet landjaeger sausage brisket.
{{< /collapsible >}}

## border

```
{{</* border */>}}
Regular
{{</* /border */>}}

{{</* border "dashed" */>}}
Dashed
{{</* /border */>}}

{{</* border "dotted" */>}}
Dotted
{{</* /border */>}}

{{</* border "dashed thick" */>}}
Dashed Thick
{{</* /border */>}}

{{</* border "dotted thick" */>}}
Dotted Thick
{{</* /border */>}}
```

{{< border >}}
Regular
{{< /border >}}

{{< border "dashed" >}}
Dashed
{{< /border >}}

{{< border "dotted" >}}
Dotted
{{< /border >}}

{{< border "dashed thick" >}}
Dashed Thick
{{< /border >}}

{{< border "dotted thick" >}}
Dotted Thick
{{< /border >}}

## color

```
{{</* color "primary" */>}}
Text primary
{{</* /color */>}}

{{</* color "secondary" */>}}
Text secondary
{{</* /color */>}}

{{</* color "success" */>}}
Text success
{{</* /color */>}}

{{</* color "warning" */>}}
Text warning
{{</* /color */>}}

{{</* color "danger" */>}}
Text danger
{{</* /color */>}}

{{</* color "muted" */>}}
Text muted
{{</* /color */>}}
```

{{< color "primary" >}}
Text primary
{{< /color >}}

{{< color "secondary" >}}
Text secondary
{{< /color >}}

{{< color "success" >}}
Text success
{{< /color >}}

{{< color "warning" >}}
Text warning
{{< /color >}}

{{< color "danger" >}}
Text danger
{{< /color >}}

{{< color "muted" >}}
Text muted
{{< /color >}}

## background

```
{{</* background "primary" */>}}
Background primary
{{</* /background */>}}

{{</* background "secondary" */>}}
Background secondary
{{</* /background */>}}

{{</* background "success" */>}}
Background success
{{</* /background */>}}

{{</* background "warning" */>}}
Background warning
{{</* /background */>}}

{{</* background "danger" */>}}
Background danger
{{</* /background */>}}
```

{{< background "primary" >}}
Background primary
{{< /background >}}

{{< background "secondary" >}}
Background secondary
{{< /background >}}

{{< background "success" >}}
Background success
{{< /background >}}

{{< background "warning" >}}
Background warning
{{< /background >}}

{{< background "danger" >}}
Background danger
{{< /background >}}

## alert

```
{{</* alert "primary" */>}}
Alert-primary
{{</* /alert */>}}

{{</* alert "secondary" */>}}
Alert-secondary
{{</* /alert */>}}

{{</* alert "success" */>}}
Alert-success
{{</* /alert */>}}

{{</* alert "warning" */>}}
Alert-warning
{{</* /alert */>}}

{{</* alert "danger" */>}}
Alert-danger
{{</* /alert */>}}
```

{{< alert "primary" >}}
Alert-primary
{{< /alert >}}

{{< alert "secondary" >}}
Alert-secondary
{{< /alert >}}

{{< alert "success" >}}
Alert-success
{{< /alert >}}

{{< alert "warning" >}}
Alert-warning
{{< /alert >}}

{{< alert "danger" >}}
Alert-danger
{{< /alert >}}

## badge

```
<h3>Example badge {{</* badge */>}}123{{</* /badge */>}}</h3>

<h3>Example badge {{</* badge "secondary" */>}}123{{</* /badge */>}}</h3>

<h3>Example badge {{</* badge "success" */>}}123{{</* /badge */>}}</h3>

<h3>Example badge {{</* badge "warning" */>}}123{{</* /badge */>}}</h3>

<h3>Example badge {{</* badge "danger" */>}}123{{</* /badge */>}}</h3>
```

<h3>Example badge {{< badge >}}123{{< /badge >}}</h3>

<h3>Example badge {{< badge "secondary" >}}123{{< /badge >}}</h3>

<h3>Example badge {{< badge "success" >}}123{{< /badge >}}</h3>

<h3>Example badge {{< badge "warning" >}}123{{< /badge >}}</h3>

<h3>Example badge {{< badge "danger" >}}123{{< /badge >}}</h3>

## card

The `img` param accepts an [image page resource](https://gohugo.io/content-management/page-resources/) name.

The `command` and `options` params accept [image processing](https://gohugo.io/content-management/image-processing/#readout) args.

Required params: `img`, `command`, `options`.

Optional params: `title`, `subtitle`, `text`.

```
{{</* card
img="sun.jpg"
command="Resize"
options="900x"
title="The Sun"
subtitle="It's the Sun, dude"
text="The Sun is the star at the center of the Solar System. It is a nearly perfect sphere of hot plasma, with internal convective motion that generates a magnetic field via a dynamo process. It is by far the most important source of energy for life on Earth. [Credits](https://images.nasa.gov/details-GSFC_20171208_Archive_e000393.html)." */>}}
```



{{< card
img="sun.jpg"
command="Resize"
options="900x"
title="The Sun"
subtitle="It's the Sun, dude"
text="The Sun is the star at the center of the Solar System. It is a nearly perfect sphere of hot plasma, with internal convective motion that generates a magnetic field via a dynamo process. It is by far the most important source of energy for life on Earth. [Credits](https://images.nasa.gov/details-GSFC_20171208_Archive_e000393.html)." >}}

## With Markdown

```
{{</* border */>}}
* Testing GitHub issue <https://github.com/zwbetz-gh/papercss-hugo-theme/issues/8>
* **bold**
* _italic_
{{</* /border */>}}

{{</* color "success" */>}}
* Testing GitHub issue <https://github.com/zwbetz-gh/papercss-hugo-theme/issues/8>
* **bold**
* _italic_
{{</* /color */>}}

{{</* background "success" */>}}
* Testing GitHub issue <https://github.com/zwbetz-gh/papercss-hugo-theme/issues/8>
* **bold**
* _italic_
{{</* /background */>}}

{{</* alert "success" */>}}
* Testing GitHub issue <https://github.com/zwbetz-gh/papercss-hugo-theme/issues/8>
* **bold**
* _italic_
{{</* /alert */>}}

<h3>Example badge {{</* badge "success" */>}}[link](https://gohugo.io/functions/markdownify/), **bold**, _italic_{{</* /badge */>}}</h3>
```

{{< border >}}
* Testing GitHub issue <https://github.com/zwbetz-gh/papercss-hugo-theme/issues/8>
* **bold**
* _italic_
{{< /border >}}

<br>

{{< color "success" >}}
* Testing GitHub issue <https://github.com/zwbetz-gh/papercss-hugo-theme/issues/8>
* **bold**
* _italic_
{{< /color >}}

<br>

{{< background "success" >}}
* Testing GitHub issue <https://github.com/zwbetz-gh/papercss-hugo-theme/issues/8>
* **bold**
* _italic_
{{< /background >}}

<br>

{{< alert "success" >}}
* Testing GitHub issue <https://github.com/zwbetz-gh/papercss-hugo-theme/issues/8>
* **bold**
* _italic_
{{< /alert >}}

<h3>Example badge {{< badge "success" >}}[link](https://gohugo.io/functions/markdownify/), **bold**, _italic_{{< /badge >}}</h3>
