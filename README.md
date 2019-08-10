# istio-examples

kubectl -n istio-system get pod -l app=grafana

kubectl -n istio-system port-forward [graphana-pod-name] 3000:3000

kubectl -n istio-system get pod -l app=jaeger

kubectl -n istio-system port-forward [jaeger-pod-name] 16686:16686

oc get svc istio-ingressgateway -n istio-system
