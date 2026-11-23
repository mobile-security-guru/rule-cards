# Rule Card 01: SIM swap and the SMS reset path

**Rule (EU).** NIS2 Article 21(2)(j) calls for multi-factor or continuous authentication. Management bodies approve the measures and can be held liable. The payment services reform (PSR) points the same way: a provider that fails to implement appropriate fraud prevention mechanisms is liable for customers' losses. The PSR is not yet in force.

**Rule (US).** FCC SIM swap rules (2024), NIST 800-63B-4 (phone-number codes are a restricted authenticator) and CISA's December 2024 mobile guidance.

**Gap.** Carrier checks cover the SIM change. Your reset flow still releases a password or MFA code to the number, and nothing in it asks whether the request should go through.

**Control.** Before the reset releases, call the decision. ALLOW proceeds, STEP_UP adds a second proof, DENY holds the reset. Keep the signed receipt.

**Line for your control narrative.** "Reset requests are decided before release, and each decision carries a signed receipt."

Mobile Trust Boundary (patent pending). Free sandbox key: sandbox.mobiletrustboundary.com/start
