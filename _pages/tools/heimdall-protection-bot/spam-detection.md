# Spam Detection

***

### Spam Detection <a href="#spam-detection" id="spam-detection"></a>

Over **200 spam patterns** are actively checked against every message. The system uses text normalization to defeat evasion techniques.

| Detection Type             | Description                                                                                                                     |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| **Banned Words**           | Messages containing known spam phrases from a maintained word list                                                              |
| **Scam Patterns**          | "Contact me if you hold X", fake wallet/payment scams, rug pull indicators, phishing attempts                                   |
| **Fake Admins**            | Users impersonating admins via similar names, titles like "CEO", "Dev", or "Owner", or matching the group/token name            |
| **Fake Contracts**         | Users with blockchain addresses in their display names to trick others                                                          |
| **Fake Bots**              | Impostor bots using homograph/lookalike characters in usernames (e.g., capital "I" instead of "l")                              |
| **Text Normalization**     | Cyrillic-to-Latin conversion, Unicode mapping, and number-to-letter substitution (0→O, 1→I) to catch evasion tricks             |
| **Image Hash Matching**    | Perceptual image hashing (DifferenceHash) detects copied or slightly modified spam images, even after cropping or color changes |
| **Similar Name Detection** | Levenshtein distance algorithm catches names visually similar to admin names or the group name                                  |
