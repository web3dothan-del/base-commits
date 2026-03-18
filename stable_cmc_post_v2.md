# Stable: The Project Bringing America's $35 Trillion Mortgage Market Onchain

**The largest store of middle-class wealth in the world has never been available in DeFi. Stable is changing that — and the implications go far beyond another stablecoin.**

---

There is a number that should sit uncomfortably with everyone who has spent time in DeFi.

$35 trillion.

That is the total value of home equity sitting inside American properties right now. It dwarfs the combined market cap of every cryptocurrency. It exceeds the US national debt. It represents decades of work by tens of millions of ordinary people who made their payments, maintained their properties, and watched their equity grow — year after year, quietly.

And almost none of it has ever been usable in any meaningful financial sense.

To access your home equity today, you need a bank's permission, an appraiser's schedule, an underwriting team's approval, and four to eight weeks of waiting — after which you may still be told no. The system has operated this way for generations. Not because it had to. Because no one built anything better.

Stable built something better.

---

## What Stable Is

Stable is a blockchain protocol that tokenizes real estate and mortgages, enabling property owners and financial institutions to bring their assets onchain, access liquidity against their equity on demand, and participate in a transparent, always-available mortgage capital market.

The headline product is **USDX** — a USD-pegged stablecoin backed not by dollars in a bank account, but by real mortgages and real property. It is the first stablecoin collateralized by the US mortgage market and represents a genuinely new asset class in decentralized finance.

But USDX is the output of a much larger system. To understand why it matters, you need to understand what Stable has actually built underneath it.

---

## The Tokenization Layer

Everything in Stable's ecosystem begins with tokenization — taking a physical, legally encumbered asset and representing it accurately and enforceably on a blockchain.

This is harder than it sounds. Real estate is among the most legally complex assets in existence. Ownership is jurisdiction-specific, title verification is required, liens must be identified, and documentation must be notarized. This is why, despite years of projects claiming to tokenize real estate, essentially nobody had done it end-to-end in a way that actually worked.

Stable's process handles all of this. A property owner enters their address, Stable pulls from multiple data sources simultaneously, auto-generates legal documentation for that specific jurisdiction, and walks the user through digital signing and remote notarization. A property NFT is minted — Core NFT on Solana, ERC-721 on Ethereum — that represents the owner's equity onchain.

This NFT is not a static record. It is a live, oracle-connected representation of the property, continuously updated with current valuations, outstanding debt status, and offchain legal information through a combination of oracle networks and zero-knowledge proofs. The ZK layer preserves privacy: borrowers' sensitive financial data stays private while the protocol verifies what it needs — payment status, debt levels, collateral health — without exposing the underlying information.

Critically, tokenized assets do not lose their offchain functionality. Stable is explicit about this. The blockchain layer is additive, not disruptive, to the property's legal standing.

---

## How USDX Works

Once a property is tokenized, it becomes USDX-enabled — it has a line of credit that the owner can draw from at any time.

The mechanism is a collateralized debt position (CDP), the same structure that underpins protocols like MakerDAO. The owner borrows USDX against their equity up to a defined loan-to-value ratio (LTV), determined by the property's assessed value, existing debt, and borrower risk profile. Monthly interest-only payments are due. Repayment can happen at any time. When the position is closed, the Debt NFT representing the loan is burned.

USDX is a standard ERC-20 on EVM chains and a SPL token on Solana — fully composable with the existing DeFi ecosystem. It can be traded, staked, used as collateral elsewhere, or redeemed for fiat.

What makes USDX structurally different from other CDP stablecoins is the collateral itself. Real estate does not flash-crash 40% in an afternoon. It does not correlate with risk-off sentiment in crypto markets. It is insured, physically tangible, and backed by the most fundamental human need. As collateral it is significantly more stable than any crypto asset, which is why the mortgage market has always offered lower borrowing rates than crypto lending platforms.

According to Aave's own data, the average stablecoin borrowing APR on their Ethereum protocol over the past year sat at 9.66%. US mortgage and home equity rates were more than 150 basis points below that — consistently, nearly every single week. Stable captures that structural rate advantage and makes it available to anyone depositing real estate as collateral.

---

## How USDX Stays Stable

USDX maintains its dollar peg through several layered mechanisms, each designed to handle a different kind of market stress.

The foundation is overcollateralization. Every USDX in circulation is backed by assets worth significantly more than $1. Stable always uses the lowest of multiple independent appraisals, deliberately prioritizing safety over volume. The combined collateral pool provides a substantial buffer before the peg could come under pressure.

On top of that, Stable deploys institutional-grade risk management tools refined over decades in traditional finance. Mortgage pools are **tranched** — divided into risk layers where subordinate tranches absorb losses first, insulating the senior layer backing USDX. **Treasury futures** hedge interest rate risk. **Interest rate swaps** provide additional flexibility. Credit default swaps protect against correlated default scenarios.

A nationwide real estate crash exceeding 20% — across a geographically diversified, thoroughly underwritten portfolio — would be required before USDX's overcollateralization faced meaningful pressure. That buffer exists before any active hedging engages.

For day-to-day peg maintenance, borrowers are always incentivized to buy below-peg USDX to repay loans at a discount. Stable conducts market operations to support the peg directly. And a maintenance pool of stablecoin holders earns yield by providing liquidity on strategic exchanges.

---

## SUSDX: Earning From Mortgages

For users who want yield without taking on a loan, Stable offers **SUSDX** — Staked USDX.

Deposit USDX into the staking contract, receive SUSDX in return. Hold it. Do nothing. Its value rises over time as the underlying mortgage assets pay monthly interest, with yield accumulating in the vault and compounding daily. When you unstake, you receive more USDX than you deposited — the difference representing your share of mortgage interest paid during your holding period.

Large institutional investors — pension funds, insurance companies, mortgage REITs — have earned steady yield from mortgage capital markets for decades. The returns are predictable because the cash flows are contractual. Homeowners make mortgage payments every month. They do not stop because Bitcoin goes down. Yield from a diversified pool of qualified mortgages is as close to consistent returns as exists anywhere in finance.

That yield has never been accessible to ordinary crypto users. SUSDX changes that — no minimum investment, no accreditation requirement, no fund manager with discretionary control. The mortgages are there, the interest is being paid, and SUSDX holders are on the receiving end.

--

## The Homeowner Math

The most immediate application for individual users is mortgage acceleration — using Stable to pay off a traditional mortgage significantly faster than the amortization schedule allows.

Consider a standard scenario: $500,000 home, 20% down, $400,000 mortgage at 6% fixed over 30 years. Monthly payment: approximately $2,398. Total interest paid over the life of the loan: roughly $463,000 — more than the original principal, handed to a bank for the privilege of borrowing.

With Stable, the borrower tokenizes the property, draws a USDX line of credit, and deploys that capital into an asset yielding 9% — a 3% positive spread. Applying the monthly yield as extra principal payments, the mortgage is paid off **5 years and 2 months early**. Total interest saved: **$176,680**.

No house sold. No speculative bet placed. No leverage stacked on top of leverage. The borrower simply used the equity they already owned — the way a corporate treasury always has — by finding idle capital, finding a positive spread, and letting it work.

That option has never existed for ordinary homeowners before. Stable built it anyway.

---

## The Institutional Opportunity

While the individual homeowner use case is compelling, the larger market opportunity lies with institutions.

Banks, brokers, and funds that originate or hold mortgages currently operate in a secondary market that moves on business hours, settles over days, and involves manual process at every step. Selling a mortgage means phone calls, legal review, and transfer documentation. None of this happens at 2am on a Saturday.

Stable integrates directly into existing loan origination software, enabling originators to tokenize mortgages at the point of creation and liquidate them into the Stable ecosystem instantly, around the clock. A white-label "Powered by Stable" option requires essentially no technical lift for institutions that want even less friction.

The value proposition is simple: every day a mortgage sits on a balance sheet waiting to be sold is a day of capital inefficiency. Stable eliminates that wait entirely.

---

## STABLE Token and the Pump Fun Hackathon

Stable launched its STABLE token through the Pump Fun Hackathon — one of the most competitive builder competitions in the Solana ecosystem. The team was not merely a participant: they were invited to demo live on the Pump Fun stream with Brycent, receiving visibility that is earned, not purchased.

That moment signals something important. The Pump Fun hackathon does not spotlight whitepaper projects. It spotlights things that are actually being built, by teams that can show their work in real time. Being chosen to present in that context — in front of one of crypto's most engaged communities — is a signal about execution quality that no press release can manufacture.

STABLE gives the community direct participation in the protocol's growth. As USDX expands and the mortgage treasury deepens, STABLE holders are positioned alongside the system they are helping build.

---

## The Underwriting Standard

One question every serious investor will ask is: what stops Stable from approving bad collateral to grow faster?

The answer is structural. Stable's own financial health is entirely dependent on the quality of what backs USDX. There is no originate-to-distribute model here — no incentive to approve loans and immediately sell the risk to someone else. Stable holds the exposure. That means every weak property in the pool is Stable's problem, not a downstream investor's.

In practice, the underwriting reflects this. Every deposited property receives multiple independent appraisals, and the lowest valuation is used — not the average, not the highest. Full KYC, credit checks, income verification, and debt analysis are run on every individual borrower. Institutional depositors go through a complete KYB process. Properties that fail at any stage are rejected, regardless of volume pressure.

Risk scoring determines both LTV and borrowing rate for each position. A borrower at 40% LTV pays a different rate than one at 78% LTV. That gradient keeps incentives aligned: conservative borrowers get better terms, and the protocol's overall exposure stays manageable.

This is not a new concept in finance. It is disciplined underwriting — the same principle that separates resilient mortgage portfolios from the kind that caused 2008. The difference is that Stable's version runs transparently, onchain, with every position verifiable.

---

## Why This Matters Right Now

The RWA narrative has circulated in crypto for years. The vision has always been clear: if the trillions locked in physical assets could be made liquid and composable onchain, the implications for capital efficiency, financial inclusion, and yield generation would be transformative.

What was missing was the execution layer — the legal infrastructure, oracle connectivity, ZK privacy architecture, and institutional risk management that would make it work in practice rather than theory. Stable has built that layer, focused on the asset class that most people in the world have direct experience with: the home they live in.

The mortgage market is not glamorous. There is no viral meme attached to it. It will not generate the cultural moment that profile picture NFTs did. But it moves $35 trillion. It touches more lives than any other financial instrument. And it has run on outdated, exclusionary infrastructure for generations — charging ordinary people enormous sums for the privilege of accessing their own equity, while institutions quietly harvested the yield on the other side.

Stable is not solving a niche problem for a niche audience. It is rebuilding the plumbing of the largest financial market on earth, and making the output available to anyone with a wallet.

The $35 trillion was always there. Now there is finally somewhere for it to go.

---

*Learn more: [trystable.co](https://trystable.co)*
*Try the app: [app.trystable.co](https://app.trystable.co)*
*Follow: [@stable_tweets](https://x.com/stable_tweets)*

*USDX: `0xfea577f08d1984e6654813be0acee3140e5d7d42`*
*STABLE: `4AjvPXMn8YZG9saAVJvcWspg73oTFf2JmU4in4Xgpump`*

*@stable_tweets @Superteam*
