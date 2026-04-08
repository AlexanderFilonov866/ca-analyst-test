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
      "name": "METRO",
      "logoUrl": "https://cdn.shop.ru/metro.png",
      "delivery": {
        "type": "scheduled",
        "label": "Ближайшая доставка",
        "date": "today",
        "timeSlot": "21:00–23:00"
      },
      "link": "https://metro.ru"
    },
    {
      "id": "2",
      "name": "Ашан",
      "logoUrl": "https://cdn.shop.ru/auchan.png",
      "delivery": {
        "type": "scheduled",
        "label": "Ближайшая доставка",
        "date": "today",
        "timeSlot": "18:00–20:00"
      },
      "link": "https://auchan.ru"
    },
    {
      "id": "3",
      "name": "ВкусВилл",
      "logoUrl": "https://cdn.shop.ru/vkusvill.png",
      "delivery": {
        "type": "express",
        "label": "Быстрая доставка",
        "minMinutes": 20,
        "maxMinutes": 60
      },
      "link": "https://vkusvill.ru"
    },
    {
      "id": "4",
      "name": "Виктория",
      "logoUrl": "https://cdn.shop.ru/victoria.png",
      "delivery": {
        "type": "scheduled",
        "label": "Ближайшая доставка",
        "date": "today",
        "timeSlot": "17:00–19:00"
      },
      "link": "https://victoria.ru"
    }
  ]
}
