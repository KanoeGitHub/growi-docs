# Logging

Logger can provide more detailed information if configured. Logger configuration may be helpful in investigating a system clash and authentication failure.

## Changelog Level

Add log namespaces separated with a comma to the environment variable `DEBUG` and restart GROWI.

### Example

```
DEBUG=growi:routes:page,growi:routes:login-passport
```

## List of Major Log Namespaces

|GROWI tatget module|log namespaces|
|---|---|
|login/logout|`growi:routes:login,growi:routes:login-passport`|
|passport authentication (OAuth/LDAP)|`growi:service:PassportService`|
|user data operation|`growi:models:user*`|
|page operation|`growi:routes:page,growi:models:page`|
|save/retrieve configs|`growi:models:config,growi:service:Config*`|
|admin operation|`growi:routes:admin`|
|file upload|`growi:models:attachment,growi:service:fileUploader*`|
|full-text search|`growi:lib:search`|
|send mails|`growi:lib:mailer`|

###

## More

Refer to [Logger](/en/dev/tips/logger.html) in [Developers Guide](/en/dev/).
