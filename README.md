# ACTIV Financial Systems

ACTIV Financial Systems is a provider of real-time and historical financial market data, best known for the ACTIV Feed consolidated multi-asset feed and the OnePlatform. ACTIV was acquired by [Options Technology](https://www.options-it.com) in 2021 and its market data capabilities are delivered as part of the Options Atlas platform.

A live public developer surface remains: the **OnePlatform Web API (One API)** — a WebSocket/WebAssembly JavaScript API with a developer portal at [weboneapi.activfinancial.com](https://weboneapi.activfinancial.com/) (documentation, tutorials, examples, playground) and 25 first-party packages on npm under the [@activfinancial](https://www.npmjs.com/search?q=activfinancial) scope. Gateway hosts and credentials are provisioned per customer rather than self-serve. The API is a session contract (not REST), so no OpenAPI is published; the machine-readable contract is the TypeDoc JSON shipped in the `@activfinancial/one-api` package.

Profiled in the API Evangelist network via [apis.yml](apis.yml), with captured artifacts for packages, embeddable components, error/status codes, authentication, lifecycle, well-known probes, and domain security.

Source: portfolio company of [bessemer-venture-partners](https://github.com/api-evangelist/bessemer-venture-partners) — https://www.activfinancial.com
