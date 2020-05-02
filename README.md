# cloud-run-cd

Continous Deployment For go-starter-service in Cloud Run
```
gcloud builds submit . --config cloudbuild.yaml --substitutions _IMGAGE_VERSION=<image_tag>,SHORT_SHA=<git_sha>
```
