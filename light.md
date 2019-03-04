---
title: "Light Test"
layout: minimal-default
permalink: "/light-test"
---

### Screen Shots

<div id="lightgallery">

    <a href="/images/dharma1-large.png" title="(01).jpg">
        <img src="/images/dharma1.png">
    </a>
    <a href="/images/dharma2-large.png" title="(02).jpg">
        <img src="/images/dharma2.png">
    </a>
    <a href="/images/dharma3-large.png" title="(03).jpg">
        <img src="/images/dharma3.png">
    </a>

</div>

<script>

document.addEventListener("DOMContentLoaded", function(event) {
    var lg = document.getElementById('lightgallery');

    lightGallery(lg, {
        mode: 'lg-fade',
        speed: 0,
        backdropDuration: 0,
        preload: 5,
        download: false,
        enableDrag: false,
        enableTouch: false,
        subHtmlSelectorRelative: true,
    });
});

</script>