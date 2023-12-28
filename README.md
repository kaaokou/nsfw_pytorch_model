nsfw_pytorch_model 

#### 数据说明

#### 数据主要来源四个地方

- [nsfw_data_scraper](https://github.com/alex000kim/nsfw_data_scraper)
- [nsfw_data_source_urls-master](https://github.com/EBazarov/nsfw_data_source_urls)
- imagenet1000 
- Danbooru 

|          | 数量   | index |
| -------- | ------ | ----- |
| drawings | 244717 | 0     |
| hentai   | 126429 | 1     |
| neutral  | 868192 | 2     |
| porn     | 294488 | 3     |
| sexy     | 5669   | 4     |

### 使用方法

- 见demo.ipynb

### 模型表现

mobilenet_v3_large_nsfw_base_v1：平均acc 96.05%

resnet101_nsfw_base_v1:平均acc
