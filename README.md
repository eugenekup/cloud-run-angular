# To Create an image

Run `gcloud builds submit --tag gcr.io/PROJECT-ID/cloud-run-angular`

## To Deploy

Run `gcloud run deploy cloud-run-angular --image gcr.io/PROJECT-ID/cloud-run-angular --platform managed --allow-unauthenticated`
