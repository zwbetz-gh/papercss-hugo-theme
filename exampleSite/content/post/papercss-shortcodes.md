---
title: "Papercss Shortcodes"
date: 2019-02-26T13:50:01-06:00
tags: [shortcodes]
---

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

```
TODO
```

<div class="card row flex-center" style="width: 20rem;">
  <img src="https://picsum.photos/768" alt="Card example image">

  <div class="card-body">
    <h4 class="card-title">My awesome Paper card!</h4>
    <h5 class="card-subtitle">Nice looking subtitle.</h5>
    <p class="card-text">Notice that the card width in this example have been set to 20rem, otherwise it will try to fill the current container/row where the card is.</p>
  </div>
</div>
