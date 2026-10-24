# Ottr privacy policy

**Last updated:** 24 October 2026  ·  **Version:** 1.0.1 (closed testing)

Ottr is a personal money app for Android. This policy explains what
information the app handles, where it goes, and how you control it. It is
written to be read, not skimmed past: if something here is unclear, write to
us at **ottrsupport@gmail.com**.

## Who is responsible

The party responsible for your data (the "controller") is **Ottr, United
Arab Emirates**. While Ottr is being tested there is no registered company yet;
when there is, its name replaces this line and we tell you as described in
section 14. Contact: **ottrsupport@gmail.com**.

## The short version

- **Your entries live on your phone.** Cloud backup is optional and you choose
  it.
- **Bank alerts are read on your phone, and their wording never leaves it.**
- **Otto, the AI assistant, and smart categories** send a limited set of
  information to our server and on to an AI provider, Anthropic. Sections 4
  and 5 say exactly what. You can use Ottr without Otto, and you can switch
  smart categories off.
- **No ads, no analytics or tracking tools, and we never sell your data.**
- **Ottr is not a bank.** It never asks for your bank login and cannot move
  money. It is not licensed or regulated by the Central Bank of the UAE or any
  other financial regulator.

## 1. Data that stays on your phone

Every entry you add or confirm is stored in the app's database on your phone:
amount, currency, date, type (expense, income or transfer), category, and any
name, merchant or note you add. Your categories, budgets, goals, salary,
payday, recurring bills and settings are stored the same way.

It stays on your phone unless you turn on cloud backup (section 6). Your
goals, salary, payday, recurring bills and Otto conversations are never
backed up.

- Notifications: Ottr can show a notification for each bank alert it captures
  and a spending summary at 9 pm. Both are made on your phone from your
  phone's own entries and show only the amount, the sender or shop, and the
  category, never the message itself. Nothing is sent anywhere to make them.
  You can switch either kind off in Android's settings for Ottr.

Deleting the app removes this data from your phone.

## 2. Bank alerts (read on your phone only)

You can let Ottr read the notifications your bank sends when you pay, so it
can record the transaction for you.

- You allow this once, in an Android settings screen Ottr opens for you, and
  you can turn it off there at any time.
- **The alert is read on your phone.** Its wording is never sent to us or to
  anyone else, and is never written to any log.
- Ottr only reads alerts from the bank senders you have approved. It keeps the
  useful parts (amount, merchant, date, category) and discards the wording.
- If Ottr cannot process an alert straight away, it keeps it on your phone for
  up to 7 days, then discards it.
- **Card purchases are recorded straight away** and marked "auto", so you
  can check or correct them. If Ottr can't yet tell what kind of shop it is,
  the purchase goes under "Uncategorised" until it can. A payment of your
  credit-card bill that Ottr recognises is recorded the same way, under
  "Card payment".
- Other transactions, such as income and transfers, wait for you to confirm
  them, unless Ottr already recognises them with high confidence. Anything
  that looks like a transaction already recorded also waits for you, in case
  it is the same one twice, and so does a foreign-currency purchase whose
  amount in your main currency isn't known yet.
- Messages that look like one-time passcodes, and anything that is not a
  transaction, are ignored.

## 3. Finding past transactions (optional, on your phone only)

Live alerts only start when you turn them on. To start from your real
history, Ottr can scan your text messages whenever you ask it to.

- Nothing is read until you tap the button, and Android asks your permission
  first. You can refuse.
- To help you pick your banks, Ottr can list the **names** of the senders that
  have texted your phone, such as a bank or a shop. No message text is read to
  make that list, and personal phone numbers are left out.
- Ottr then reads messages **only from the senders you tick**. The text of
  every other message is never read.
- Everything happens on your phone; message text never leaves it.
- You can withdraw the permission at any time in Android Settings → Apps →
  Ottr → Permissions.

## 4. Otto, the AI assistant

Otto answers questions about your spending and can suggest budgets and goals.
Otto's wording is written by an AI model from **Anthropic**, reached through
our own server. Ottr's app does the sums; Otto explains them.

- **When you ask Otto something**, we send your question, the recent messages
  of that conversation, and a summary of your figures: totals by period and by
  category, the names of the shops you spend most at with their totals, your
  recurring bills and charges, budgets, goals, and your salary and payday if
  you entered them.
- **Without you asking**: if you are signed in, the short summary on your Home
  and Overview screens is written by Otto **at most once a day**, from the same
  kind of summary totals, the first time one of those screens opens that day.
  Once a week, Otto also writes a short recap of the past week on Home, from
  that week's totals by category and your budgets.
- **Never sent**: the wording of any bank alert or text message, your
  individual transactions, your email address or password.
- **Where conversations are kept**: on your phone only. Our server counts how
  many requests each account makes per day, to apply a limit; it does not
  keep your questions or Otto's answers.
- **Anthropic**, in the United States, processes the request to write the
  answer, on our behalf. Anthropic deletes the request within 30 days (longer only if it is flagged
  for misuse) and does not use it to train its models.
- Otto can be wrong. It does not give financial advice, and nothing in your
  records changes unless you tap to apply a suggestion.

## 5. Smart categories (on by default; you can switch it off)

When a card purchase comes from a shop Ottr doesn't recognise, Ottr can ask our
server what kind of shop it is, so the purchase is filed for you. Switch it off
in Settings → AI advisor → Smart categories; then nothing in this section is
sent.

- **Sent**: the shop's name as it appears in the alert (up to 40 characters)
  and, separately, the names of your expense categories.
- **Never sent**: the amount, the date, the alert's wording, your notes,
  transfers, income, cash withdrawals, or a shop name that looks like personal
  information.
- For a shop we don't know yet, our server asks Anthropic's AI what kind of
  shop it is. The AI is given the shop's name and nothing about you.
- The answer (shop name and kind of shop) is kept in a list shared by all
  users. The list holds no account, amount or date.
- If you move a purchase to a different category, Ottr sends the shop's name
  and your choice as a **vote**. Votes are stored under a code made from your
  account and the shop's name with a secret only our server holds. It is not
  your name or email, but it is **not anonymous**: someone with both the secret
  and our list of accounts could work out which votes are yours.
- Your category names are not stored on our server.

## 6. Cloud backup (only if you choose it)

The first time you sign in, Ottr asks where your entries should live: **on
this phone only**, or **on this phone plus a cloud backup**. Nothing is backed
up until you choose, and you can change it in Settings.

- **Backed up**: your entries (whether you confirmed them or Ottr filed them),
  categories, budgets and main currency.
- **Never backed up**: bank-alert or message text, goals, salary and payday,
  recurring bills, Otto conversations, and device settings such as app lock.
- Each backup is private to its account. The database is set up so that one
  account cannot read another's data, and we test this.
- To create an account we collect your **email address** and a password. Our
  sign-in provider, Supabase, handles them; we never see your password.

## 7. Exchange rates

To convert other currencies into your main one, Ottr downloads public
exchange rates about once a week from ExchangeRate-API. The request contains
your main currency code (for example "AED") and nothing else. Like any
website, the service sees the network address the request comes from. It
receives no other information about you, and we have no other relationship
with it.

## 8. Who handles your data for us

- **Supabase**: stores your backup and account, and runs our server. Our
  database is hosted in **Tokyo, Japan**.
- **Anthropic**, in the **United States**: writes Otto's answers and
  identifies kinds of shops, only as described in sections 4 and 5.

Both work on our behalf and under our instructions.

The app also downloads exchange rates directly from **ExchangeRate-API**, a
public rate service (section 7). It is not one of our providers and we have no
agreement with it. It receives your main currency code and, like any website,
your phone's network address; nothing else.

All traffic between your phone and these services is encrypted (HTTPS).

**Why your data may leave the UAE, and why we are allowed to handle it.** Your
backup and account are stored in Japan and Otto's requests are answered in the
United States. We use Supabase and Anthropic under their terms for business
customers, which commit them to keeping your data secure and limit what they
may do with it. By choosing cloud backup, or by using Otto, smart categories
or the Home summary, you agree to this. Your account and backup are needed to
provide the service you asked for, and are your choice. Otto, smart categories
and the Home summary rest on your consent: switch smart categories off in
Settings, stop using Otto, or sign out, and nothing more is sent. Ottr files
and categorises entries automatically but makes no decision about you with
legal or similar effect; you can change every entry.

## 9. What we don't do

- No advertising, and no advertising code in the app.
- No analytics or tracking tools.
- We don't sell your data or share it with anyone for their own use.
- We don't build marketing profiles.
- We don't use your data to train AI models, and neither does Anthropic
  (its commercial terms say so).

## 10. How long we keep it

| What | How long |
|---|---|
| Data on your phone | Until you delete it or delete the app |
| Cloud backup and account | While your account exists; deleted when your account is deleted |
| Bank-alert and message text | Not kept; discarded once read (up to 7 days in the on-phone queue if Ottr couldn't run) |
| Otto conversations | On your phone until you clear them or delete the app |
| Daily request counts | Deleted with your account |
| Requests sent to Anthropic (Otto, smart categories) | Deleted by Anthropic within 30 days, longer only if flagged for misuse |
| The shared list of shops | Kept; it holds nothing about any user |
| Your votes on shops | **Kept after your account is deleted**, under the code described in section 5. Once your account is gone, that code can no longer be linked to you, so the votes no longer point to anyone; they keep the shared shop list useful for everyone |

## 11. Your rights

Under the UAE Personal Data Protection Law (and, if you are in the EU, the
GDPR), you can ask to **see** your data, **correct** it, **delete** it,
**export** it, **withdraw consent** to backup, and **object** or
**complain**.

- Correct or delete any entry in the app at any time.
- Export your entries as a spreadsheet file: Settings → Export entries.
- Switch backup off: Settings.
- **Delete your account**: see <https://draupnir-studio.github.io/legal/delete-account>. In short: email
  ottrsupport@gmail.com from your account's address; we delete your account
  and its cloud backup within 30 days. An in-app button is coming.
- Anything else: ottrsupport@gmail.com. We reply within 30 days.

You can also complain to the **UAE Data Office** or, if you are in the EU,
to your national data-protection authority.

## 12. Security

Your phone's own lock screen protects the data on it; Ottr also offers its
own app lock. Data on the phone is protected by Android, not separately
encrypted by Ottr. Your sign-in session is kept in Android's secure storage.

## 13. Who Ottr is for

Ottr is designed for people living in the UAE. It is for adults aged **18 and
over** managing their own money. We don't knowingly collect data from anyone
younger; if you think we have, write to us and we will delete it.

## 14. Ottr is still being tested

This is a test version. Features may change, and this policy will change with
them. When it changes we update the date and version at the top, and we tell
you in the app before a significant change takes effect.

## 15. Contact

Questions, requests or complaints: **ottrsupport@gmail.com**.

Our terms of use: <https://draupnir-studio.github.io/legal/terms-of-use>.
