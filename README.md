# Bug Bounty Wordlists

Essential wordlists for web reconnaissance and vulnerability testing.

## Usage

Clone this repo:
```bash
git clone https://github.com/manojxshrestha/wordlists.git ~/wordlists
```

## Structure

```
wordlists/
├── api/                      # API discovery wordlists
│   ├── endpoints.txt
│   └── raft-large-directories.txt
├── seclists/                 # SecLists subset
│   └── Discovery/
├── Web-Content/              # Web content discovery
│   ├── burp-parameter-names.txt
│   └── raft-medium-directories.txt
├── common.txt                # Common paths & files
├── commonwords.txt           # Common words
├── LFI-Jhaddix.txt          # LFI payloads
├── SQL.txt                   # SQL injection payloads
├── ssrf-payloads.txt        # SSRF payloads
├── subdomains-top1million-110000.txt  # Subdomain enumeration
├── subdomains-top1million-20000.txt
├── traversal.txt             # Path traversal payloads (→ LFI-Jhaddix.txt)
├── sqli.txt                  # SQL injection (→ SQL.txt)
├── wordlist.txt             # Generic wordlist (→ common.txt)
├── users.txt                 # Common usernames
├── passwords.txt             # Common passwords
├── ids.txt                   # ID enumeration patterns
├── extensions.txt            # File extensions for fuzzing
├── origins.txt               # CORS origin testing
├── host-payloads.txt         # Host header payloads
├── cache-headers.txt         # Cache poisoning headers
├── file-upload-bypass.txt    # File upload bypass payloads
├── business-logic-paths.txt  # Business logic testing
├── parameter-names.txt        # HTTP parameter names
├── admin-PATHS.txt           # Admin panel paths
├── graphql-paths.txt          # GraphQL paths
├── graphql-payloads.txt       # GraphQL payloads
├── sensitivejs.txt            # Sensitive JS files
└── ...
```

## Tools Compatible

- ffuf, gobuster, feroxbuster, dirb
- wfuzz, sqlmap, nmap
- nuclei, amass, subfinder
- cariddi, katana, hakrawler

## Credits

- [SecLists](https://github.com/danielmiessler/SecLists)
- [Assetnote](https://wordlists.assetnote.io/)
- Custom curated wordlists

## License

MIT License
