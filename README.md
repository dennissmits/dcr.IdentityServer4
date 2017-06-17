# dcr.IdentityServer4
Dynamic Client Registration Endpoint for Identity Server4

Dynamic Client registration is an enpoint acording to the standard https://tools.ietf.org/html/rfc7591 for registration of new clients.
The endpoint will hopefully being incorporated in the discovery document so it's easier to figure out if there is an endpoint and how to reach out to that.

Goals:
- Automatic registration of new clients
- Registration based on "business" policies
  -- IP Ranges allowed clients
  -- Open duration set by an administration (routers WPS a like)
  -- should be easy to add new business rules, like the new authorizaion policy system
