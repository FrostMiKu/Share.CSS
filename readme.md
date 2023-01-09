# Share.CSS

Sharing theme for Trilium Note.
Can also be used for paper page.

## Screenshot

- Before:
![Origin](screenshot/before.png)

- After:
![Origin](screenshot/page.png)
![tree](screenshot/treepage.png)
<img src="screenshot/mobile.png" height="400px">

## How to use

1. copy `src/share.css` and create a new note
2. clone this note into your Sharing Tree
3. add a ~shareCss relation to the share.css code note which will be linked in the shared page
    1. in case you want this to apply to the whole subtree, don't forget to make the label inheritable
    2. If you want to hide this css code note from left tree navigation, add #shareHiddenFromTree label to the CSS code note.

[See the Trilium wiki for more information](https://github.com/zadam/trilium/wiki/Sharing)

## For paper page

This theme can also be used for page which have the fixed structure like this:
```html
<body>
    <div id="layout">
        <div id="main">
            <h1 id="title">...</h1>
            <div id="content">
                <p>...</p>
            </div>
        </div>
    </div>
</body>
```

[Like this](https://blog.frostmiku.com/Flow-VAE-VC/)

## Contribute

Welcome PR

## Thx

- https://github.com/sivan/heti
- https://github.com/CaiJimmy/hugo-theme-stack
