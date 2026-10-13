Added native unary gRPC callouts for HTTP dynamic modules and the Rust SDK. Callouts use configured
HTTP/2 clusters and include request metadata, both response metadata blocks, signed terminal status,
finite whole-response deadlines, message size limits, and cancellation when the parent filter is
destroyed. See :ref:`dynamic modules <arch_overview_dynamic_modules>`.
