# list

## 本地化
1. 了解国际标准：
    1. [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes)
  2. [ISO 3166-1](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)
  3. [ISO 15924](https://en.wikipedia.org/wiki/ISO_15924)
2. 了解本地化相关规范/库：
  1. [CLDR](https://www.unicode.org/cldr/)：Common Locale Data Repository，即通用语言环境数据仓库，是Unicode组织维护的，包含各语言的本地化数据；
  2. [ICU](https://icu.unicode.org/)：International Components for Unicode，是一套广泛应用的开源跨平台库，为软件提供Unicode和本地化支持,CLDR是其数据来源；
  3. [Intl](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl): 浏览器内置的国际化API，是ICU的JS实现，提供了日期、时间、数字、货币等格式化功能；
3. 简单阿拉伯语特性(RTL)、不同于语言下的格式化区别；

## SEO
1. 主要遵循 https://developers.google.com/search/docs/fundamentals/seo-starter-guide?hl=zh-cn#simpleurlsconveyinfo
2. 其次 也看一下https://developers.google.com/search/docs/specialty/international/localized-versions?hl=zh-cn
3. 了解web vitals各项评分及优化方式，尤其INP和LCP；

## 设计系统
1. C端：
  1. 了解响应式UI的方式（非国内PC/H5写两套的方式）；
  2. 了解Design token的理念，国内可以参考阿里的Fusion，国外可以参考[谷歌](https://m3.material.io/foundations/design-tokens/overview)；
  3. 了解CSS变量的使用，以及高级Less语法；
  4. 了解iconfont的原理、常见问题、业界方案；
  5. 了解E2E测试方案；
2. B端：
  1. 了解antd的使用；
  2. 熟练使用Cursor；

## 合规
1. 了解各地区对数据使用和隐私的要求，比如欧盟的GDPR，可以参考[该网页非中国部分](https://www.adpchina.com/resources/articles-and-insights/articles/p/privacy-laws-in-the-world.aspx)；
2. 了解cookie的有效期、分类、续期、管理，以及各地的要求，以及专门做这些的第三方，如onetruet；
3. 大概了解各地区对crypto的的政策和态度；

## 安全
1. 了解业界设备指纹的方案，它能解决的问题、它无法解决的场景；
2. 了解业界防DDOS的手段；
3. 了解业界对页面做各类篡改检查的琐碎手段；
4. 了解XSS，并考虑如何在为团队提供基建的维度 来尽可能保证安全性；
5. 了解AES加密，Sbox的作用；

## 其他
1. 了解web worker、WASM；
3. 各项浏览器存储方式，storage,cookie, indexeddb;
4. 简单了解谷歌插件的机制和限制；
5. 了解Figma插件的机制、限制、能做的事儿；






