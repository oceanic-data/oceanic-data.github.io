---
title: "Minimal Page 2"
layout: minimal-default
permalink: "/cat/minimal-page-md"
---

### minimal subtitle

content

content

<div class="my-gallery" itemscope itemtype="http://schema.org/ImageGallery">

    <figure itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="/images/dharma1-large.png" itemprop="contentUrl" data-size="600x600">
            <img src="/images/dharma1.png" itemprop="thumbnail" alt="Image description" />
        </a>
        <figcaption itemprop="caption description">caption</figcaption>
    </figure>

    <figure itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="/images/dharma2-large.png" itemprop="contentUrl" data-size="600x600">
            <img src="/images/dharma2.png" itemprop="thumbnail" alt="Image description" />
        </a>
        <figcaption itemprop="caption description">caption</figcaption>
    </figure>

    <figure itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
        <a href="/images/dharma3-large.png" itemprop="contentUrl" data-size="600x600">
            <img src="/images/dharma3.png" itemprop="thumbnail" alt="Image description" />
        </a>
        <figcaption itemprop="caption description">caption</figcaption>
    </figure>


</div>

<script>
document.addEventListener("DOMContentLoaded", function(event) {
    initPhotoSwipeFromDOM('.my-gallery');
});
</script>