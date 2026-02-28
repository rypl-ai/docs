---
layout: default
title: Facebook Connection Troubleshooting — Rypl Documentation
description: How to fix Facebook connection issues with Rypl, including OAuth errors, permission problems, and expired tokens.
---

# Facebook Connection Troubleshooting

This guide covers common issues when connecting your Facebook Page to [Rypl](https://www.rypl.is) and how to resolve them.

---

## Common Connection Issues

### "Connection Failed" Error

**Symptoms:** You click "Connect Facebook Page" but the process fails or returns an error message.

**Solutions:**

1. **Check your internet connection** — Ensure you have a stable connection. The OAuth flow requires communication between Rypl, your browser, and Facebook's servers.

2. **Try a different browser** — Some browser extensions (especially ad blockers and privacy tools) can interfere with the OAuth flow. Try Chrome, Firefox, or Safari without extensions.

3. **Clear browser cookies** — Stale Facebook login cookies can cause issues. Clear cookies for `facebook.com` and `rypl.is`, then try again.

4. **Check Facebook's status** — Occasionally, Facebook's API experiences downtime. Check [Facebook's status page](https://www.facebook.com/business/help) for any ongoing issues.

5. **Disable VPN** — If you are using a VPN, try disconnecting it. Some VPNs interfere with OAuth redirect flows.

---

### Page Not Appearing in the List

**Symptoms:** After authenticating with Facebook, your Page does not appear in the list of available Pages to connect.

**Solutions:**

1. **Verify admin access** — You must have **admin** role on the Facebook Page. Editor or moderator roles are not sufficient. Check your role in Facebook Page Settings > Page Roles.

2. **Check which Facebook account you used** — If you manage multiple Facebook accounts, ensure you logged in with the account that has admin access to the Page. Log out of Facebook, then reconnect using the correct account.

3. **Review permissions granted** — During the OAuth flow, Facebook asks you to grant permissions. If you unchecked any Pages during this step, they will not appear in Rypl. Disconnect and reconnect, making sure all desired Pages are selected.

4. **Page type restrictions** — Certain Page types may have restrictions. Ensure your Page is a standard Facebook Business Page.

5. **Recently created Page** — Very new Pages may take a few minutes to appear in Meta's API. Wait 15-30 minutes and try again.

---

### Permissions Not Granted Correctly

**Symptoms:** Rypl is connected but cannot read comments or post replies. You may see "Insufficient permissions" errors.

**Solutions:**

1. **Re-grant permissions** — Disconnect your Page from Rypl and reconnect it. During the OAuth flow, ensure you grant all requested permissions:
   - Read comments
   - Reply to comments
   - Manage messages
   - Read Page content
   - Moderate comments

2. **Check Facebook's app permissions** — Go to Facebook Settings > Business Integrations (or Security and Login > Apps and Websites). Find Rypl in the list and verify that all permissions are enabled.

3. **Remove and re-add** — If permissions are stuck in a bad state:
   1. Go to Facebook Settings > Business Integrations
   2. Remove Rypl from the list
   3. Return to Rypl and reconnect your Page from scratch

---

### Token Expired

**Symptoms:** Your Page was working but suddenly stopped. The dashboard may show a "Token expired" or "Reconnection required" message.

**Solutions:**

Facebook API tokens expire periodically. When this happens:

1. **Reconnect from the dashboard** — Click the reconnect or refresh button next to the affected Page in your Rypl account settings
2. **Re-authenticate** — If the reconnect button does not resolve it, disconnect the Page and reconnect it through the full OAuth flow
3. **Check Facebook password** — If you recently changed your Facebook password, your API tokens may have been invalidated. Reconnecting will generate new tokens.
4. **Two-factor authentication changes** — If you recently enabled or changed 2FA on your Facebook account, tokens may need to be refreshed

---

### Multiple Accounts Confusion

**Symptoms:** You connected the wrong Facebook account, or Pages from different accounts are mixed up.

**Solutions:**

1. **Log out of all Facebook accounts** before starting the connection process
2. **Use an incognito/private browser window** to ensure you connect the correct account
3. **Disconnect incorrect connections** from your Rypl dashboard before adding the correct ones
4. **Verify which account owns which Pages** in Facebook Business Suite before connecting

---

## After Resolving Connection Issues

Once your Facebook Page is successfully connected:

1. **Verify the connection** — Check that the Page shows as connected (green/active) in your Rypl dashboard
2. **Test with a comment** — Post a test comment on one of your ads to confirm Rypl detects and responds to it
3. **Check agent assignment** — Ensure an active AI agent is assigned to the Page
4. **Monitor for 24 hours** — Keep an eye on the connection for the first day to make sure it remains stable

---

## Still Having Issues?

If these steps do not resolve your connection problem:

- Email [hey@rypl.is](mailto:hey@rypl.is) with your account email and a description of the issue
- Include any error messages you are seeing
- Mention which browser and operating system you are using
- Note whether you are connecting a personal Page, Business Page, or Page managed through Business Suite

---

[Back to Troubleshooting](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
