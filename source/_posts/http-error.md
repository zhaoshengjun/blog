title: ng2 error - No provider for Http
tags:
  - Angular 2
  - HTTP
categories:
  - Dev
date: 2016-05-08 11:06:00
---


This error is caused by, as you can guess, no Http provider in your ts/js file.

Here's a screenshot of my error message.
![http provider error](/images/http-error.png)

How to fix this? By adding the http provider of course. It's two lines of code.

1. `import { HTTP_PROVIDERS } from '@angular/http';`
2. add `HTTP_PROVIDERS` to your provider list.

![use http provider](/images/fix-http.png)
