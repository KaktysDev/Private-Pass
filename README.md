# Private-Pass

This project uses zxcvbn, an open-source password strength estimation library developed by Dropbox. The library analyzes passwords by checking length, character variety, and common patterns such as dictionary words, repeats, sequences, and predictable substitutions.

It estimates approximate crack times by simulating different attack scenarios (for example, offline brute-force attacks) and provides a strength score with human-readable feedback.

All analysis runs entirely locally on your device. Passwords are never stored, sent to a server, or logged in any way. This tool is purely client-side and designed with privacy as a core principle.

