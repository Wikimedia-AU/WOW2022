# WOW2022 website

Scraped in April 2023 with the following:

```
wget \
--span-hosts \
--domains wixstatic.com,wixsite.com,wix.com,parastorage.com \
--page-requisites \
--adjust-extension \
--convert-links \
--restrict-file-names=windows \
--no-parent \
-e robots=off \
https://<user>.wixsite.com/website-1 \
https://<user>.wixsite.com/website-1/program \
https://<user>.wixsite.com/website-1/team-4 \
https://<user>.wixsite.com/website-1/about-3 \
https://<user>.wixsite.com/website-1/your-visit
```

And then tidied up by hand.
