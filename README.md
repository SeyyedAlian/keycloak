# keycloak

# Load keycloak 24.0.4 docker :
# With User: admin Pass: admin : 
# Part: 8080
sudo docker run -itd --name Alian -p 8080:8080 -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:24.0.4 start-dev
