<h1 align="center" style="border-bottom: none">
  <div>
    <a href="https://www.signfo.com">
      <img  alt="Signfo" src="https://github.com/DrrWebDeveloper/signfo/assets/5418788/c12cd051-81cd-4402-bc3a-92f2cfdc1b06" width="80" />
      <br>
    </a>
    Signfo
  </div>
</h1>
<h3 align="center">
  Open source document filling and signing
</h3>
<p align="center">
  <a href="https://hub.docker.com/r/docuseal/docuseal">
    <img alt="Docker releases" src="https://img.shields.io/docker/v/docuseal/docuseal">
  </a>
  <a href="https://discord.gg/qygYCDGck9">
    <img src="https://img.shields.io/discord/1125112641170448454?logo=discord"/>
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=docusealco">
    <img src="https://img.shields.io/twitter/follow/docusealco?style=social" alt="Follow @docusealco" />
  </a>
</p>
<p>
Signfo is an open source platform that provides secure and efficient digital document signing and processing. Create PDF forms to have them filled and signed online on any device with an easy-to-use, mobile-optimized web tool.
</p>
<h2 align="center">
  <a href="https://demo.signfo.com">✨ Live Demo</a>
  <span>|</span>
  <a href="https://signfo.com/sign_up">☁️ Try in Cloud</a>
</h2>

[![Demo](https://github.com/DrrWebDeveloper/signfo/assets/5418788/d8703ea3-361a-423f-8bfe-eff1bd9dbe14)](https://demo.signfo.com)

## Features
- PDF form fields builder (WYSIWYG)
- 12 field types available (Signature, Date, File, Checkbox etc.)
- Multiple submitters per document
- Automated emails via SMTP
- Files storage on disk or AWS S3, Google Storage, Azure Cloud
- Automatic PDF eSignature
- PDF signature verification
- Users management
- Mobile-optimized
- Signing available in 13 languages
- API and Webhooks for integrations
- Easy to deploy in minutes

## Pro Features
- Company logo and white-label
- User roles
- Automated reminders
- Invitation and identify verification via SMS
- Conditional fields and formulas
- Bulk send with CSV, XLSX spreadsheet import
- SSO / SAML
- Template creation with HTML API ([Guide](https://www.signfo.com/guides/create-pdf-document-fillable-form-with-html-api))
- Template creation with PDF or DOCX and field tags API ([Guide](https://www.signfo.com/guides/use-embedded-text-field-tags-in-the-pdf-to-create-a-fillable-form))
- Embedded signing form ([React](https://github.com/DrrWebDeveloper/signfo-react), [Vue](https://github.com/DrrWebDeveloper/signfo-vue), [Angular](https://github.com/DrrWebDeveloper/signfo-angular) or [JavaScript](https://www.signfo.com/docs/embedded))
- Embedded document form builder ([React](https://github.com/DrrWebDeveloper/signfo-react), [Vue](https://github.com/DrrWebDeveloper/signfo-vue), [Angular](https://github.com/DrrWebDeveloper/signfo-angular) or [JavaScript](https://www.signfo.com/docs/embedded))
- [Learn more](https://www.signfo.com/pricing)

## Deploy

|Heroku|Railway|
|:--:|:---:|
| [<img alt="Deploy on Heroku" src="https://www.herokucdn.com/deploy/button.svg" height="40">](https://heroku.com/deploy?template=https://github.com/DrrWebDeveloper/signfo-heroku) | [<img alt="Deploy on Railway" src="https://railway.app/button.svg" height="40">](https://railway.app/template/IGoDnc?referralCode=ruU7JR)|
|**DigitalOcean**|**Render**|
| [<img alt="Deploy on DigitalOcean" src="https://www.deploytodo.com/do-btn-blue.svg" height="40">](https://cloud.digitalocean.com/apps/new?repo=https://github.com/DrrWebDeveloper/signfo-digitalocean/tree/master&refcode=421d50f53990) | [<img alt="Deploy to Render" src="https://render.com/images/deploy-to-render-button.svg" height="40">](https://render.com/deploy?repo=https://github.com/DrrWebDeveloper/signfo-render)

#### Docker

```sh
docker run --name docuseal -p 3000:3000 -v.:/data docuseal/docuseal
```

By default Signfo docker container uses an SQLite database to store data and configurations. Alternatively, it is possible use PostgreSQL or MySQL databases by specifying the `DATABASE_URL` env variable.

#### Docker Compose

Download docker-compose.yml into your private server:
```sh
curl https://raw.githubusercontent.com/docusealco/docuseal/master/docker-compose.yml > docker-compose.yml
```

Run the app under a custom domain over https using docker compose (make sure your DNS points to the server to automatically issue ssl certs with Caddy):
```sh
sudo HOST=your-domain-name.com docker compose up
```

## For Businesses
### Integrate seamless document signing into your web or mobile apps with Signfo

At Signfo we have expertise and technologies to make documents creation, filling, signing and processing seamlessly integrated with your product. We specialize in working with various industries, including **Banking, Healthcare, Transport, Real Estate, eCommerce, KYC, CRM, and other software products** that require bulk document signing. By leveraging Signfo, we can assist in reducing the overall cost of developing and processing electronic documents while ensuring security and compliance with local electronic document laws.

[Book a Meeting](https://www.signfo.com/contact)

## License

Distributed under the AGPLv3 License. See [LICENSE](https://github.com/DrrWebDeveloper/signfo/blob/master/LICENSE) for more information.
Unless otherwise noted, all files © 2023 Signfo LLC.

## Tools

- [Signature Maker](https://www.signfo.com/online-signature)
- [Sign Document Online](https://www.signfo.com/sign-documents-online)
- [Fill PDF Online](https://www.signfo.com/fill-pdf)
