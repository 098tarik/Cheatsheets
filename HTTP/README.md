# HTTP

## HTTP Request Structure

```
[method] [path] [protocol]
[HEADERS]
```

## Headers

### Mandatory Headers

HEADER | Definition
--- | ---
Host | Domain of the nameserver and the connection port.


### All Headers

HEADER | Description
--- | ---
Accept | Content-Types That can be given as response.
Accept-Charset | Charactersets that can be used.
Accept-Encoding | Compressions that can be used.
Accept-Language | Specifies human language that can be used.
Accept-Datetime | Version in time.
Authorization | Credentials that are attached to HTTP header.
Cache-Control | Flag for caching mechanisms.
Connection | How to maintain connection between devices when handling requests.
Cookie | HTTP cookie data.
Content-Length | Size request in bytes.
Content-MD5 | MD5 Sum for the Content.
Content-Type | Mime type of content.
Date | Time stamp for the message.
Expect | Server behaviors that the client wants.
Forwarded | If a message has passed through many client-servers, this will contain original client info.
From | An email of the user.
Host | Domain of the nameserver and the connection port.
If-Match | Call is only meant to be used if a message matches this field.
If-Modified-Since | Causes a 304 error when content is not changed since that.
If-None-Match | Maps 304 to Not Modified if content is unchanged.
If-Range | If unchanged, send missing parts.
If-Unmodified-Since | Only respond if message hasn't been modified since a specific tim.
Max-Forwards | Limit the number of times a message can be sent through gateways.
Origin | The request initiated for cross-origin resource sharing.
Pragma | Implementation-specific field
Proxy-Authorization | Credentials for any proxy
Range | Requests only a certain set of bytes.
Referer | The link to which the previous link was followed from.
TE | Technology encodings that users will accept.
User-Agent | String indicating user.
Upgrade | Ask server to Upgrade to a higher protocol (than the request protocol)
Via | List of proxies from which server was sent.
Warning | General Warning about problems with body.


### Non-Standard Headers


#### Accept Types


#### Warning Types





## Status Codes




