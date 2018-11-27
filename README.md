# temp-js

mos command to use


#setup wifi and google cloud

mos wifi ssid passwrd

mos gcp-iot-setup --gcp-project tempsensor-221722 --gcp-region us-central1 --gcp-registry weather-report

#glcoud 
gcloud beta pubsub subscriptions pull --auto-ack weather-sub
