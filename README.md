<h1 align="center">keyhacks.sh</h1>

<h4 align="center">
    Automation of tokens/api keys testing.
</h4>

<p align="center">
    <img src="https://img.shields.io/badge/-bash-gray" alt="bash badge">
    <img src="https://img.shields.io/badge/license-MIT-green" alt="MIT license badge">
    <a href="https://twitter.com/intent/tweet?text=https%3a%2f%2fgithub.com%2fgwen001%2fkeyhacks.sh%2f" target="_blank"><img src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fgwen001%2Fkeyhacks.sh" alt="twitter badge"></a>
</p>

<!-- <p align="center">
    <img src="https://img.shields.io/github/stars/gwen001/keyhacks.sh?style=social" alt="github stars badge">
    <img src="https://img.shields.io/github/watchers/gwen001/keyhacks.sh?style=social" alt="github watchers badge">
    <img src="https://img.shields.io/github/forks/gwen001/keyhacks.sh?style=social" alt="github forks badge">
</p> -->

---

## Description

This Bash tool can check the validity of API keys from several services. This is very useful when you want to automate the process of testing leaked secrets.

See KeyHacks project from Streaak:
https://github.com/streaak/keyhacks
"KeyHacks shows ways in which particular API keys found on a Bug Bounty Program can be used, to check if they are valid."

## Install

```
git clone https://github.com/gwen001/keyhacks.sh
```

## Usage

```
$ ./keyhacks.sh
Usage:  <mod> <secrets...

Supported mods are:
  - algolia_api_key
  - asana_access_token
  - aws_secret
  - azure_tenant
  - bitly_access_token
  - branchio_secret
  - browserstack_access_key
  - buildkite_access_token
  - cloudflare_api_token
  - comcast_access_token
  - datadog_api_key
  - deviantart_secret
  - deviantart_access_token
  - dropbox_api_token
  - facebook_appsecret
  - facebook_access_token
  - firebase_custom_token
  - firebase_id_token
  - github_client
  - github_ssh_key
  - github_token
  - gitlab_private_token
  - gitlab_runner_registration_token
  - google_cm
  - google_maps_key
  - heroku_api_key
  - infura_api_key
  - instagram_access_token
  - mailchimp_api_key
  - mailgun_api_key
  - mailjet
  - mapbox_access_token
  - opsgenie_api_key
  - pagerduty_api_token
  - paypal_key_sb
  - paypal_key_live
  - paypal_token_sb
  - paypal_token_live
  - pendo_integration_key
  - salesforce_access_token
  - saucelabs_ukey
  - securitytrails_key
  - sendgrid_api_key
  - slack_api_token
  - slack_webhook
  - square_secret
  - square_auth_token
  - travisci_api_token
  - twilio_sid_token
  - twitter_api_secret
  - twitter_bearer_token
  - spotify_access_token
  - stripe_key_live
  - wakatime_api_key
  - wompi_auth_bearer_sb
  - wompi_auth_bearer_live
  - wpengine_api_key
  - zapier_webhook
  - zendesk_access_token
```

---

<img src="https://raw.githubusercontent.com/gwen001/keyhacks.sh/main/preview.png" />

---

Feel free to [open an issue](/../../issues/) if you have any problem with the script.  

