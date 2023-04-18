
# Zumper Scraper Api

Since Zumper.com doesn’t provide an API, this API will help you to retrieve data from it.


## API Reference

#### Get properties

```http
  POST /properties/search
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `url` | `string` | **Required**. You can get the URL from /location_suggestion response  |
| `offset` | `int` | **Required**. to paginate  |
| `type` | `string` | **Required**. should be either "shortTerm" or "longTerm"  |

#### Get item

```http
  POST /properties/details
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. You'll get the id from "listing_id" key in "/properties/search"|
```http
  POST /location_suggestion
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `query`      | `string` | **Required**.



## RapidApi

https://rapidapi.com/brahimboussaa1998/api/zumper-com-scraper/


## Authors

- [@B9UU](https://github.com/B9UU)

