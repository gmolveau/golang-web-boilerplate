# Golang web boilerplate/skeleton/starter project

features :

- ORM : pop ? sqlx ? go-pg ?
- i18n : github.com/gobuffalo/mw-i18n ?
- env : github.com/gobuffalo/envy ?
- dockerfile
- grift (https://github.com/markbates/grift)
- moteur template : plush ?
- templating avec import (cf. ogps pour le hack)
- session
- flash
- design pattern : hexa ? repository pattern ? both ?
- routes, controllers, views, models ?
- middlewares ?
- validation
- security headers
    - `c.Response.Out.Header().Add("X-Frame-Options", "SAMEORIGIN")`
    - `c.Response.Out.Header().Add("X-XSS-Protection", "1; mode=block")`
    - `c.Response.Out.Header().Add("X-Content-Type-Options", "nosniff")`
    - `c.Response.Out.Header().Add("Referrer-Policy", "strict-origin-when-cross-origin")`
- secret pour signer les cookies
- port
- prefix de cookie
- duree session
- format de la date et du temps (abstraction)
- logging
- tests fonctionnels
- authentification : https://github.com/markbates/goth
- migrations
