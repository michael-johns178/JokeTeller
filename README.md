
# Joke Teller

Joke Teller is a JavaScript Responsive and Mobile Friendly program that allows text to speech.

## Acknowledgements

 - [ZTM] (https://zerotomastery.io)
 - [w3Schools] (https://www.w3schools.com)
 - [Rapid API] (https://rapidapi.com/hub)
 - [Voice RSS API] (https://www.voicerss.org)
 - [Joke API] (https://sv443.net/jokeapi/v2/)
 - favicon from ZTM 
 - Working Doc from ZTM 

## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.

