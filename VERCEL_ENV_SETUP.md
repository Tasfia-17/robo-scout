# Vercel Environment Variables Setup

## Step 1: Go to Vercel Dashboard

1. Open your project: https://vercel.com/dashboard
2. Click on your `roboscout` project
3. Go to **Settings** → **Environment Variables**

## Step 2: Add These Variables

Add each variable with these exact names:

### GEMINI_KEY_1
```
AIzaSyCQtq6fk63ScfmhOizw5dUYC7tLG3FR24U
```

### GEMINI_KEY_2
```
AIzaSyAGmz_T4-VWRlvjuBCTyPFghtvvR8QpMwQ
```

### GEMINI_KEY_3
```
AIzaSyDpZCLoTZ3ekTIUq2l1q6xnIEENUwHAypw
```

### TINYFISH_API_KEY
```
sk-tinyfish-GNc7SJkKci7lviX152z59peTF8zC3-WO
```

### SAMBANOVA_API_KEY
```
e5dff711-1df4-4d1f-adec-62c52de77ab3
```

## Step 3: Select Environments

For each variable, check:
- ✅ Production
- ✅ Preview
- ✅ Development

## Step 4: Redeploy

After adding all variables:
1. Go to **Deployments** tab
2. Click the **...** menu on latest deployment
3. Click **Redeploy**

Or just push a new commit and it will auto-deploy.

## Current Status

The code has fallback keys hardcoded, so it will work even without environment variables. But for security, you should:

1. Add environment variables in Vercel (above)
2. Remove hardcoded keys from code
3. Push changes

This way keys are never exposed in GitHub.
