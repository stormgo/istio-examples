

##### Istio Makefile

```
.PHONY: galley-test2
galley-test2: depend
	go test -count=1 -v ./galley/pkg/source/kube -run Builtin
```
