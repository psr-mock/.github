**Lightweight mock PSR implementations tailored to simplify unit testing.**

Each of these packages provides a mock of a particular PHP-FIG PSR implementation. It currently supports [PSR-18 HTTP Clients](https://github.com/psr-mock/http-client-implementation), [PSR-17 HTTP Factories](https://github.com/psr-mock/http-factory-implementation) and [PSR-7 HTTP Message](https://github.com/psr-mock/http-message-implementation) implementations, with more on the way.

This is largely intended for use in libraries like SDKs that consume PSRs implimentations without requiring hard dependencies on specific libraries. These libraries also provide additional APIs that further simplify unit testing, while strictly adhering to the PSR specification and offering the most accurate representation of what a real world usage will look like.

These packages pairs nicely with the [PSR Discovery](https://github.com/psr-discovery) suite, which can automatically detect the presence of any of these mock implementations in your development environment and will prefer them during unit test runs without extra configuration.

---

These libraries are not produced or endorsed by, or otherwise affiliated with, the PHP-FIG.
