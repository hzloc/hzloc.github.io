---
title: 'Automated Database Migrations'
date: '2024-08-08T13:01:44+02:00'
# weight: 1
# aliases: ["/first"]
tags: ["first"]
author: "hzloc"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Desc Text."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/<path_to_repo>/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---
# Why do we need it?
As a data engineer, we cannot imagine our life without a database at this point. We plan our data
schema, and proceed to create it, for a while life is wonderful and nothing is required from us.
As we approach to the expiry date, the update is inevitable. But how we gonna do it? 
Is it enough to create schemas using cli, or a tool such as Dbeaver to run a few sql scripts
manually. Got what we desired and call it a day? I'd say maybe 20 years ago it was the case,
it is not most definitely now. You need to keep track of the changes you've made. Well it is possible
to create a new .docx file and throw the lines of the sql there so you can see the changes, though
it is not fancy, and fancy is what we do here. Jokes aside, maybe you've decided to use a tool alembic
to automatically run the migrations with versioning. Awesome choice, so let's go and desing our
postgres database which we gonna run on the cloud.

<mark>To be continued...</mark>