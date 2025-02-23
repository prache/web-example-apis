# Example APIs 🐕

✨ Easy to fetch example APIs made for training purposes.

[🔗 GitHub Repository](https://github.com/neuefische/web-example-apis)

## 🎲 Status

### `GET` `/api/status`

Randomly returns status code 200 or error codes after a random delay.

```
https://example-apis.vercel.app/api/status
```

## 🙄 Bad Jokes

### `GET` `/api/bad-jokes`

Retrieve a list of bad jokes:

```
https://example-apis.vercel.app/api/bad-jokes
```

### `GET` `/api/bad-jokes/[id]`

Retrieve a bad joke for the given id:

```
https://example-apis.vercel.app/api/bad-jokes/1
```

### `GET` `/api/bad-jokes/random`

Retrieve a random bad joke:

```
https://example-apis.vercel.app/api/bad-jokes/random
```

## 🛒 Shopping Items

### `GET` `/api/shopping/categories`

Retrieve a list of shopping categories:

```
https://example-apis.vercel.app/api/shopping/categories
```

### `GET` `/api/shopping/items`

Retrieve a list of shopping items:

```
https://example-apis.vercel.app/api/shopping/items
```

## 🌤️ Weather

### `GET` `/api/weather`

Retrieve a seeded random weather for "europe" based on the current hour:

```
https://example-apis.vercel.app/api/weather
```

### `GET` `/api/weather/[location]`

Retrieve a seeded random weather for a location based on the current hour.

Only the following locations are supported:

```
https://example-apis.vercel.app/api/weather/europe
```

```
https://example-apis.vercel.app/api/weather/arctic
```

```
https://example-apis.vercel.app/api/weather/sahara
```

```
https://example-apis.vercel.app/api/weather/rainforest
```

## 🎨 Art

### `GET` `/api/art`

Retrieve a list of artworks:

```
https://example-apis.vercel.app/api/art
```
