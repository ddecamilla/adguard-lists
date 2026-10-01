# AdGuard Lists

Custom DNS blocklists for AdGuard Home.

## Adult AI Blocklist

`lists/adult-ai.txt`

Blocks domains associated with:

- Adult AI image and video generation
- Adult AI chat and companion services
- AI-generated adult content
- Directories and discovery sites that promote these services

### AdGuard Home

Add the following URL as a custom DNS blocklist:

https://raw.githubusercontent.com/YOUR-USERNAME/YOUR-REPO/main/lists/adult-ai.txt

In AdGuard Home:

1. Open **Filters → DNS blocklists**
2. Select **Add blocklist**
3. Select **Add a custom list**
4. Name it **Adult AI Blocklist**
5. Paste the Raw GitHub URL above

## Contributing

Domains can be added to `lists/adult-ai.txt` using AdGuard filtering syntax:

`||example.com^`

This blocks the domain and its subdomains.