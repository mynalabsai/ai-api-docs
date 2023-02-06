# Error handling

Gateway has two different transport channels: HTTP REST and GRPC. There is grpc-gateway that transforms HTTP traffic to grpc traffic, but it is still two different transport channels for uses.

Two transport channels are not compatible with their error handling, so we implement it on application level. With each respose we provide status code and error message. HTTP code 200 means transport was okay, application got request without problems. If request had invalid data on application layer, we will return `INVALID_ARGUMENT` / `INTERNAL` / `DEADLINE_EXCEEDED` in `statusCode`. Additional information can be found in `errorMessage`.


