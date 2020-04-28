origin from chotot code

To use, simply
```
import (
  echoprometheus "github.com/carousell/echo-prometheus-middleware"
)

prometheusMiddleware := echoprometheus.NewPrometheus("")
prometheusMiddleware.Use(e)
```
