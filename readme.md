# 🛡️ Phishing URL Detector

A client-side cybersecurity web application that analyzes URLs
for common phishing indicators.

## Features

- HTTPS detection
- IP address detection
- Suspicious `@` symbol detection
- URL length analysis
- Subdomain analysis
- Suspicious keyword detection
- URL shortener detection
- Domain structure analysis
- Risk score from 0–100
- Low, Medium and High risk classification
- Responsive interface
- No backend or API required

## Technologies

- HTML5
- CSS3
- JavaScript
- URL API

## How It Works

The application uses heuristic-based analysis.

Each security check examines a different characteristic of the
submitted URL.

Suspicious characteristics increase the risk score.

### Example

A URL using:

- HTTP instead of HTTPS
- An IP address
- Multiple suspicious keywords
- Excessive subdomains
- A URL shortener

will receive a higher risk score.

## Running the Project

1. Clone the repository.

```bash
git clone https://github.com/YOUR_USERNAME/phishing-url-detector.git
