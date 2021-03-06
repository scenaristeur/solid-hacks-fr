# Créer un éditeur Markdown temps-réel

## ![](../.gitbook/assets/markdown.png)   <a id="introduction"></a>

## Introduction  <a id="introduction"></a>

This hack again builds on the previous hack.

> [https://solid.gitbook.io/solid-hacks/section-1/hosting-a-web-page-on-your-pod](https://solid.gitbook.io/solid-hacks/section-1/hosting-a-web-page-on-your-pod)

This time we will create a realtime markdown editor. This page is more complex and contains several files. However there is a trick that will enable us to use the same one page pattern as before. And that is to use the `<base>` tag.

## The Hack  <a id="the-hack"></a>

Browse to your solid pod. Within your `public` create a webpage called markdown.html with the databrowser.

Cut and paste the following file to your page.

> [https://raw.githubusercontent.com/jbt/markdown-editor/master/index.html](https://raw.githubusercontent.com/jbt/markdown-editor/master/index.html)

However we are going to add one additional line to mimic the base. Beneath the HTML tag add.

`<base href="`[`https://jbt.github.io/markdown-editor/`](https://jbt.github.io/markdown-editor/)`">`

And we're done. Congratulations, you have now made a useful app. A realtime markdown editor!

## Demo  <a id="demo"></a>

> [https://solidhacks.solid.community/public/demos/markdown.html](https://solidhacks.solid.community/public/demos/markdown.html)

## Exercises

As a step further try and create some of the markdown editors below. See what issues come up. Or try some other static apps.

## See Also

### Realtime Markdown editors

> [https://github.com/joemccann/dillinger](https://github.com/joemccann/dillinger)
>
> [https://github.com/tylingsoft/markdown-plus](https://github.com/tylingsoft/markdown-plus)
>
> [https://github.com/jbt/markdown-editor](https://github.com/jbt/markdown-editor)
>
> [https://github.com/benweet/stackedit](https://github.com/benweet/stackedit)

### Create a web page with Markdown

> [https://github.com/oscarmorrison/md-page](https://github.com/oscarmorrison/md-page)  
>   
> [https://casual-effects.com/markdeep/features.md.html](https://casual-effects.com/markdeep/features.md.html)

