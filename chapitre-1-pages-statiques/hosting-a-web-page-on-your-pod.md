# Héberger une page html sur votre Pod

## Introduction

Cette astuce vous permet d'héberger des pages web traditionnelles sur votre POD Solid. Solid est 100% compatible avec le web existant. Héberger une page web sur votre POD ne peut être plus simple. Vous pouvez aussi bien y mettre une page html statique que du javascript.

On va créer une page publique hébergée sur votre POD Solid, qui sera accessible à l'adresse :

[https://{yourname.solidpod}/public/mysite/webpage.html](https://{yourname.solidpod}/public/mysite/webpage.html)

## L'astuce

Browse to your solid pod. Since you want to offer your web page to everyone on the Internet go to your `public` folder. Within your `public` folder click the green + sign on your [databrowser](https://github.com/solid/userguide) and click the `folder` icon and give this new folder the name _mysite_. Now click the new green + sign within the _mysite_ folder and create a new `source` by clicking the icon and give this the name `webpage.html`.

![Create a webpage with the databrowser](../.gitbook/assets/hacks-webpage.png)

This will create a file `webpage.html` in your public _mysite_ folder. Expand webpage.html and hover over the top which will give you the ability to edit the source.

![Edit webpage source](../.gitbook/assets/hacks-webpage-edit.png)

In the textbox type in something \(or paste\) something suitably kitch. Example

```text
<h2>Hello</h2>

Solid World!
```

And click the green tick. Congratulations, you have now published your first web page to solid!

**Tip 1** Drag and drop a file to the green plus and it will be uploaded to that directory.

**Tip 2** If you want to start a site within the _mysite_ folder, you can name the HTML file `index.html` and this way the contents of the folder will not be shown as a Solid Pod folder, but your HTML file will be used instead.

## Demo

> [https://solidhacks.solid.community/public/demos/webpage.html](https://solidhacks.solid.community/public/demos/webpage.html)

## Exercises

Pour le fun créez quelques pages en utilisant le copié/collé du code proposé sur ce site!

> [http://aem1k.com/](http://aem1k.com/)

