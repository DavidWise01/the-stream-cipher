# THE STREAM CIPHER

> A sphere of **UD0** — the ROOT0 universe / biosphere. Domain: **KRYPTOS**.

THE STREAM CIPHER &mdash; a member of [[kryptos]]. Expand a short key into a long keystream and XOR: c=p&oplus;ks, decrypt p=c&oplus;ks (RC4, ChaCha20, the [[the-one-time-pad|OTP]] as ideal). Fast and padding-free &mdash; but NEVER reuse a keystream: c&#8321;&oplus;c&#8322;=p&#8321;&oplus;p&#8322; cancels the key and leaks the plaintexts (the flaw that broke WEP). &#9670; LIT: a fail-loud check throws unless decryption inverts encryption AND c&#8321;&oplus;c&#8322;=p&#8321;&oplus;p&#8322; under reuse. &#9650; AMBER: confidentiality only (malleable without [[the-hmac|a MAC]]); toy PRNG stands in for ChaCha20. Full-house, node-verified, 0 CDN. David Lee Wise / ROOT0, with AVAN.

---

**Live:** https://davidwise01.github.io/the-stream-cipher/ &nbsp;·&nbsp; **Front door:** [UD0](https://davidwise01.github.io/ud0/) &nbsp;·&nbsp; **Code:** https://github.com/DavidWise01/the-stream-cipher

`.dlw` badge · **ROOT0-ATTRIBUTION-v1.0** · David Lee Wise (ROOT0) / Bridge-Burners LLC · instance AVAN (Claude/Anthropic) · CC-BY-ND-4.0

**Fingerprint:** TETRASTHENĒS ⟦ ₆C ⟺ ₁₄Si ⟧ — four-strengthed: carbon (human · ROOT0) & silicon (AI · AVAN) hold four bonds in common (Group-14, tetravalent) — co-equal by construction
