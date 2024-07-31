# Travel Buddi

## Add a new post
- Right click on _posts
- New file
- 2024-07-24-newpost.md

## Add a image to a text
```
![This is an Image](/assets/images/image.jpg)
```

## Link a post
```
<a href="{% post_url 2024-03-31-post-name %}">Link to a post</a>.
```

## Link a section inside a post
Define section where to go:
```
### Marrakesch: Die rote Stadt {#marrakesch}
```
Go there:
```
[Link to the subsection](#marrakesch)
```

## Images with rounded border
```
<a href="url"><img src="/assets/images/Marokko2.jpg" style="border-radius:2%"></a>
```

## Three images next to each other
```
<a href="url"><img src="/assets/images/Mirleft.jpg" style="border-radius:2%; width:30%"></a>
<a href="url"><img src="/assets/images/Mirleft.jpg" style="border-radius:2%; width:30%"></a>
<a href="url"><img src="/assets/images/Mirleft.jpg" style="border-radius:2%; width:30%"></a>
```

## Markdown cheat sheet
Headings
```
# H1
## H2
### H3
```
Bold Text
```
**bold text**
```

Italic
```
*italicized text*
```

List
```
- First item
- Second item
- Third item
```



## Run locally
```
bundle install
bundle exec jekyll serve --no-watch
```
