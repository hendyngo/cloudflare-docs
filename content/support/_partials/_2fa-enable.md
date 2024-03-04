---
_build:
  publishResources: false
  render: never
  list: never
---

We recommend that all Cloudflare user account holders enable two-factor authentication (2FA) to keep your accounts secure. 

2FA can only be enabled successfully on an account with a [verified email address](/fundamentals/setup/account/verify-email-address/). If you do not verify your email address first, you may lock yourself out of your account.

{{<Aside type="warning">}}
Super Administrators can turn on **2FA Enforcement** to require all members to enable 2FA. If you are not a Super Administrator, you will be forced to turn on 2FA prior to accepting the invitation to join a Cloudflare account as a member. 
{{</Aside>}}

To enable two-factor authentication for your Cloudflare login:

1.  Log in to the [Cloudflare dashboard](https://dash.cloudflare.com/login).
2.  Under the **My Profile** dropdown, select **My Profile**.
3.  Select **Authentication**. 
4.  Select **Manage** in the Two-Factor Authentication card.
5.  Configure either a [TOTP mobile app](/fundamentals/setup/account/account-security/2fa/#configure-totp-mobile-application-authentication-for-two-factor-cloudflare-login) or a [security key to enable 2FA on your account](/fundamentals/setup/account/account-security/2fa/#configure-security-key-authentication-for-two-factor-cloudflare-login).