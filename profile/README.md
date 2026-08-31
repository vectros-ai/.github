# Vectros

**The secure data, document, search, and AI back-end you build apps on.**

Vectros gives your application a typed data store, a document pipeline, hybrid
search (BM25 + vector with RRF fusion), and citation-grounded retrieval, with
multi-tenant isolation, scoped access keys, and a tamper-evident audit trail,
behind one coherent API.

## A first call

```ts
import { VectrosClient } from "@vectros-ai/sdk";

const client = new VectrosClient({
  environment: "https://api.vectros.ai",
  token: process.env.VECTROS_API_KEY!,
});

// Hybrid (keyword + semantic) search over your indexed content, with citations.
const results = await client.search.content({ query: "annual leave policy" });
```

## Get started

- **Docs & quickstart** → https://docs.vectros.ai
- **Website** → https://vectros.ai

## SDKs

| Language | Install | Repository |
| --- | --- | --- |
| TypeScript / Node.js | `npm install @vectros-ai/sdk` | [vectros-sdk-node](https://github.com/vectros-ai/vectros-sdk-node) |
| Python | `pip install vectros` | [vectros-sdk-python](https://github.com/vectros-ai/vectros-sdk-python) |
| Java | `ai.vectros:vectros-sdk` (Maven Central) | [vectros-sdk-java](https://github.com/vectros-ai/vectros-sdk-java) |

The full API surface is described in
[vectros-api-spec](https://github.com/vectros-ai/vectros-api-spec) (OpenAPI).
Agents can reach Vectros over MCP via
[vectros-mcp-server](https://github.com/vectros-ai/vectros-mcp-server).

## What you can build

- **Hybrid search** over your documents and structured records, keyword + vector, fused.
- **Document ingestion** with schema-defined indexing, lookup/range queries, and folders.
- **Grounded inference**: chat, RAG, and document-ask, answered with citations.
- **Multi-tenant by design**: per-customer isolation, scoped keys, and app-contexts.

## Reference apps

Forkable, production-grade front-ends with no application server of their own. Clone one, wire
your own identity provider and host, and see exactly how a real app talks to Vectros.

| App | What it demonstrates | Repository |
| --- | --- | --- |
| HR case management | The flagship reference app: BYO-IdP sign-in (Auth0), org/case/client compartments, zero application backend, built to be forked as-is | [vectros-casework-spa](https://github.com/vectros-ai/vectros-casework-spa) |
| Data workspace | Records, documents, hybrid search, an AI workspace over your own data | [vectros-app-vectros-ai](https://github.com/vectros-ai/vectros-app-vectros-ai) |
| Admin | Members, API keys, roles and access profiles, activity logs, usage | [vectros-admin-app](https://github.com/vectros-ai/vectros-admin-app) |

## Security & trust

Per-customer fail-closed isolation, least-privilege scoped keys, and a tamper-evident
audit and version history. Customer-facing surfaces are hardened through extensive
adversarial security review. See the
[compliance & trust guide](https://docs.vectros.ai/guides/operations-trust/compliance).

---

Building something with Vectros? Start at [docs.vectros.ai](https://docs.vectros.ai).
