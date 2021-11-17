---
title: Get authorization keys
permalink: /docapis_get_auth_keys.html
categories:
- api-doc
keywords:
course: "Documenting REST APIs"
weight: 2.1
sidebar: docapis
section: likeadeveloper
path1: /likeadeveloper.html
---

Almost every API has a method in place to authenticate requests. You usually have to provide an API key in your requests to get a response. Although we'll dive into [authentication and authorization](docapis_more_about_authorization.html) later, we need to get some API keys now to make requests to our weather API.

* TOC
{:toc}

## Why requests need authorization

Requiring authorization allows API publishers to do the following:

* License access to the API
* Rate limit the number of requests
* Control availability of certain features within the API, and more

To run the code samples in this course, you will need to use your own API keys, since these keys are usually treated like passwords and not given out or published openly on a web page.

{: .note2}

{% include content/activities/get_authorization_keys.md %}

## Get the Aeris Weather API secret and ID {#aeris_weather_apikey}

Now for contrast, let's get the keys for the Aeris Weather API. The Aeris Weather API requires both a secret and ID to make requests.

1.  Go to [http://www.aerisweather.com](http://www.aerisweather.com) and click **Sign Up** in the upper-right corner.
2.  Under **Developer**, click **TRY FOR FREE**. (The free version limits the number of requests you can make.)
3.  Enter a username, email, and password, and then click **SIGN UP FOR FREE** to create an Aeris account. Then sign in.
4.  After you sign up for an account, click **Account** in the upper-right corner.
5.  Click **Apps** (on the second navigation row, to the right of "Usage"), and then click **New Application**.

    {% include course_image.html size="700px" url="https://www.aerisweather.com/account/apps" border="" filename="aerisaccount" ext_print="png" ext_web="png" alt="Aeris account" caption="Aeris account" %}

6.  In the Add a New Application dialog box, enter the following:
    * **Application Name**: My biking app (or something)
    * **Application Namespace**: localhost
7.  Click **Save App**.

After registering your app, you should see an ID, secret, and namespace for the app. Copy this information into a place you can easily access since you'll need it to make requests.

{: .tip}
Keep in mind how users authorize calls with an API &mdash; this is something you usually cover in API documentation. Later in the course, we will dive into [authorization methods](docapis_more_about_authorization.html) in more detail.

{: .note2}

## Make sure you have a text editor

{: .note3} In the upcoming activities, you'll work with code in a text file. When you're working with code, you use a text editor (to work in plain text) instead of a rich text editor (which would provide a WYSIWYG interface). Here are a few choices for text editors:

* [Sublime Text](http://www.sublimetext.com/) (Mac or PC)
* [TextWrangler](http://www.barebones.com/products/textwrangler/) or [BBEdit](http://www.barebones.com/products/bbedit/) (Mac)
* [WebStorm](https://www.jetbrains.com/webstorm/) (Mac or PC)
* [Notepad++](https://notepad-plus-plus.org/) (PC)
* [Atom](https://atom.io/) (Mac or Windows)
* [Komodo Edit](http://komodoide.com/komodo-edit/) (Mac or PC)
* [Coda](https://panic.com/coda/) (Mac)

These editors provide features that let you better manage the text. Choose the one you want. (My preference is to use Sublime Text when I'm working with independent code samples, and Atom when I'm working with Jekyll projects.) Avoid using TextEdit since it adds some formatting behind the scenes that can corrupt your content.

{: .note2}
