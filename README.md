### Hi there 👋

<!--
**vdbulcke/vdbulcke** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

#### Projects 

##### OIDC/IAM

- [oidc-client](https://github.com/vdbulcke/oidc-client-demo): OIDC CLI client for testing/troubleshooting integration with OpenID Connect Providers (e.g. Forgerock, Azure AD, Okta, FAS, etc).
- [oidc-server](https://github.com/vdbulcke/oidc-server-demo): Mock OIDC server for testing integration with OIDC Relying Party (i.e. can be used to mock response from OIDC Providers in dev environments). 
- [cert-monitor](https://github.com/vdbulcke/cert-monitor): Both CLI and monitoring server for discovering X509 certificates from various sources: TLS, LDAPS, SAML XML Metadata, OIDC JWK URIs, and expose certificates expiration dates as Prometheus metric for monitoring and alerting. As CLI can be used to extract, parse and display X509 certificates from remote sources.



##### Hashicorp Vault

- [terraform-vault-sample](https://github.com/vdbulcke/terraform-vault-sample): Sample Vault configuration in Terraform and tutorial guides to kickstart your Vault setup. 
- [vault-token-monitor](https://github.com/vdbulcke/vault-token-monitor): Monitoring server to track Vault tokens' expiration  TTLs and exposing them as Prometheus metrics. Additionally adds the ability to auto-renew Vault [periodic tokens](https://developer.hashicorp.com/vault/docs/concepts/tokens#periodic-tokens).
- [hc-vault-util](https://github.com/vdbulcke/hc-vault-util): CLI tool for Vault Transit secret engine: import private key into Vault Transit, and generate CSR from a Vault Transit backed private key. Vault TUI for kv2 secret engine.
- [secret-agent](https://github.com/vdbulcke/secret-agent/tree/feature/vault) Fork of Forgerock secret agent kubernetes operator to add Hashicorp Vault as a KMS.

##### GitOps 

- [json-patcher](https://github.com/vdbulcke/json-patcher): CLI (and interactive terminal UI) tool for managing, previewing, and applying JSON Patch RFC6902 (i.e. same as Kustomize but for arbitrary JSON).


##### Algo

- [foo-bar-challenges](https://github.com/vdbulcke/foo-bar-challenges): Algorithm challenges from my Google Foobar participation.
