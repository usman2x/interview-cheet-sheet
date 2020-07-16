### REST

- Representational state transfer (Architectural pattern of comunication between client and server)
- Underlying protocol security
- URI
- HTTP methods
- Idempotant methods do not change the state if applied multiple times
- Safe methods do not change the state
- Media types; xml, json, text etc
- Stateless
- Usually use in microservice architecture (Internal communication)

### SOAP

- Simple object access protocol
- WS-Security, Message level security
- Media types; XML only
- Transport handled by HTTP POST usually, XMLHttpRequest could be used from browser
- SOAP envelop, SOAP fault
- SOAP implementations; Apache Axis, JAX-WS
- WSDL Web service description language
- Usually use in enterprise level third party integration where request/response are complex
