# AutoSitemapUpdater
AutoSitemapUpdater" is an open-source Continuous Integration (CI) project designed to automate the maintenance of your sitemap.xml file with each commit.

This tool streamlines the process of keeping your sitemap up to date, ensuring search engines have the latest information about your website's structure and content. Simplify your workflow and enhance your site's search engine optimization (SEO) with AutoSitemapUpdater.

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=js,githubactions"/></a>

## Description
AutoSitemapUpdater is a lightweight tool built with JavaScript (JS) that seamlessly integrates with GitHub Actions. It utilizes YAML (YML) configuration files and manipulates XML files to automatically update your sitemap.xml whenever changes are pushed to your repository.

## Setup
To set up AutoSitemapUpdater for your project, follow these steps:

### Project Setup
1. Place the `utils` folder and the `.github` folder at the root of your project.
2. Ensure that your `sitemap.xml` file is located at the root of your project directory.
3. Configure the `Variables to setup` inside `generate-sitemap.js`.
4. Ensure the extension is correct (if you are not using php replace `.php`with `.html`).

### Repository Setup
1. On [GitHub](https://github.com/), open your repository.
2. Go to `Settings`.
3. Then drop `Actions` to open `General`.
4. In `Workflow permissions`, toggle `Read and write permissions`.
5. Then, enable `Allow GitHub Actions to create and approve pull requests`.
6. Don't forget to click on `Save` button below.

That's it! With these simple setup instructions, AutoSitemapUpdater will handle the rest, keeping your sitemap.xml file up to date with each commit.

## Contributing

If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository
2. Create a new branch: `git checkout -b my-feature`
3. Make your changes and commit them: `git commit -am 'Add some feature'`
4. Push the branch to your forked repository: `git push origin my-feature`
5. Submit a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.