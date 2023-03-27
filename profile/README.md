**Lightweight mock PSR implementations tailored for simplified unit testing.**

Each of these libraries provides a mock of a particular PHP-FIG PSR implementation. This suite is largely intended for use in libraries like SDKs that accept PSRs implimentations by developers without requiring hard dependencies on specific implementations.

In some cases, these libraries also provide additional APIs that further simplify the unit testing experience.

This suite pairs nicely with the [PSR Discovery](https://github.com/psr-discovery) suite, which can automatically detect the presence of any of these mock implementations and prefer them during unit test runs without extra configuration.

---

These libraries are not produced or endorsed by, or otherwise affiliated with, the PHP-FIG.
