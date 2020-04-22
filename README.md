To use, simply
```
import "git.chotot.org/go-common/echopprof"


prometheusMiddleware := echoprometheus.NewPrometheus("")
prometheusMiddleware.Use(e)
```