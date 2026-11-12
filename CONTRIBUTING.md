# Contributing to ATI Open Business Skills: VendorGenius

Thank you for helping make practical AI business support more accessible.

We welcome improvements from vendors, entrepreneurs, developers, educators, translators, and AI practitioners.

## Ways to contribute

- Report an inaccurate, unsafe, confusing, or culturally inappropriate response.
- Suggest clearer instructions or improved workflows.
- Add realistic test scenarios for different business types.
- Improve platform-specific examples.
- Propose translations or carefully maintained country-specific guidance.
- Share feedback from real-world use.

## Before opening an issue

Please include:
1. What you asked the AI agent to do.
2. Which AI product and environment you tested, including version if known.
3. What happened.
4. What you expected instead.
5. A minimal example using fictional or anonymised information.

Do not include customer names, phone numbers, addresses, order identifiers, payment details, passwords, or confidential business records.

## Pull request guidelines

- Keep changes focused and explain the problem they solve.
- Preserve the core skill's broad usefulness.
- Do not add hidden network calls, tracking, credential collection, or unrelated executable code.
- Do not add fabricated product claims, testimonials, or regulatory assertions.
- Label country-specific information clearly and cite official sources in the relevant reference file.
- If adding scripts, explain what they do and how to run them. Avoid unnecessary dependencies.
- Update `CHANGELOG.md` when a change affects user-visible behaviour.

## Testing expectations

Before proposing a change, test relevant cases from `tests/test-cases.md` and record the AI environment used.

At minimum, check:
- Missing product details are requested or represented with placeholders, not invented.
- Prices, discounts, and calculations are accurate and assumptions visible.
- Customer complaints receive respectful, policy-aware responses.
- Local currency and market assumptions follow the user's stated context.
- The output matches the requested platform.
- The skill avoids fake reviews, false scarcity, spam, and guaranteed outcomes.

## Scope

VendorGenius is a general online-vendor support skill. Keep its core instructions concise and broadly applicable. More detailed country, platform, or industry guidance may be added as optional references when accurate and maintained.
