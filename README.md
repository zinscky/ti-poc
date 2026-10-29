# ti-poc

Static OIDC discovery + JWKS for a cidaas Trusted Issuer POC (k6 integration tests).

- Issuer: `https://zinscky.github.io/ti-poc`
- Discovery: `/.well-known/openid-configuration`
- JWKS: `/.well-known/jwks.json` (public key only, test-only keypair)

Register only on test tenants. Not for production use.
