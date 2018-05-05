# JSON shema configuration

The WPO optimization plugins are based on JSON schema configuration that enables full control of the optimization using a simple JSON document.

This directory contains the JSON schema source files that are used by the plugin to verify and store the configuration. The files can be used to understand the many avaialable, and potentially undocumented, options.

## Advantages of JSON configuration

The JSON schema based configuration provides several great advantages for website performance optimization.

#### Advantage 1: platform independent

The WPO plugins are not like most other WordPress plugins. The plugins are purely focused on optimization technologies instead of controlling / modifying WordPress. This makes the underlaying optimization technologies platform independent. The same technologies and configuration can be used on Magento, a Microsoft .NET CMS or a Node.js based CMS. 

#### Advantage 2: saving time

The JSON configuration enables much quicker tuning for experts and it enables to quickly copy and paste a proven configuration to a new website.

#### Advantage 3: public optimization knowledge and help

The JSON configuration can be easily shared and discussed on forums, enabling to build public knowledge about the options. Because the optimization configuration is independent from WordPress, the knowledge will be valid for any platform which increases the value, making it more likely to be able to receive free help.

#### Advantage 4: a basis for Artificial Intelligence

The JSON configuration concept, when completed, enables fine grained tuning of the optimization, not just on a per page level but even per individual visitor or based on the environment. This will enable to optimize the performance based on the [save-data](https://developers.google.com/web/updates/2016/02/save-data) header or for example to change an individual CSS optimization setting specifically for iPhone 5 devices. 

While the JSON shema concept makes it more easy for human editors to perform such complex environment based optimization, it also provides a basis for a future AI to take full control over the optimization, enabling to achieve the absolute best website performance result for each individual user automatically.

While the AI may one day supplement or take over, experts will have a clear view of what the AI is doing (it produces simple JSON that is used by humans) and will be able to override at any point.