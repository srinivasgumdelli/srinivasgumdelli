### What I do

Infrastructure and reliability engineering. Most of my work has been the unglamorous
side of keeping things available: multi-region failover, secrets management, disaster
recovery testing, and the evidence that proves any of it actually works.

### Outside of work

I'm keenly interested in agent infrastructure, from the reliability and security side
rather than the model side.

**[PipeRoll](https://piperoll.org):** a public registry of verified AI-agent incidents.
Versioned schema, source-verified records, published corrections, CVE-style permanent
identifiers. Records are CC BY 4.0; contributions welcome at
[piperoll/registry](https://github.com/piperoll/registry).

**[moat](https://github.com/srinivasgumdelli/moat):** sandboxed environment for coding
agents. Zero-egress network behind a fail-closed proxy, credentials held outside the
container, Terraform plan-only and kubectl read-only enforced host-side.

**[murmur](https://github.com/srinivasgumdelli/murmur):** message bus for multi-agent
sessions. Postgres-backed, long polling, single binary.

**[plumb](https://github.com/srinivasgumdelli/plumb):** checks structured model output
against the request that produced it, and repairs it in code instead of re-asking. Go,
stdlib only.

The through-line: systems that act on their own should fail in ways you can see, bound,
and recover from.
