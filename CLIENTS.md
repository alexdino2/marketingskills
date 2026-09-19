# Client Product Marketing Registry

Map of Digital Optimus clients (and the agency itself) to their product marketing context files.

Agents: when the user names a client below (or a listed alias), **read that client's `product-marketing.md` immediately** and treat it as the active product marketing context for the rest of the task. Do not ask which client they mean if the name/alias matches.

Skills that normally check `.agents/product-marketing.md` should use the matched client file instead when a client is named.

## Active clients

| Client | Aliases | Product marketing file |
|--------|---------|------------------------|
| Digital Optimus | DO, digitaloptimus, digitaloptimus.com, the agency | `outputs/2026-09-07-digital-optimus-pitch/product-marketing.md` |
| Marvento Homes | Marvento, marventohomes, marventohomes.com, student housing, 3530 Datura | `outputs/2026-09-07-marvento-product-marketing/product-marketing.md` |
| Future Home Loans | FHL, Future Financial, future.loans, future loans, VA loans (FHL context) | `outputs/2026-09-18-future-home-loans-product-marketing/product-marketing.md` |
| Expert Home Advisors | EHA, Expert Home, experthomeadvisors, experthomeadvisors.com, JPAR City & Beach (EHA team) | `outputs/2026-09-19-expert-home-advisors-product-marketing/product-marketing.md` |

## Matching rules

1. **Case-insensitive.** "future home loans", "Future Home Loans", and "FHL" all match.
2. **Prefer the named client** over `.agents/product-marketing.md` when both exist.
3. **If two clients could match** (rare), ask which one — do not merge contexts.
4. **If no client is named** and `.agents/product-marketing.md` exists, use that (default skill behavior).
5. **If no client is named** and no `.agents/product-marketing.md` exists, ask which client (or offer to draft one) before marketing work that needs positioning.
6. **Do not invent** a client entry. Add new clients to this table when their product-marketing file is created.

## Maintaining this registry

When you create or move a client's `product-marketing.md`:

1. Add or update the row in the table above.
2. Keep aliases short and how the user actually refers to them.
3. Point at the latest dated folder under `outputs/` (do not leave the table pointing at an obsolete path).
