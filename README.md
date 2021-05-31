# md

The repo is mainly used to store markdown assets.


# Typora and Markdown

[toc]

# H1

## H2

### H3

#### H4

## common

paragraph break: <kbd>Return</kbd>

line break: <kbd>Shift</kbd> + <kbd>Return</kbd>



header: <kbd>Cmd</kbd> + <kbd>1</kbd> ~ <kbd>6</kbd>; `# header`, etc.



==highlight==: <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>H</kbd>; `==text==`

**bold**: <kbd>Cmd</kbd> + <kbd>B</kbd>; `**text**`

*italic*: <kbd>Cmd</kbd> + <kbd>I</kbd>; `*text*`

<u>underline</u>: <kbd>Cmd</kbd> + <kbd>U</kbd>; `<u>text</u>`

~~deleteline~~: `~~text~~`

~subscript~: `~subscript~`

^superscript^: `^superscript^`



<q>quote inline</q>: `<q>quote</q> `

> quote block: `> quote`



<url>: `<url>`

[link](): `[text](url)`, `[text](url "title")`



code inline: 

```
`code`
```

code block: 

```
​```type
code
​```
```



equation inline: `$equation$`

equation block: 

```
$$
equation
$$
```



image: `![text](path)`, `![text](path "title")`



unordered list: 

```
- item
- item
```

ordered list: 

```
1. item
2. item
```

task list: 

```
- [ ] item
- [x] item
```



table: <kbd>Cmd</kbd> + <kbd>Opt</kbd> + <kbd>T</kbd>



horizontal rule: `---`



table of contents: `[toc]`



## extension

topscript: `<ruby>text<rt>topscript</rt></ruby>`

emoji: `:smile:`, etc.

keyboard: `<kbd>key</kbd>`

button: `<button>button</button>`

html entity: `&amp;`, etc.

comment: `<!-- comment -->`



internal link: `[text](#header)`

reference link: 

```
[text][ref_id]
[ref_id]: url "optional_title"
```

```
[text_id][]
[text_id]: url "optional_title"
```

rich link: implemented by html.



footnote: 

```
text[^fn_id]
[^fn_id]: ref_text
```



toggle block: 

```
<details>
<summary>display_text</summary>
toggle_text
</details>
```



audio: `<audio src="path" />`

video: `<video src="path" />`

local file: `[text](path)`

file embed: use embed file viewer on the web.



embed: `<iframe src="url"></iframe>`. Just copy embed code from the share source. 



digram: take a look at references.

## embed examples

embed a video on youtube

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/w3Wluvzoggg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

embed a video on bilibili

<iframe src="//player.bilibili.com/player.html?aid=587394232&bvid=BV1iB4y1P7py&cid=321152931&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

embed a playlist on spotify

<iframe src="https://open.spotify.com/embed?uri=spotify%3Aplaylist%3A6SmdaueTjuTdCz9o3BavcE" width="300" height="380" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>

embed a playlist on apple music

<iframe allow="autoplay *; encrypted-media *; fullscreen *" frameborder="0" height="450" style="width:100%;max-width:660px;overflow:hidden;background:transparent;" sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-storage-access-by-user-activation allow-top-navigation-by-user-activation" src="https://embed.music.apple.com/jp/playlist/%E3%81%AF%E3%81%98%E3%82%81%E3%81%A6%E3%81%AE-%E9%AC%BC%E6%9D%9F%E3%81%A1%E3%81%B2%E3%82%8D/pl.57be0534d7ec4bb399777116d83f6708"></iframe>

embed a location on google map

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d51848.84403171196!2d138.55376947910156!3d35.6880131!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1szh-CN!2sjp!4v1619862679707!5m2!1szh-CN!2sjp" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>



## Reference

[Table Editing](https://support.typora.io/Table-Editing/)

[Links](https://support.typora.io/Links/)

[Images in Typora](https://support.typora.io/Images/)

[Upload Images](https://support.typora.io/Upload-Image/)

[如何使用 Github 作为自己的免费图床](https://learnku.com/articles/48574)

[Embed Video, Media or Web Contents](https://support.typora.io/Media/)

[Embedded File Viewer: Google Drive, OneDrive](https://gist.github.com/tzmartin/1cf85dc3d975f94cfddc04bc0dd399be)

[Draw Diagrams With Markdown](https://support.typora.io/Draw-Diagrams-With-Markdown/)

[Page Breaks](https://support.typora.io/Page-Breaks/)

[File Management](https://support.typora.io/File-Management/)

[Export](https://support.typora.io/Export/)

<div style="height:100px;width:100%;"><div style="height: 100%;width: 100px;float:left;border-top:1px solid #ddd;border-bottom:1px solid #ddd;border-left:1px solid #ddd;border-top-left-radius:5px;border-bottom-left-radius:5px;background-color:#f8f8f8;"><a href="https://www.w3school.com.cn/cssref/css_selectors.asp" style="padding:0;"><img src="https://www.w3school.com.cn/ui2019/logo-16-red.png" style="width:94px;height:94px;object-fit:cover;margin:2px;border:1px solid #f8f8f8;border-radius:5px;"/></a></div><div style="height: 100%;width: 40%;float:left;border-top:1px solid #ddd;border-bottom:1px solid #ddd;border-right:1px solid #ddd;border-top-right-radius:5px;border-bottom-right-radius:5px;background-color:#f8f8f8;"><div style="width: 100%;height:36px;font-size:12px;font-weight:bold;padding:4px;overflow:scroll;padding-left:10px;padding-right:10px;margin-top:2px;margin-bottom:3px;">CSS 选择器参考手册</div><div style="width: 100%;height:37px;font-size:11px;font-weight:normal;padding:3px;overflow:scroll;border-top:1px solid #ddd;color:#999;padding-left:5px;padding-right:10px;"></div><div style="width: 100%;height:15px;font-size:10px;font-weight:normal;overflow:hidden;color:#666;text-align:right;padding-left:5px;padding-right:15px;">www.w3school.com.cn</div></div></div>

