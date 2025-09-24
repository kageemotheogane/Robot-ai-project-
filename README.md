# Robot AI Project - Full Flutter Skeleton

This is a full Flutter project skeleton prepared for Codemagic builds. BEFORE building, replace YOUR_API_KEY in lib/main.dart with your OpenAI API key (for quick testing).

IMPORTANT: Embedding the API key in the app is NOT secure for production. For production, move API calls to a server and keep secrets server-side.

How to build (locally):
1. flutter pub get
2. flutter build apk --release

Codemagic usage:
- Upload this project to a GitHub repo, connect the repo in Codemagic, and run a Flutter Android build.
