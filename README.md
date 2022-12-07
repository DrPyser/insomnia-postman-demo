# Postman & Insomnia overview

* Summarize insomnia features
* Summarize Postman features
* Show core features
* Compare

## Install
* insomnia: https://docs.insomnia.rest/insomnia/install
    * nix/devbox: insomnia
    * archlinux: aur/insomnia
    * debian-based: snap

* postman: https://www.postman.com/downloads/
    * archlinux: aur/postman-bin
    * nix/devbox: postman (requires NIXPKGS_ALLOW_UNFREE=1)
    * debian-based: snap

## Insomnia
https://insomnia.rest/products/insomnia
https://github.com/Kong/insomnia

* API client GUI tool
* Open source
* Owned & Maintained by KongHQ(Kong API gateway/service mesh, mockbin)

### Core Features(free, open-source version)
* Multi-protocol support: HTTP, gRPC, Websocket, SOAP, GraphQL
* HTTP features
    *  Cookies
    *  auth methods(oauth2, basic auth, bearer token, AWS IAM, ...)
    *  body content formatting/syntax support
    *  response body filtering with JSONPath(https://www.npmjs.com/package/jsonpath-plus)
* Parameterization(json "environments")
    * dynamic variables(requests and responses processed into variables)
* Syncing & Versioning through git/github,
* exporting and sharing
* importing from various collection formats
    * backward compatible insomnia formats
    * compatible with postman format, Swagger/OpenAPI, HAR, cURL, WSDL
* automated test suite
* openapi spec editor(with rendered preview)
* Export into code snippets for language and tooling of choice(shell/curl, shell/wget, language of choice)
* plugins for extensions

### Enterprise/non-free features
https://insomnia.rest/pricing

* secure(E2EE) sharing, syncing between users in a team, between devices
 

## Postman
https://www.postman.com/
https://learning.postman.com/docs/getting-started/introduction/

* Postman API client part of Postman API platform
* Free, closed-source version available
* Expanded tooling catalog: https://www.postman.com/product/tools/
* Postman *api client*

### Core Features(free)
* insomnia features
* graphic novel: https://api-first-world.com/
* body format support: form data, url encoded form, raw(text), binary(from file), graphql
* js scripting hooks
    * pre-request script: arbitrary code execution before request is sent
    * tests: arbitrary code execution after request is sent
    * response data visualization: build a frontend from response data
        * https://learning.postman.com/docs/sending-requests/visualizer/
        * handlebarjs templates
* web version with free account

### Non-free features
https://www.postman.com/pricing/
https://www.postman.com/postman-enterprise/

* Synced workspaces & data

## Comparison
### Common features/goals
* User/Developer-friendly GUIs for simplifying manual API interactions
* GUI to help design APIs interactively through openapi specs
* Export & share collected requests & responses, enable collaboration
    * shared workspace

### XOR
* Cost/Freedom
    * Postman: free version available
    * Insomnia: free, open source version available
    * both offer paying features with multiple subscription plans & enterprise versions
* Postman: part of a platform of tooling for API development
* Postman: more advanced features for automation(scripting), visualization

