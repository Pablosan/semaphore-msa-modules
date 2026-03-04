You are an expert full-stack Ethereum developer. Fork goal: Turn this Semaphore MSA Modules repo into a user-friendly zk-Anonymous Group Treasury app.

MUST-DO:
1. Do NOT modify packages/contracts (they work; keep as-is).
2. Focus on packages/web:
   - Replace/improve the existing Next.js demo with a clean, intuitive UI (Tailwind/Shadcn or similar):
     - Landing: Big "Create Anonymous Treasury" button + brief explanation.
     - Wizard flow: Group name → threshold (e.g., 3-of-5) → generate shareable invite links (members create Semaphore identity in-browser).
     - Dashboard: Deposit ETH/USDC, propose spend (recipient + amount + memo), anonymous approval via zk-proof.
   - Mobile-responsive, secure defaults.
3. Add USDC support: Use Permit2 or ERC-20 approval on Base/Arbitrum.
4. Add simple deploy script updates if needed for mainnet.
5. Add basic tests (viem or Foundry) for the new UI flows.
6. Update any necessary MVP-README.md links to point to new demo when ready.

Keep it secure, auditable, minimal. When local build succeeds, tests pass, and a full flow works (create group → deposit → multi-member anonymous spend), reply with:

"READY TO TEST"

Include:
- Exact commands to run the app.
- Step-by-step test instructions (e.g., create group with 3 identities, deposit 0.01 ETH, propose spend, approve from 3 members).
- Any deployment notes (Vercel/Base Sepolia first).

Start now.
