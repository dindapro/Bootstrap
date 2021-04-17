# Including Bootstrap & Containers

Get started with Bootstrap, the world’s most popular framework for building responsive, mobile-first sites, with jsDelivr and a template starter page.

## Table of Contents

* [Quick start](#quick-start)
* [Setup Environment](#setup-environment)
* [New record](#new-record)
  * [Record update](#record-update)
  * [Record delete](#record-delete)

## Quick start

Looking to quickly add Bootstrap to your project? Use jsDelivr, a free open source CDN.

Copy-paste the stylesheet <link> into your <head> before all other stylesheets to load our CSS.
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css" integrity="sha384-B0vP5xmATw1+K9KRQjQERJvTumQW0nPEzvF6L/Z6nronJ3oUOFUFpCjEUQouq2+l" crossorigin="anonymous">
```

If you decide to go with the separate scripts solution, Popper must come first (if you’re using tooltips or popovers), and then our JavaScript plugins.
```shell
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.min.js" integrity="sha384-+YQ4JLhjyBLPDQt//I+STsc9iw4uQqACwlvpslubQzn4u2UU2UFM80nGisd026JF" crossorigin="anonymous"></script>
```

## Layout

How to run:

```shell
<div class="container">
  <!-- Content here -->
</div>
```