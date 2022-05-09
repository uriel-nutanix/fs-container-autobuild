FROM gcr.io/google.com/cloudsdktool/google-cloud-cli:emulators

ENV FS_PORT=8090
CMD exec gcloud beta emulators firestore start --host-port=0.0.0.0:${FS_PORT}