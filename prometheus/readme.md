#prometheus各项配置文件
- job: 同一种类型的检测定义一个job即可
- targets: 在file_sd_configs或consul_sd_configs中为不同的team、集群、区域添加标签，以区分告警接受对象、告警分类
- rules: 相同类型的exporter设置同一个组，在警报里细分对象
