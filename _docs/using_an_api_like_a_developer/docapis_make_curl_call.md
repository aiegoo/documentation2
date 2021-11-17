---
title: "Make a curl call"
permalink: /docapis_make_curl_call.html
categories:
- api-doc
keywords:
course: "Documenting REST APIs"
weight: 2.4
sidebar: docapis
section: likeadeveloper
path1: /likeadeveloper.html
---

In this section, you'll use curl to make the same weather API requests you made previously with Postman. If you haven't installed curl, see [curl intro and installation](docapis_install_curl.html) first.

* TOC
{:toc}

{% include content/activities/make_curl_request.md %}

{: .note2}

{% include image_ad_right.html %}

## Note about single and double quotes with Windows curl requests {#windows_notes}

If you're using Windows to submit a lot of curl requests, and the curl requests require you to submit JSON in the [request body](docapis_doc_parameters.html#request_body), you might run into issues with single versus double quotes. The problem is that request body content is often formatted in JSON, which requires double quotes. Since you can't use double quotes inside of other double quotes, you'll run into issues in submitting curl requests in these scenarios.

{: .note2}

Here's the workaround. If you have to submit body content in JSON, you can store the content in a JSON file. Then you reference the file with an `@` symbol, like this:

```sh
curl -H "Content-Type: application/json" -H "Authorization: 123" -X POST -d @mypostbody.json http://endpointurl.com/example
```

Here curl will look in the existing directory for the `mypostbody.json` file. (You can also reference the complete path to the JSON file on your machine.)

{: .note2}
