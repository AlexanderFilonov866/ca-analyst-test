# Проектирование API

## Endpoint

GET /api/v1/partner-shops

---

## Пример ответа

```json
{
  "shops": [
    {
      "id": "1",
      "name": "Пятерочка",
      "imageUrl": "https://cdn.shop.ru/5ka.png",
      "rating": 4.5,
      "deliveryTime": "30-40 мин",
      "link": "https://5ka.ru"
    },
    {
      "id": "2",
      "name": "ВкусВилл",
      "imageUrl": "https://cdn.shop.ru/vkusvill.png",
      "rating": 4.8,
      "deliveryTime": "20-30 мин",
      "link": "https://vkusvill.ru"
    }
  ]
}
