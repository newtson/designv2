---
views:
    flash:
        region: flash
        template: anax/v2/image/default
        data:
            src: "image/theme/flashblogg.JPG?width=1100&height=150&crop-to-fit&area=30,0,0,0"

    main:
        template: anax/v2/article/default
        data:
            class: blog

    byline: false
    block-about: false
    article-toc: false

    blog-list:
        region: main
        template: anax/v2/blog-list/default
        sort: 2
        data:
            dateFormat: j F Y
            meta:
                type: toc
                orderby: publishTime
                orderorder: desc

    blog-toc:
        region: sidebar-right
        template: anax/v2/blog-toc/default
        sort: 2
        data:
            meta:
                type: copy
                view: blog-list

---
<!--
Nytt och Noterat
===========================-->
Dagens Bild
===========================

Visar dagens bild, en bild som kan vara av vad som helst men som antagligen kommer att visa djur, natur eller byggnader som är omgivna av natur. Kort och gott, det visar vad som intresserar mig.
<!--
<Kortare blogginlägg om vad som händer på dbwebb.se, kurserna samt webbprogrammering och webbutveckling med HTML, CSS, JavaScript, PHP och SQL i allmänhet.-->
