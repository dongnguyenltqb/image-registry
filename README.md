# image-registry

1. To generate account for registry
    ```shell
        docker run --entrypoint htpasswd httpd:2 -Bbn testuser testpassword > auth/htpasswd
    ```
2. Run
    ```shell
    docker-compose up -d
    ```
3. UI
    - visit `http://localhost:5009`
