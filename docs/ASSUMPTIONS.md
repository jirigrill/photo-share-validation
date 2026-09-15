# Assumptions

Every inferred value this effort leans on. IDs are global and permanent: once `A7` is
assigned it is never reused or renumbered, so any section may cite it.

Sections arrive with `A?-n` placeholders. The resolving session assigns the next free ID here
before committing the section.

**Sensitivity** is the column the verdict selects on — it names what breaks if the value is
wrong by roughly 2×. An assumption whose sensitivity is "nothing" did not need registering.

| ID | Assumption | Value | Basis | Sensitivity | From |
|---|---|---|---|---|---|
| A1 | Share of US parent households whose family photo channel is a WhatsApp group | ≤20% | Pew 2025: 40% of 30–49s use WhatsApp at all (VERIFIED); channel-of-choice share INFERRED | 2× higher: pool doubles but still hits A3. 2× lower: X1 fan-out must target iMessage / Messenger, not WhatsApp | 01 |
| A2 | Share of US parent households already paying for any cloud photo/storage subscription | 30–50% placeholder | NO EVIDENCE FOUND — Apple/Google do not disclose paid counts | Low: product competes with free storage. High: competes for budget share on top of $1–3/mo. Verdict unchanged; drives pricing decision | 01 |
| A3 | Free→paid conversion achievable in this niche | ~6% of MAU | Tinybeans FY25 51k payers / 0.86M MAU (INFERRED from two VERIFIED figures) | 3% ⇒ ~27k active trialists needed for ~800 payers; 12% ⇒ ~7k. Both need a channel a solo builder can run | 01 |
| A4 | Sharing/upload frequency falls as child ages | roughly halves after 5, again by 12 | INFERRED from birth-entry KPIs (MIXI 65%), "baby" App Store naming, Tinybeans low-upload Legacy tier, UK ~100 posts/yr; no US age curve found | If it does not fall, payer life extends to a decade+, LTV 3–5× larger, any-age persona holds. Highest-value gap (X4/X5) | 01 |
| A5 | Payers needed to net $3–5k/mo | ~600–1,000 at $60–75/yr, before store fees and infra | Arithmetic on VERIFIED incumbent ARPU; not a forecast | ARPU 2× lower ⇒ 1,200–2,000 payers; store fees 15–30% and storage/egress push higher. 06 models properly | 01 |
| A6 | JPY→USD conversion for MIXI figures | ¥150 = US$1 | INFERRED; MIXI reports in JPY only | ±30% FX does not change "segment ≈ US$100M, barely profitable" | 01 |

## Retired assumptions

Assumptions later replaced by verified evidence. Kept, not deleted — a downstream section may
have been reasoned on the old value.

| ID | Was | Now verified as | Superseded by |
|---|---|---|---|
| | | | |
