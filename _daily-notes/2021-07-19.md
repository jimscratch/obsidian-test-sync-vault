---
Creation Date: <% tp.file.creation_date() %>
Last Modified: <% tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %>
Author: Jimmy Briggs <jimbrig1993@outlook.com>
Tags: [ "#Daily-Note" ]
Alias: <% tp.file.creation_date() %>
---

<< [[<% tp.date.now("YYYY-MM-DD", -1) %>]] | [[<% tp.date.now("YYYY-MM-DD", 1) %>]] >>

# <% tp.date.now("dddd, MMMM YYYY") %>

## Daily Quote & Image

### Quote `ris:ChatQuote`

```ad-quote
title: Daily Quote

<% tp.web.daily_quote() %>

```

### Image `ris:Image2`

<% tp.web.random_picture("400x400", "landscape,water,space,sun,skyline") %>

***
Links: [[Daily Notes Index]]
Sources: 