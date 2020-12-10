# jenkins-sessions

Validar un jenkins file:

```bash
curl --user admin:test -X POST -F "jenkinsfile=<./Jenkinsfile" http://localhost:8080/pipeline-model-converter/validate
```
