# Play Console — Data Safety Form Answers

> All answers for the Google Play Console Data Safety section.
> Fill these in at: Play Console → App content → Data safety

---

## Step 1: Does your app collect or share any of this user data?

| Category | Collected | Shared |
|----------|-----------|--------|
| Financial info | Yes | Yes |
| Personal info (name, email) | Yes | No |
| Photos and videos | Yes | Yes |
| Device or other IDs | Yes | No |

**Answer: Yes**

---

## Step 2: Data type details

### Financial info → User payment info

| Field | Answer |
|-------|--------|
| Collected | Yes |
| Shared | Yes (Razorpay, Stripe) |
| Processed ephemerally | No — retained 8 years (tax law) |
| Required or optional | Required for subscriptions |
| Purpose (collected) | App functionality, Fraud prevention |
| Purpose (shared) | App functionality (payment processing) |

### Financial info → Purchase history

| Field | Answer |
|-------|--------|
| Collected | Yes |
| Shared | Yes (Razorpay, Stripe) |
| Processed ephemerally | No — retained 8 years |
| Required or optional | Required for subscriptions |
| Purpose (collected) | App functionality, Fraud prevention |
| Purpose (shared) | App functionality (payment processing) |

### Photos and videos

| Field | Answer |
|-------|--------|
| Collected | Yes |
| Shared | Yes (Google Gemini, Render) |
| Processed ephemerally | No — stored until account deletion |
| Required or optional | Required (core feature) |
| Purpose (collected) | App functionality |
| Purpose (shared) | App functionality (AI solving) |

### Email

| Field | Answer |
|-------|--------|
| Collected | Yes |
| Shared | No |
| Processed ephemerally | No — stored as account identifier |
| Required or optional | Optional (Guest mode available) |
| Purpose | App functionality |

### Name

| Field | Answer |
|-------|--------|
| Collected | Yes |
| Shared | No |
| Processed ephemerally | No — stored in database |
| Required or optional | Optional (Guest mode available) |
| Purpose | App functionality |

### Device or other IDs

| Field | Answer |
|-------|--------|
| Collected | Yes |
| Shared | No |
| Processed ephemerally | No — stored for quota tracking |
| Required or optional | Required (abuse prevention) |
| Purpose | App functionality, Fraud prevention |

---

## Step 3: Encryption and account creation

| Question | Answer |
|----------|--------|
| Data encrypted in transit | Yes |
| Account creation method | OAuth (Google Sign-In) |
| Delete account URL | https://girishshankaran.github.io/snapsolve-legal/delete-account.html |
| Data deletion without account deletion | No |

---

## Step 4: Data safety declaration checklist

- [x] Privacy policy: https://girishshankaran.github.io/snapsolve-legal/privacy-policy.html
- [x] Account deletion: In-app (Profile Settings → Delete Account)
- [x] All data encrypted in transit (HTTPS)
- [x] Data not used for advertising
- [x] Data not sold
- [x] Committed to Play Families Policy (target age includes children)
