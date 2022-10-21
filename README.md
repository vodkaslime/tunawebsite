To serve on Google Cloud GCS:

```
gsutil mb gs://tuna-cloud.com

gsutil web set -m index.html -e 404.html gs://tuna-cloud.com

gsutil defacl ch -u allUsers:R gs://tuna-cloud.com

gsutil iam ch allUsers:objectViewer gs://tuna-cloud.com

gsutil rsync -R public gs://tuna-cloud.com
```