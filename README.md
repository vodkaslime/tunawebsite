To serve on Google Cloud GCS:

```
gsutil mb gs://www.tuna.com

gsutil web set -m index.html -e 404.html gs://www.tuna.com

gsutil defacl ch -u allUsers:R gs://www.tuna.com

gsutil iam ch allUsers:objectViewer gs://www.tuna.com

gsutil rsync -R public gs://www.tuna.com
```