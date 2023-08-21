# Quiz Demo

## Overview
This is a demonstration of the Quiz application which consists of a server-side component and a client-side component.

## Server

### Deployment

To publish the server, for instance, to Google Cloud Registry (GCR), use the following sample commands:

```
gcloud config set project quiz-49abd
gcloud builds submit --tag gcr.io/quiz-49abd/quiz_app
gcloud run deploy quiz-service --image gcr.io/quiz-49abd/quiz_app --platform managed --region us-central1 --allow-unauthenticated
```

### Running GCR Server Instance:

You can access the running GCR server instance at:

https://quiz-service-2fcpeakuua-uc.a.run.app/


## Client Application

The client-side of the Quiz application can be accessed through:

https://imedvedev75.github.io/quiz/


