---
title: Developer Focused Examples
page_title: Developer Focused Examples
description: Developer Focused Examples
slug: radpersistenceframework-sdk-examples
tags: sdk,examples
published: True
position: 1
---

# Developer Focused Examples

The [Telerik XAML SDK repository](https://github.com/telerik/xaml-sdk/tree/master/) provides additional demos for most of the Telerik UI for {% if site.site_name == 'WPF' %}WPF{% endif %}{% if site.site_name == 'Silverlight' %}Silverlight{% endif %} controls. The examples demonstrate many specific user case scenarios, that might be really helpful. In this article you can find the complete list of all SDK examples for __RadPersistenceFramework__.

## List of all RadPersistenceFramework SDK examples:

{% if site.site_name == 'WPF' %}

* __[GridView serialization](https://github.com/telerik/xaml-sdk/tree/master/PersistenceFramework/GridViewSerialization)__ - This example demonstrates custom serialization of properties for the RadGridView control.Sorting and Grouping, width and position of the columns will be serialized.
* __[Native controls](https://github.com/telerik/xaml-sdk/tree/master/PersistenceFramework/NativeControls)__ - This example demonstrates persisting and restoring properties of the intrinsic Silverlight or WPF controls.
* __[Zip integration](https://github.com/telerik/xaml-sdk/tree/master/PersistenceFramework/ZipIntegration)__ - This example demonstrates the integration between the Persistence framework and the Zip library for providing an output stream object with compressed size.
{% endif %}
{% if site.site_name == 'Silverlight' %}
* __[GridView serialization](https://github.com/telerik/xaml-sdk/tree/master/PersistenceFramework/GridViewSerialization)__ - This example demonstrates custom serialization of properties for the RadGridView control.Sorting and Grouping, width and position of the columns will be serialized.
* __[Native controls](https://github.com/telerik/xaml-sdk/tree/master/PersistenceFramework/NativeControls)__ - This example demonstrates persisting and restoring properties of the intrinsic Silverlight or WPF controls.
* __[Zip integration](https://github.com/telerik/xaml-sdk/tree/master/PersistenceFramework/ZipIntegration)__ - This example demonstrates the integration between the Persistence framework and the Zip library for providing an output stream object with compressed size.
{% endif %}

>You can also check the [SDK Samples Browser]({%slug sdk-samples-browser%}) that provides a more convenient approach in exploring and executing the examples in the Telerik XAML SDK repository. The SDK Samples Browser application is available for download from [this link](http://demos.telerik.com/xaml-sdkbrowser/).