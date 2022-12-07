---
title: Post with Header Image
tags: ssh
article_header:
  type: cover
  image:
    src: /screenshot.jpg
---

A Post with Header Image, See [Page layout](https://kitian616.github.io/jekyll-TeXt-theme/samples.html#page-layout) for more examples.

<!--more-->

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but ...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

SSH for GitHub
  
```shell
cd ~/.ssh
ssh-keygen -t rsa -C "my@pers.on.al" -f "github-ibrahimlawal"
ssh-keygen -t rsa -C "my@wo.rk" -f "github-ibrahimlawal-paystack"
ssh-keygen -t rsa -C "moi@pl.ay" -f "github-ibraheemweynodey"
```

  In ~/.ssh/config
  #ibrahimlawal account

    Host github.com-ibrahimlawal
      HostName github.com
      User git
      IdentityFile ~/.ssh/github-ibrahimlawal
  #ibrahimlawal-paystack account
  Host github.com-ibrahimlawal-paystack
      HostName github.com
      User git
      IdentityFile ~/.ssh/github-ibrahimlawal-paystack
#ibraheemweynodey account
Host github.com-ibraheemweynodey
    HostName github.com
    User git
    IdentityFile ~/.ssh/github-ibraheemweynodey

Usage:
$ git config user.email "my@pers.on.al"
$ git config user.name "Ibrahim Lawal"
$ git config user.email "my@wo.rk"
$ git config user.name "Ibrahim Lawal"
$ git config user.email "my@pl.ay"
$ git config user.name "Ibrahim wey no dey"


Account 1 # account_1
  Host gitlab.com-account_1
  HostName gitlab.com
  User git
  PreferredAuthentications publickey
  IdentityFile ~/.ssh/id_rsa_account_1

Account 2 # Account2
  Host gitlab.com-Account2
  HostName gitlab.com
  User git
  PreferredAuthentications publickey
  IdentityFile ~/.ssh/id_rsa_Account2

Account 3 # Account_3
  Host github.com-Account3
  HostName github.com
  User git
  PreferredAuthentications publickey
  IdentityFile ~/.ssh/id_rsa_Account_3



bundle config set --local path 'vendor/bundle'

