# hummingbird
REST web service designed specifically for web interfaces designed to interact with Particle.io's Photon wi-fi module.

## API
| Resource Name | HTTP Verbs                                                                 | HTTP Methods                                                                                                   |
|:--------------|:---------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------|
| User          | create User<br>update User<br>delete User<br>view User                     | POST /user with Payload<br>PUT /user/123 with Payload<br>DELETE /user/123<br>GET /user/123                     |
| Token         | create Token<br>update Token<br>delete Token<br>view Token                 | POST /token with Payload<br>PUT /token/123 with Payload<br>DELETE /token/123<br>GET /token/123                 |
| Device        | create Device<br>update Device<br>delete Device<br>view Device             | POST /device with Payload<br>PUT /device/123 with Payload<br>DELETE /device/123<br>GET /device/123             |
| Operations    | create Operation<br>update Operation<br>delete Operation<br>view Operation | POST /operation with Payload<br>PUT /operation/123 with Payload<br>DELETE /operation/123<br>GET /operation/123 |
