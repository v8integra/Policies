# DocStew Privacy Policy

**Effective date:** November 4, 2026
**Publisher:** V8developing

DocStew is a document app for Windows that works on your PC. This policy explains what DocStew does with your information. The short version: your documents stay on your PC, DocStew has no accounts, ads, analytics or tracking, and the few times it connects to the internet are listed below.

## Your documents stay on your PC

DocStew opens, edits, searches and organizes the files in the folders you choose. Everything it does with them happens on your PC:
- reading, editing and searching documents;
- the built-in AI ("Ask My Documents", summaries, "Do it for me", the smart inbox);
- text recognition (OCR) and redaction;
- signatures, reminders, and making PDFs smaller.

DocStew doesn't upload your documents, and V8developing never sees them.

The only exception is the optional cloud AI described below, which sends text only if you turn it on.

## What DocStew doesn't do

- No account or sign-in.
- No advertising.
- No analytics, usage tracking, or crash reports sent anywhere.
- No selling or sharing of your information. V8developing doesn't receive it in the first place.

## When DocStew connects to the internet

DocStew only connects for the reasons below. Every connection is listed in the **Privacy** page's network log inside DocStew, and **Offline mode** blocks all of them except the license check.

1. **Downloading AI models.** When you set up DocStew's AI, or the speech model for meeting transcripts, DocStew downloads the model files from Hugging Face (huggingface.co). Nothing about you or your documents is sent. Hugging Face, like any website, receives your IP address with the request.
2. **Checking your license with the Microsoft Store.** DocStew asks Windows whether you're in the free trial or have bought DocStew. When you buy, the Microsoft Store handles the purchase. DocStew never sees payment details. No document information is sent. Microsoft's privacy statement covers the Store: https://privacy.microsoft.com/privacystatement
3. **Cloud AI, only if you turn it on.** In AI Settings, you can connect a cloud AI provider (Anthropic, OpenAI, Google, or a server you name) with your own API key, and choose which features use it. When a feature you've sent to a cloud provider runs, DocStew sends that provider the text it needs:
   - your question and the passages from your documents that answer it, for Ask My Documents;
   - the document's text, for summaries, writing tools, translation, data extraction, comparing documents, and naming files in the smart inbox;
   - the transcript, for meeting notes;
   - your request plus your folder names and tags, for "Do it for me".

   The provider handles that text under its own privacy policy and terms. Some things always stay on your PC, even with cloud AI turned on:
   - documents in the vault;
   - the search for sensitive information before redaction;
   - the search index itself.

Opening a link yourself (for example "Get an API key") opens your web browser. That isn't DocStew connecting.

## What DocStew stores on your PC

DocStew keeps its working data in its data folder in your Windows user profile:
- **The library:** the list of documents in your folders, a search index of their text, document versions for undo, tags, reminders, and the network log. The log records which site was contacted, why, when, and how many characters were sent. It never records what the text was.
- **Settings:** your choices, such as Offline mode and AI settings.
- **AI models** you've downloaded.
- **Saved signatures and cloud AI API keys,** encrypted with your Windows account. Another account, or the files copied to another PC, can't read them.
- **The vault,** if you use it. Documents in the vault are encrypted with AES-256-GCM, with a key derived from your vault password using Argon2id. Without the password or the recovery key, they can't be read, including by V8developing.
- **Ask My Documents conversations,** so they're still there next time. You can clear them at any time. Conversations about the vault are never kept.

Your documents themselves stay where you put them. DocStew creates new files (such as signed, redacted or smaller copies) next to the originals and doesn't delete your files.

## Removing your information

- Clear Ask conversations with **Clear** in Ask My Documents.
- Delete cloud AI keys in AI Settings, and AI models in AI Settings → Models.
- Uninstalling DocStew from Windows (Settings → Apps) removes its data folder: the library index, settings, models, saved signatures, keys, reminders, and the vault. Export anything you want to keep from the vault first. Your own documents in your folders aren't touched.

## Children

DocStew isn't directed at children under 13 and doesn't knowingly collect information from anyone.

## Changes to this policy

If DocStew's handling of information changes, this policy will be updated and the effective date above changed. Significant changes will also be noted in the app's release notes.

## Contact

Questions about privacy: v8developing@gmail.com
