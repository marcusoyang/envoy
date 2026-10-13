The native gRPC client now reports ``INTERNAL`` when an ``OK`` response ends with an incomplete message
frame. Explicit non-OK statuses and trailing metadata are preserved.
