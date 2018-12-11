---
views:
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
Dagens bild
===========================

I denna blogg läggs det upp en bild för varje dag kallad dagens bild. Denna blogg är gjord i utbildningssyfte i kursen Design v2 på BTH.
