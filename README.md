# Using CI/CD github actions

- SSH KEY doesn't work yet


        host: ${{ secrets.SSH_HOST }}
        port: ${{ secrets.SSH_PORT }}
        username: ${{ secrets.SSH_USERNAME }}
        key: ${{ secrets.SSH_PRIVATE_KEY }}
        # password: ${{ secrets.SSH_PASSWORD }}