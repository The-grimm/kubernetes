1. $ kubectl create -f rsvp-db.yaml

2.create a Service named mongodb to access the backend:
  $ kubectl create -f rsvp-db-service.yaml
  
3. $ kubectl create -f rsvp-web.yaml

4. Create a service for fronend:
  $ kubectl create -f rsvp-web.yaml
