# MAGNE Agent-Native Landing Page Skill

## Purpose

Create high-impact, compliance-safe, agent-native landing pages for MAGNE.AI, MAGNE Agent Pay, M Hash L2, and MAGNE AI Agent Layer.

The output should feel like a protocol-native AI agent economy page: dark, terminal-driven, dense, technical, and investor-readable.

This skill is inspired by modern agent-native protocol landing pages, but all content must be original and specific to MAGNE.

---

## Core Visual Style

Use a dark protocol-native interface.

Visual direction:

- Deep black / near-black background
- Subtle radial gradients
- Thin grid lines
- Terminal panels
- Monospace labels
- Uppercase section tags
- Dense data cards
- CLI-style demonstrations
- Minimal neon accents
- No glossy Web2 SaaS look
- No childish AI imagery
- No overly colorful gradients

Recommended visual keywords:

- agent-native
- secure mobile settlement
- terminal economy
- AI task receipt
- protocol dashboard
- x402-compatible payment
- M Hash L2 settlement
- secure phone authorization

---

## Typography

Use:

- Large, sharp hero headlines
- Short sentences
- Strong line breaks
- Monospace for technical labels, logs, addresses, tx hashes, task IDs
- Uppercase labels for metadata

Avoid:

- Long paragraphs
- Marketing fluff
- Overly emotional language
- Generic AI buzzwords

---

## Page Structure

Default page structure:

1. Announcement Bar
2. Hero
3. Problem Grid
4. MAGNE Agent Pay Flow
5. Live Terminal Demo
6. AI Task Receipt Layer
7. Secure Phone Authorization
8. Developer / SKILL.md Section
9. Runtime Verification Status
10. Roadmap
11. Final CTA
12. Footer Disclaimer

---

## Hero Requirements

Hero should state a clear, high-conviction thesis.

Recommended MAGNE hero thesis:

"AI agents can think. They still cannot safely pay."

Alternative:

"MAGNE turns secure phones into AI agent payment terminals."

Hero subtext should explain:

MAGNE Agent Pay is an x402-compatible developer demo for AI agent payment, wallet authorization, facilitator verification, and AI Task Receipt generation on M Hash L2.

Use compliance-safe wording:

- testnet-stage
- developer demo
- designed to support
- subject to technical validation

Do not claim production readiness unless explicitly verified.

---

## Problem Grid

Use three sharp problems:

1. **No Secure Authorization**
Agents may trigger tasks, but payments still require trusted user authorization.

2. **No Agent Payment Rail**
APIs and model services need pay-per-use settlement that agents can call programmatically.

3. **No Verifiable Receipt**
AI tasks need auditable records: who requested, who paid, what settled, and what was returned.

Each problem card should include:

- label
- short headline
- zero-state metric, such as "0 verified receipts"
- one concise paragraph
- link-style arrow

---

## MAGNE Solution Mapping

Map the problem to MAGNE:

- MAGNE Agent ID
- x402-Compatible Payment Flow
- MAGNE Facilitator
- mMHA / supported settlement assets
- M Hash L2 Settlement
- AI Task Receipt
- Secure Phone / Wallet Authorization
- MAGNE.AI Phone optional secure signing layer

Do not imply all modules are production-ready unless verified.

---

## Agent Pay Flow Section

Show this flow visually:

```
AI Agent Task
→ HTTP 402 Payment Required
→ Wallet Authorization
→ mMHA Payment
→ Facilitator Verify
→ M Hash L2 Receipt
→ API Result Returned
```

Use short labels and transaction-style UI.

---

## Terminal Demo Section

Always include a CLI-style terminal panel.

Example content:

```bash
$ magne agent task create "analyze wallet risk"
✓ task created — task_20260520_001

$ magne api call wallet-risk --wallet 0x742d...
✕ 402 Payment Required — 0.01 mMHA

$ magne pay settle --network mhash-l2
✓ payment verified — tx 0x130b...701e

$ magne receipt create
✓ AI Task Receipt created — 0x428d...fe91

$ magne receipt inspect 0x428d...fe91
agent: MAGNE-Agent-001
service: wallet-risk-analysis
amount: 0.01 mMHA
status: settled
network: M Hash L2
```

If the demo is only local runtime verified, label it clearly:

```
[LOCAL RUNTIME VERIFIED]
```

If deployed to testnet, label it:

```
[M HASH L2 TESTNET VERIFIED]
```

---

## Runtime Verification Status

Always include a transparent status panel.

Use statuses such as:

| Component | Status |
|-----------|--------|
| Smart contracts compile | verified |
| Local Hardhat deploy | verified |
| Backend starts | verified |
| mMHA ERC20 payment | verified |
| Facilitator verify | verified |
| Receipt transaction created | verified |
| M Hash L2 testnet deployment | pending / verified |
| Explorer link | pending / verified |
| Browser MetaMask flow | pending / verified |

Do not mark items as verified without evidence such as logs, transaction hashes, or explorer links.

---

## Compliance Rules

**Do not claim:**
- guaranteed revenue
- token price appreciation
- risk-free rewards
- production-ready payment integration
- official x402 partnership
- official Coinbase partnership
- fully decentralized network unless verified
- first / only / world first unless legally reviewed
- mainnet live unless deployed and verifiable

**Use:**
- x402-compatible
- developer demo
- local runtime verified
- testnet-stage
- designed to support
- planned
- subject to technical validation
- subject to security review
- subject to governance approval
- applicable compliance requirements

---

## MAGNE Content Vocabulary

**Preferred terms:**
- MAGNE Agent Pay
- M Hash L2
- MAGNE Facilitator
- AI Task Receipt
- x402-compatible payment flow
- secure mobile authorization
- MAGNE.AI Phone
- Secure Element
- TEE
- mMHA test token
- MHA-supported settlement asset
- Agent Pay Demo
- Agent-native payment layer

**Avoid:**
- guaranteed mining
- passive income
- risk-free
- moon
- pump
- official x402
- official Coinbase
- production payment rail, unless verified

---

## NARA-style Concept Mapping for MAGNE

Use this mapping only as inspiration:

| NARA Concept | MAGNE Mapping |
|-------------|--------------|
| Agent Identity | MAGNE Agent ID / Agent Registry |
| Aapps | MAGNE Agent Services / Agent Pay APIs |
| SkillHub | MAGNE SkillHub / Developer SDK |
| Agent-native currency | mMHA test asset / MHA-supported settlement utility |
| CLI demo | MAGNE Agent Pay terminal demo |
| On-chain actions | M Hash L2 AI Task Receipts |
| Agent social / live product | MAGNE Agent Portal / Agent Pay Demo |

Do not copy NARA names, layout, or proprietary wording.

---

## Output Requirements

When asked to generate or modify a page, output:

- Clear file list
- HTML structure
- CSS design tokens
- JavaScript interaction requirements if needed
- Copywriting blocks
- Compliance disclaimer
- Mobile responsive behavior
- GitHub-ready patch instructions

For OpenClaw implementation tasks, provide exact steps:

- files to create
- files to modify
- sections to insert
- classes to use
- text to replace
- testing checklist

---

## Preferred CTA Labels

**Use:**
- View Demo
- Read Docs
- Inspect Receipt
- Run Agent Task
- View GitHub
- Open Developer Demo
- Connect Wallet
- Verify Payment
- Create Receipt

**Avoid:**
- Buy now
- Earn guaranteed rewards
- Start earning
- Profit from agents

---

## Testing Checklist

Before delivery, verify:

- [ ] All terminal demo tx hashes are real (from runtime verification)
- [ ] No "production-ready" unless verified mainnet
- [ ] Testnet badge visible in hero
- [ ] Risk warning in footer
- [ ] Chain ID / RPC / Explorer links point to magicalhash.com
- [ ] No token price claims
- [ ] No guaranteed revenue language
- [ ] Page loads without console errors
- [ ] Mobile responsive at 375px width
- [ ] Terminal demo renders correctly
- [ ] All external links point to correct hosts

---

## Reference Links

- MAGNE Agent Pay Demo: https://github.com/jerrysohigh-create/magne-agent-pay-demo
- M Hash L2: https://github.com/magne-ai/M-Hash-L2
- M Hash L2 Agent Pay Docs: https://github.com/jerrysohigh-create/M-Hash-L2/blob/main/docs/agent-pay-demo.md
- SKILL source: `~/.openclaw/workspace-main/skills/magne-agent-native-landing/SKILL.md`
