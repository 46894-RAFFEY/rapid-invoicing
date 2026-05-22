# Troubleshooting Guide

## Common Issues & Solutions

### Login Issues

#### I forgot my password

**Solution:**
1. Click "Forgot Password?" on the login page
2. Enter your email address
3. Check your email for reset link (check spam folder)
4. Click the link and set your new password
5. Log in with your new password

**If you don't receive the email:**
- Check your spam/junk folder
- Try requesting another reset email
- Contact support@rapid-invoicing.com

---

#### I'm getting "Invalid credentials" error

**Solution:**
1. Double-check your email and password
2. Ensure CAPS LOCK is off
3. Try resetting your password
4. Clear browser cache and try again
5. Try a different browser

**If still not working:**
- Contact support@rapid-invoicing.com with your email

---

#### I can't access my workspace

**Solution:**
1. Verify you have the correct workspace URL
2. Check if you have access rights (ask workspace admin)
3. Log out and log back in
4. Clear browser cookies for the site
5. Try a different browser

---

### Invoice Creation Issues

#### "Buyer not found" error

**Solution:**
1. Check buyer's NTN/CNIC number is correct
2. Verify buyer is registered with FBR
3. Try adding buyer as new buyer
4. Wait 5 minutes (FBR database may be syncing)
5. Contact support if buyer should exist

---

#### "Validation failed" error

**Common causes and solutions:**

**Invalid NTN format:**
- NTN should be 5 digits + 3 digits (e.g., 123456789)
- Remove any special characters or spaces

**Missing required fields:**
- Ensure all fields marked with * are filled
- Check seller and buyer information is complete

**Tax calculation mismatch:**
- Verify item quantities and prices
- Check tax percentages are correct
- Ensure total matches sum of items

**Invalid dates:**
- Invoice date cannot be in future
- Check date format is MM/DD/YYYY

---

#### "Invoice number already exists"

**Solution:**
1. Check your invoice list for duplicate
2. Use a different invoice number
3. Enable auto-invoice numbering instead

---

#### File upload fails

**Solution:**
1. Check file size is under 10MB
2. Verify file format is .xlsx or .csv
3. Try a different browser
4. Check internet connection
5. Clear browser cache

---

### FBR Submission Issues

#### "FBR submission failed"

**Solution:**
1. Ensure all invoice details are correct
2. Verify buyer is FBR-registered
3. Check internet connection
4. Wait a few minutes and retry
5. Contact FBR support if persistent

---

#### "FBR is down or slow"

**Solution:**
1. Check [FBR Status Page](https://fbr.gov.pk)
2. Try again after 30 minutes
3. Check your internet connection
4. Use VPN if you're outside Pakistan
5. Contact support for troubleshooting

---

#### Invoice stuck in "Pending" status

**Solution:**
1. Refresh the page (F5 or Cmd+R)
2. Wait 5 minutes for FBR response
3. Check your email for FBR notification
4. Go to "Submitted Invoices" to verify
5. Contact support if still pending after 30 minutes

---

### Dashboard & Reporting Issues

#### Dashboard shows incorrect numbers

**Solution:**
1. Refresh the page
2. Clear browser cache (Ctrl+Shift+Delete)
3. Check filters are correct
4. Verify date range selection
5. Wait for data to sync (may take up to 5 minutes)

---

#### Export to Excel not working

**Solution:**
1. Check you have invoices to export
2. Verify file size is under limits
3. Check browser allows downloads
4. Try different browser
5. Try exporting fewer invoices

**If still not working:**
- Contact support for manual export

---

### Performance Issues

#### Website is slow

**Solution:**
1. Check your internet connection
2. Refresh the page
3. Clear browser cache
4. Disable browser extensions
5. Close other tabs/applications
6. Try a different browser

---

#### Page won't load / blank screen

**Solution:**
1. Refresh the page (F5)
2. Hard refresh (Ctrl+F5 or Cmd+Shift+R)
3. Clear browser cache and cookies
4. Try a different browser
5. Disable browser extensions
6. Check internet connection

---

### Account & Workspace Issues

#### Can't invite team member

**Solution:**
1. Verify your account is Admin role
2. Check email address is correct
3. Verify user doesn't already have access
4. Check for typos in email
5. Try resending invitation

---

#### Settings changes not saving

**Solution:**
1. Check internet connection
2. Refresh the page after saving
3. Try saving with fewer changes at once
4. Clear browser cache
5. Try different browser

---

### Mobile/App Issues

#### Mobile site won't load

**Solution:**
1. Refresh the page
2. Check internet connection
3. Try desktop version instead
4. Clear mobile browser cache
5. Restart your phone

---

#### App crashes

**Solution:**
1. Close and reopen the app
2. Update your app to latest version
3. Clear app cache (Settings > Apps > Rapid Invoicing)
4. Restart your phone
5. Reinstall the app

---

## Advanced Troubleshooting

### Check Browser Console for Errors

1. Press F12 (or right-click > Inspect)
2. Go to "Console" tab
3. Look for red error messages
4. Screenshot and share with support

### Clear Cache Completely

**Chrome:**
1. Press Ctrl+Shift+Delete
2. Select "All time"
3. Check all options
4. Click "Clear data"

**Firefox:**
1. Press Ctrl+Shift+Delete
2. Click "Clear Now"

**Safari:**
1. Safari > Preferences > Privacy
2. Click "Manage Website Data"
3. Select rapid-invoicing.com
4. Click "Remove"

---

## Contact Support

If the above solutions don't work, contact the project maintainer by email:

- **support@rapid-invoicing.com** — include the error message, a screenshot, and browser/OS information.

If your deployed instance includes an in-app bug report feature or a status page, use those tools; otherwise email support.

---

## System Requirements

### Browser Support
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

### Internet Speed
- Minimum: 2 Mbps
- Recommended: 5+ Mbps

### Screen Resolution
- Minimum: 1024x768 (desktop)
- Recommended: 1366x768+ (desktop)
- Mobile: Any standard resolution

---

## FAQ Troubleshooting

**Q: I'm getting a timeout error**
A: Check your internet connection and try again. FBR may be slow.

**Q: Invoice won't validate**
A: Check all required fields are filled correctly, especially NTN/CNIC.

**Q: Export is taking too long**
A: For large exports (1000+ invoices), try exporting in smaller batches.

**Q: Can't login to my account**
A: Clear cache, try a different browser, or reset your password.

---

## Status Page

For FBR system status check: [https://fbr.gov.pk](https://fbr.gov.pk).

If you are using a hosted deployment that provides a status page, check that host's status page for system availability.

---

**Last Updated:** May 14, 2025  
**For more help:** support@rapid-invoicing.com
