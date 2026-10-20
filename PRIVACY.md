# Job Explorer privacy policy

**Effective:** 10/20/2026
**Publisher:** Keith Francis
**Contact:** keith.francis83@gmail.com

Job Explorer is a Windows app that finds job postings, scores them against your experience, and helps you keep track of your job search. You apply to jobs yourself, on the employers' own websites. This policy explains what information the app handles, where it's kept, and when it leaves your computer.

**The short version:** Job Explorer has no accounts and no servers of its own. Your information is stored on your computer, encrypted, and is never sent to us. It goes to other services only when you use a feature that needs them, such as an AI provider you choose. Job Explorer never fills in or submits job applications.

## Information the app stores on your computer

- **Your profile:** contact details (name, email, phone, address, links), work history, education, skills, certifications, and work authorization.
- **Documents:** resumes and cover letters you import or create.
- **Your job search:** job postings found by your searches, match scores, your application tracker (statuses, dates, notes), contacts you add (for example a recruiter's name and email), your saved answers to common application questions, and interview prep notes.
- **Email updates (if you turn them on):** for emails about your applications, the sender, the subject, and a short excerpt, used to suggest tracker updates.
- **Settings and history:** your settings, report send history, AI usage counts (token totals, not content), and a troubleshooting log with personal details removed.
- **Saved keys and passwords:** AI provider API keys, job source keys, and your email app password.

**How it's protected:** the database is encrypted (SQLCipher, 256-bit AES) and documents are encrypted (AES-256-GCM). The key is protected by Windows (DPAPI), so only your Windows account can open it. You can add a master password in Settings. Saved keys and passwords get an extra layer tied to the database key.

## When information leaves your computer

Information leaves your computer only in the cases below, and only to the service involved.

1. **Your AI provider.** Job Explorer uses the AI provider you choose to score jobs and to write drafts (resumes, cover letters, follow-up emails, interview prep). A local option (Ollama, LM Studio, or a custom server) keeps all of this on your computer. With a cloud provider (Anthropic, OpenAI, or Google), the app sends only what each task needs:
   - job postings;
   - a summary of your experience and skills, or resume content;
   - company website text, for interview prep;
   - if you turn on AI sorting for email updates, the subject and first few hundred characters of unclear emails.

   Your name, email address, phone number, and street address are removed before anything is sent. You use your own API key, and the provider's own privacy policy applies to what it receives.
2. **Job sources.** When a search runs, Job Explorer reads job listings from the sources you turn on:
   - public company job boards you add (such as Greenhouse, Lever, Ashby, and SmartRecruiters);
   - USAJOBS, which receives your search terms and the email address you registered with it, as its API requires;
   - in editions that include them, Adzuna and Remotive.

   These services also see your computer's IP address, as any website does. Opening a job posting opens it in your own web browser.
3. **Your email provider.** If you set up email:
   - Reports are sent from your own email account to the recipients you choose.
   - If you turn on email updates, the app reads your inbox read-only. It opens only messages that look like they're from a company you applied to, and it never marks, moves, or deletes mail.
4. **Company websites.** For interview prep, if you choose to include the company's website, the app reads that site's home and About pages.
5. **Downloads.** If you choose local AI, AI models are downloaded from ollama.com (and, outside the Microsoft Store edition, the Ollama installer too). That server sees your IP address.

Job Explorer doesn't use analytics, advertising, tracking, or crash-reporting services, and it doesn't sell or share your information.

## Your choices and controls

- Every feature that sends information is optional and can be turned off in the app, for example Email updates, a cloud AI provider, or a job source.
- **Backup** saves everything to one password-protected file. **Delete everything** (Settings) removes all Job Explorer data from your computer.
- Uninstalling the Microsoft Store version deletes all of its data from your computer. Make a backup first if you might want it later.
- Your information is on your computer, so you can view, change, or export it in the app at any time. We don't hold a copy, so there's nothing for us to access, correct, or delete for you.

## Children

Job Explorer is meant for adults looking for work. It isn't directed at children under 16, and we don't knowingly collect information from them.

## Changes

If this policy changes, the new version will be posted at this address with a new effective date. Changes that affect how your information is shared will also be noted in the app's release notes.

## Contact

Questions about this policy: [YOUR SUPPORT EMAIL]
