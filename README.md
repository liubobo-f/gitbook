---
description: Welcome to your team’s developer platform
layout:
  width: wide
  title:
    visible: false
  description:
    visible: false
  tableOfContents:
    visible: false
  outline:
    visible: false
  pagination:
    visible: false
  metadata:
    visible: true
metaLinks:
  alternates:
    - https://app.gitbook.com/s/2AwfWOGBWBxQmyvHedqW/
---

# 主页

## 帮助打工人实现生产力飞跃

提供全面的定制化培训与在线课程

<table data-view="cards"><thead><tr><th></th><th></th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td><strong>Power Query教程</strong></td><td>Get started with the developer platform in 5 minutes.</td><td><a href="https://app.gitbook.com/o/Z87x680ArP9YP4w4baNJ/s/VoC1S04V0JsuCMDYkUKe/">Documentation</a></td><td><a href=".gitbook/assets/no-code.jpg">no-code.jpg</a></td></tr><tr><td>Office<strong>全家桶教程</strong></td><td>Learn more about hosting the developer platform.</td><td><a href="https://app.gitbook.com/o/Z87x680ArP9YP4w4baNJ/s/VoC1S04V0JsuCMDYkUKe/">Documentation</a></td><td><a href=".gitbook/assets/hosted.jpg">hosted.jpg</a></td></tr><tr><td><strong>Power BI教程</strong></td><td>Browse, test, and implement APIs.</td><td><a href="https://app.gitbook.com/o/Z87x680ArP9YP4w4baNJ/s/QzrGlopgCB46dRYn9UJp/">API Reference</a></td><td><a href=".gitbook/assets/api-reference.jpg">api-reference.jpg</a></td></tr><tr><td>Power Automate教程</td><td></td><td></td><td></td></tr><tr><td>Python教程</td><td></td><td></td><td></td></tr><tr><td>Excel教程</td><td></td><td></td><td></td></tr></tbody></table>

{% columns %}
{% column %}
<figure><img src="https://gitbookio.github.io/onboarding-template-images/placeholder.png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
### 关于打工砖家刘波波

B站UP主身份、学员数量、擅长领域
{% endcolumn %}
{% endcolumns %}

{% columns %}
{% column %}
### 教程设计理念

Setting up your first API call should be the easiest part of getting started. With clear endpoints, copy-paste-ready examples, and quick authentication, you’ll be up and running in minutes—not hours.

No guesswork, no complexity—just your first successful call, fast.

<a href="https://app.gitbook.com/o/Z87x680ArP9YP4w4baNJ/s/VoC1S04V0JsuCMDYkUKe/" class="button primary" data-icon="rocket-launch">Get started</a> <a href="https://app.gitbook.com/o/Z87x680ArP9YP4w4baNJ/s/QzrGlopgCB46dRYn9UJp/" class="button secondary" data-icon="terminal">API reference</a>
{% endcolumn %}

{% column %}
{% code title="index.js" overflow="wrap" %}
```javascript
// Import the SDK
import ExampleAPI from "example-api";

// Initialize the client
const client = new ExampleAPI({ apiKey: "YOUR_API_KEY" });

// Send your first message
const response = await client.messages.send({
  message: "Hello, world!"
});

```
{% endcode %}
{% endcolumn %}
{% endcolumns %}
