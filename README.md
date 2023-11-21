# SecPush
SecPush is an application to communicate passwords over the web. Links to passwords expire after a certain number of views and/or time has passed. It is based on the [Password Pusher](https://github.com/adesso-as-a-service/PasswordPusher) adaption of adesso-as-a-service.

## API
PasswordPusher allows creating passwords using the API endpoint. Please consider that passwords which have been created using the API will not benefit from the JavaScript E2E-encryption.
The following POST data is required for Content-Type: ´application/x-www-form-urlencoded´:
password[payload]: mypassword
password[expire_after_time]: 6
password[expire_after_views]: 2
