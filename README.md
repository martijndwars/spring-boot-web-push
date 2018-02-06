# Spring Boot + Maven + Web Push

See `src/main/java/com/example/demo/SendController.java` and `src/main/resources/static/*`.

Note that the public key, generated at [web-push-codelab.glitch.me](https://web-push-codelab.glitch.me), is configured in two places:

* `src/main/java/com/example/demo/SendController.java` at line 17 & 18.
* `src/main/resources/static/push.js` at line 45.

## Usage

1. Run `mvn package && java -jar target/demo-0.0.1-SNAPSHOT.jar`
2. Open `http://localhost:8080/`
3. Allow the notification; the subscription field should be populated with a subscription in JSON notation
4. Click "Send a notification ..." to send a notification
5. A notification should appear within a second or so
