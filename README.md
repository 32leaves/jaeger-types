# jaeger-types
Typescript typings for jaeger-client-node lib

NOTES:
- we only need to care about the initTracer function
- cast the return value to `<opentracing.Tracer>` and use opentracing typings from then on
