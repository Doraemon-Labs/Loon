# iRingo Siri Plugin for Loon / Quantumult X

This is a custom plugin designed for Loon and compatible with Quantumult X. It integrates with Apple's Siri services through a plugin-based interface, allowing custom configuration and usage.

## 🔧 Manual Installation

### Installation Path

Loon > Configuration > Plugin > Plugin

### Plugin Source URL

Use the following direct plugin file URL:

https://github.com/NSRingo/Siri/releases/latest/download/iRingo.Siri.plugin

### Configuration (For Loon)

When adding the plugin, replace the default arguments section:

#### Original Argument Format:
```ini
argument=[{CountryCode},{SiriLocale},{Region},{SiriResponseLanguageVariant},{LogLevel}]

Replace With:

argument=["US","AUTO","US","AUTO","OFF"]

This sets:
	•	CountryCode to US
	•	SiriLocale to AUTO (auto-detect)
	•	Region to US
	•	SiriResponseLanguageVariant to AUTO
	•	LogLevel to OFF

📦 Using with Quantumult X

Loon plugins are compatible with Quantumult X via the remote resource parser.

Instructions:
	1.	Upload the .plugin file to your own GitHub repository.
	2.	Reference the plugin file via Quantumult X’s Remote Resource feature.

Example:

[plugin]
https://your-github-username.github.io/your-repo/iRingo.Siri.plugin

📝 Notes
	•	This plugin is intended for educational and testing purposes only.
	•	Ensure your configuration and usage comply with local laws and Apple’s terms of service.
	•	AUTO detection depends on device locale and system settings.

📎 Reference
	•	Author’s Documentation Page
	•	Plugin Release Page

⸻

© NSRingo
