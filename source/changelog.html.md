---
title: Front API Changelog

toc_footers:
  - <a href='/'>API reference</a>
  - <a href='plugin.html'>Plugin API documentation</a>
  - <a href='mailto:api@frontapp.com'>Contact us</a>

---

# API

## 10/05/2016 - Plugin draft

* [Plugin SDK] Support the copy of attachments when composing a draft (new, reply or forward)
* [Plugin SDK] Add a method to fetch the draft of the current conversation
* [Plugin SDK] Add a method to update a draft recipients and/or attachments
* [Plugin SDK] Add the `attachments` array to the message representation object
* [Plugin SDK] Add the `has_draft` boolean to the conversation representation object

## 08/19/2016 - Attachments

* [API] Add metadata (`is_inline` & `cid`) to attachments
* [API] Support of sending messages with attachments with a `multipart/form-data` request

## 03/07/2016 - API v2

* [API] Release of the API v2
* [API] Deprecation of the API v1
