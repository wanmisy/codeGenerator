
# dataSource
* 类型：DataSourceConfig
* 默认值：null
* 数据源配置，通过该配置，指定需要生成代码的具体数据库

# strategy
* 类型：StrategyConfig
* 默认值：null
* 数据库表配置，通过该配置，可指定需要生成哪些表或者排除哪些表，具体请查看 数据库表配置

#packageInfo
* 类型：PackageConfig
* 默认值：null
* 包名配置，通过该配置，指定生成代码的包路径，具体请查看 包名配置

# template
 * 类型：TemplateConfig
 * 默认值：null
 * 模板配置，可自定义代码生成的模板，实现个性化操作
 
# globalConfig
* 类型：GlobalConfig
* 默认值：null
* 全局策略配置，具体请查看 全局策略配置

# injectionConfig
 * 类型：InjectionConfig
 * 默认值：null
 * 注入配置，通过该配置，可注入自定义参数等操作以实现个性化操作，具体请查看 注入配置

## 参考 http://mp.baomidou.com/guide/generator.html