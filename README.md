## Depurar en local

Podemos ejecutar el comando:

```bash
helm install --debug --dry-run --values .\eoloserver\values.yaml release-name .\eoloserver | code -
```
NOTA: Se nos abrira un tab em el VSCode donde podremos buscar lo que corresponda. Cuando cerremos ese tab la terminal nos volverá a responder. 