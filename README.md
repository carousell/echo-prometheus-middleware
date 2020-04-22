To use, simply
```
import (
  echoprometheus "github.com/701search/echo-prometheus-middleware"
)

prometheusMiddleware := echoprometheus.NewPrometheus("")
prometheusMiddleware.Use(e)
```
