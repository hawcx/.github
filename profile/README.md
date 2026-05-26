<div align="center">

<img src="https://framerusercontent.com/images/LWvgxNenE5YA1kp60okH4QF8Mk.png" alt="Hawcx" width="640" />

### One identity platform. For humans. For agents. For what's next.

Passwordless security built on device-bound cryptography, quantum-resistant by design.

[hawcx.com](https://www.hawcx.com) · [Docs](https://docs.hawcx.com) · [Blog](https://www.hawcx.com/blog) · [Book a demo](https://calendly.com/team-hawcx)

</div>

---

## What is Hawcx

Hawcx is a Zero Knowledge Authentication (ZKA) platform that replaces passwords, passkeys, and shared secrets with **device-bound cryptographic proofs**. There is no credential database to breach, no phishable secret to harvest, and no centralized vault for attackers to target.

- **Cryptographic proof, not credentials** — Ed25519 device-bound keypairs with DPoP token binding ([RFC 9449](https://datatracker.ietf.org/doc/html/rfc9449))
- **Quantum-resistant by design** — crypto-agile foundation ready for NIST post-quantum algorithms
- **Built to outsmart automation** — device-bound architecture inherently resists AI-driven attacks, replay, and synthetic identity fraud
- **Drop-in federation** — OIDC and SAML integration with existing IAM platforms
- **SOC 2 Type II certified**

## Get started

Pick your platform. Each SDK ships with sample apps and integration guides.

| Platform | Repo | Status |
| --- | --- | --- |
| iOS | [`hawcx_ios_sdk`](https://github.com/hawcx/hawcx_ios_sdk) | Stable |
| Android | [`hawcx_android_sdk`](https://github.com/hawcx/hawcx_android_sdk) | Stable |
| React Native | [`reactnative_sdk`](https://github.com/hawcx/reactnative_sdk) | Stable |
| Flutter | [`flutter_sdk`](https://github.com/hawcx/flutter_sdk) | Stable |
| AI Agents | [`hawcx_agentic_sdk`](https://github.com/hawcx/hawcx_agentic_sdk) | Alpha |

### React quick look

```tsx
import { HawcxProvider } from '@hawcx/react';
import { LoginFlow } from './LoginFlow';

export function App() {
  return (
    <HawcxProvider config={{ configId: import.meta.env.VITE_HAWCX_CONFIG_ID }}>
      <LoginFlow />
    </HawcxProvider>
  );
}
```

Full integration walkthroughs live at **[docs.hawcx.com](https://docs.hawcx.com)**.

## Who Hawcx is for

| | |
| --- | --- |
| **Developers** | Modern APIs, native SDKs, deploy in weeks |
| **Security teams** | Eliminate credential breaches, cut help-desk burden 40–60%, strengthen compliance posture |
| **Businesses** | Faster onboarding, higher digital adoption, future-proof infrastructure |

Purpose-built for regulated industries: [Financial Services](https://www.hawcx.com/financialservices) · [Healthcare](https://www.hawcx.com/healthcare) · [Retail](https://www.hawcx.com/retail)

## Resources

- 📘 **[Documentation](https://docs.hawcx.com)** — integration guides, API reference, protocol details
- 📄 **[Whitepapers](https://www.hawcx.com/whitepapers)** — the Hawcx Protocol, post-quantum readiness, threat models
- ✍️ **[Blog](https://www.hawcx.com/blog)** — engineering posts and product updates
- 🤝 **[Partners](https://www.hawcx.com/partners)** — integration and channel partners
- 💼 **[Careers](https://www.hawcx.com/careers)** — we're hiring

## Talk to us

- **Demo:** [calendly.com/team-hawcx](https://calendly.com/team-hawcx)
- **Security disclosures:** security@hawcx.com
- **General:** admin@hawcx.com

---

<div align="center">

Built in Austin, TX · SOC 2 Type II certified · © 2026 Hawcx

</div>
