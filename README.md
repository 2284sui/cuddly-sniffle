# SWYSTEMS group website
URL: [www.swystems.usi.ch](https://swystems.usi.ch)

Website built with [**Wowchemy**](https://wowchemy.com) and generated with [Hugo](https://github.com/gohugoio/hugo).

Original template: [Hugo Research Group Theme](https://github.com/wowchemy/starter-hugo-research-group)

## Editing guides 

- 👉 [**Get Started**](https://wowchemy.com/hugo-themes/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy research community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- ⬇️ **Automatically import citations from BibTeX** with the [Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli)
- 🐦 Share your new site with the community: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=%23MadeWithWowchemy&src=typed_query)
- 🗳 [Take the survey and help us improve #OpenSource](https://forms.gle/NioD9VhUg7PNmdCAA)
- 🚀 [Contribute improvements](https://github.com/wowchemy/wowchemy-hugo-themes/blob/main/.github/contributing.md) or [suggest improvements](https://github.com/wowchemy/wowchemy-hugo-themes/issues)
- ⬆️ **Updating?** View the [Update Guide](https://wowchemy.com/docs/hugo-tutorials/update/) and [Release Notes](https://github.com/wowchemy/wowchemy-hugo-themes/releases)

## Run website locally
- clone the repository
- Install [Hugo](https://gohugo.io/)
- from the repository folder, run:
```sh
hugo server
```
## Deploy to swystems.usi.ch

### Get access to the USI website server
People with access as of 15/11/2022:
- Davide
- Shamiek
- Patrick

If you don't have access, ask Massimiliano Florio (massimiliano.florio@usi.ch). Details:

- Host Name: swystems.usi.ch
- Document Root: /var/opt/www/usi_swystems/docs
- Mysql Credential in: /var/opt/www/usi_swystems/conf/MySQL.account_info
- PhpMyAdmin Access: https://swystems.usi.ch/mysqladmin/

### Update the website
From this folder, generate the static website running:
```sh
hugo # build the website in public/ folder
```

Copy website to the USI server
> Website folder: `/var/opt/www/usi_swystems/docs` 

- Using a client such as [FileZilla](https://filezilla-project.org/) (Recommended). <br>
Set up a new SFTP connection using the GUI with *username: username@usi.ch, remote server: swystems.usi.ch, password: yourUSIpassword*.

- From a terminal: `sftp "username@usi.ch"@swystems.usi.ch` <br>
Password is the same as the email. Once logged in, you can use [sftp](https://sftptogo.com/blog/sftp-commands-cheat-sheet/) commands to copy the locally generated website to the remote webfolder