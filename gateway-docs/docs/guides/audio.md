# Audio

There are several ways audio can be represented.

## Bytes

You can send video in bytes, wav. Either base64 (REST) or raw bytes (GRPC) or file macros (REST, [read here](./macros.md))

```jsx
"audio": {
    "format": "BYTES",
    "data": "$nevergonnagiveyouup" // file macros
}
```

## Url

You can pass an audio with url, f.e. to object storage.

```jsx
"audio": {
    "format": "URL",
    "url": "https://open.spotify.com/track/4cOdK2wGLETKBW3PvgPWqT?autoplay=true"
}
```

## Generated

You can create hidden requests with generate-audio requests, such as `GENERATE_TTS` and `GENERATE_VC`

```jsx
"audio": {
    "format": "GENERATE_TTS",
    "text": "i am the president of the united states",
    "speaker": {
        "name": "obama"
    }.
    "configuration": {
        "speed": 0.8
    }
}
```

```jsx
"audio": {
    "format": "GENERATE_VC",
    "speaker": {
        "name": "obama"
    },
    "audio": {
        "format": "BYTES",
        "data": "$nevergonnagiveyouup"
    }
    "configuration": {
        "speed": 0.8
    }
}
```

Looking at `GENERATE_VC`, we expect a really good question to be asked - wait, is this a recursive type? Well, yes, but we restrict it to level-two depth, so `"audio": {"audio": {"audio": {}}}` will throw `INVALID_ARGUMENT` in response