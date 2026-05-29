# Store Listing Draft

## App Name

Speak2Docs

## Short Description

Realtime voice question answering over your selected documents.

## Full Description

Speak2Docs lets you add PDFs, Markdown, and structured JSON sources, build a local retrieval index, and ask questions by voice using OpenAI realtime models. The app keeps document indexes on device and uses your OpenAI API key for realtime answers and optional keyword enrichment after you allow OpenAI processing in the app.

## Reviewer Notes

The app requires microphone permission for realtime voice interaction. Core functionality also requires an OpenAI API key. Reviewers can use a temporary test key, if provided, or enter their own key in Settings.

OpenAI data use: Speak2Docs uses OpenAI as the third-party AI service for realtime transcription, voice answers, retrieval support, and optional keyword enrichment. Before sending data to OpenAI, the app shows an in-app permission screen explaining that microphone audio, transcripts, prompts, selected document passages, and optional keyword-generation text may be sent to OpenAI. The user can allow or cancel, and can later review or revoke this permission in Settings. Documents and indexes remain local unless selected context is sent to OpenAI for these features. Speak2Docs does not use a separate developer backend for OpenAI requests; the user's OpenAI API key authenticates requests directly to OpenAI.

Suggested reviewer flow:

1. Open Settings and enter an OpenAI API key.
2. Add or use bundled sample documents.
3. Wait for document processing to finish.
4. Select one or more ready documents.
5. Tap Connect, review the OpenAI Data Processing screen, and choose Allow OpenAI Processing.
6. Tap Connect again if needed, then ask a question about the selected documents.

## Keywords

voice, documents, PDF, question answering, retrieval, AI, OpenAI, notes, research

## Support And Privacy URLs

- Support URL: https://fwaris.github.io/docs/
- Terms of Use URL: https://fwaris.github.io/docs/fsvoice/terms.html
- Privacy Policy URL: https://fwaris.github.io/docs/fsvoice/privacy.html
- Third-Party Software License URL: https://fwaris.github.io/docs/fsvoice/third-party-notices.html
