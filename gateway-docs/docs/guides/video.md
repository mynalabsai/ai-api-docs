# Video

There are several ways video can be represented.

## Bytes

You can send video in bytes, mp4. Either base64 (REST) or raw bytes (GRPC) or file macros (REST, [read here](./macros.md))

```jsx
"video": {
    "format": "VIDEO_BYTES",
    "data": "$rickroll" // file macros
}
```

## Url

You can pass a video with url, f.e. to object storage.

```jsx
"video": {
    "format": "VIDEO_URL",
    "url": "https://www.youtube.com/watch?v=dQw4w9WgXcQ"
}
```

## Template

You can specify video template: either by name or by number.

```jsx
"video": {
    "format": "VIDEO_TEMPLATE",
    "template": {
        "id": 1940
    }
}
```