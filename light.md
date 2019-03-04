---
title: "Light Test"
layout: minimal-default
permalink: "/light-test"
---

### Screen Shots

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<div id="lightgallery">
    <a href="/images/dharma1-large.png" title="(01).jpg"><img src="/images/dharma1.png"></a>
    <a href="/images/dharma2-large.png" title="(02).jpg"><img src="/images/dharma2.png"></a>
    <a href="/images/dharma3-large.png" title="(03).jpg"><img src="/images/dharma3.png"></a>
</div>

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

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