# Robocor - course robot project workflow

## Creating a secret in the cloud vault
The local robot used the file-based secret for the credentials. The robot in the cloud cannot access that file on your computer. You need to provide the credentials in the cloud.

- Navigate to Vault and click Add.
- Enter robotsparebin as the name (the name has to match the secret name in the robot script).
- Click Add item and enter username as the key and maria as the value.
- Click Add item and enter password as the key and thoushallnotpass as the value.
- Click Confirm to create the secret.
