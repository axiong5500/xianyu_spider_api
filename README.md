## 介绍

`Xianyu Spider API` 是一个用于爬取闲鱼 APP 数据的项目，提供对闲鱼商品数据的访问和分析。你可以通过 API 获取商品的详细信息，包括标题、价格、图片链接和所在地区等。本 API 免费提供，旨在帮助开发者和数据分析师更方便地获取闲鱼平台的数据。

**声明**：本项目仅用于学习和研究目的，绝不用于任何违法活动。用户应遵守相关法律法规，合理合法使用本 API。项目作者不对使用本 API 进行的任何违法活动或其后果承担责任。如果本项目内容涉及任何版权或其他法律问题，请及时联系我，我们将会进行处理和删除。

## 数据展示

项目提供了一个简洁的界面来展示爬取的数据效果，你可以通过以下链接查看效果演示视频：
[闲鱼数据效果演示](https://youtu.be/LL1ilLlo-7Q)

![Xianyu Data](https://github.com/user-attachments/assets/d0b2109e-ddaf-43e3-bcfa-190625afc31e)

## API 说明

| 请求方式 | URL                  | 参数     | 说明                                            |
|----------|----------------------|----------|-------------------------------------------------|
| `GET`    | `/api/items`         | 无       | 返回所有爬取到的商品数据列表。                   |
| `GET`    | `/api/items/{id}`    | `id`     | 根据提供的商品 `id` 返回该商品的详细信息。       |
| `POST`   | `/api/items`         | 无       | 提供商品数据（如标题、价格、图片链接等），在数据库中新增一条商品记录。 |
| `DELETE` | `/api/items/{id}`    | `id`     | 根据提供的商品 `id` 删除对应的商品数据。         |

## 许可证

此项目使用 [MIT License](LICENSE) 许可。

## 联系方式

如果你有任何问题、建议，或涉及侵权问题，请通过以下方式联系我：

- 邮箱: xianyuapi@protonmail.com
- GitHub Issues: [GitHub Issues](https://github.com/yourusername/xianyu_spider_api/issues)
