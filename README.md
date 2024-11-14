# Linkwarden Search Engine Integration

## Description

This Violentmonkey UserScript enhances your web browsing experience by letting you search through your Linkwarden bookmarks across multiple search engines. With this script, you can quickly find and access your bookmarks while searching on popular platforms like Google, Bing, DuckDuckGo, and more.

![Linkwarden Search Screenshot](https://cdn.jsdelivr.net/gh/mjysci/imgs@master/blog/linkwardenSearch_screenshot.png)

## Features

- **Search Integration**: Fetch and display your Linkwarden bookmarks directly in the search results of major search engines.
- **Custom Settings**: Configure your Linkwarden URL and API token for secure access to your bookmarks.
- **Pagination**: Navigate through your bookmarks with pagination controls for easier browsing.
- **Stylish Interface**: A clean, modern UI that integrates smoothly into your search experience.

## Installation

1. **Install Violentmonkey**: Make sure the Violentmonkey extension is installed in your browser. You can download it from [here](https://violentmonkey.github.io/).

2. **Install Script**: Click [here](https://github.com/mjysci/hypothesis-search/raw/refs/heads/main/hypothesisSearch.user.js) to open Violentmonkey's Userscript installation page, then click `Install`.

3. **Generate Linkwarden API Token**: Go to Settings -> Access Tokens -> New Access Token to generate an API token.

4. **Settings**: After installation, search for anything on a supported search engine. The `Linkwarden Settings` panel will appear on the first run. Input your Linkwarden URL and API token.

## Usage

1. **Open a Search Engine**: Go to a supported search engine (e.g., Google, Bing, DuckDuckGo).

2. **Search for a Term**: Enter your search term. The script will automatically fetch related Linkwarden bookmarks.

3. **View Boomarks**: Bookmarks will appear in a panel alongside the search results, and you can click on links to view each bookmark in detail.

4. **Settings**: Click the settings icon (⚙️) in the bookmarks panel to configure your Linkwarden URL, API token.

## Example

When you search for "climate change" on Google, the script will display any relevant bookmarks from your Linkwarden account, providing a quick way to reference your notes alongside the search results.

## Requirements

- A valid Linkwarden account on the [official site](https://linkwarden.app/) or a self-hosted server.
- Your Linkwarden API token.

## Contributing

We welcome suggestions or bug reports! To submit a pull request:

1. Check the Issues tab; if there’s no relevant issue, feel free to create one.

2. Submit your PR and link it to a related issue.

## License

This project is licensed under the GPL-3.0 License. See the [LICENSE](https://github.com/mjysci/hypothesis-search/blob/main/LICENSE) file for more information.

## Author

Created by MA Junyi.

---

If you have any questions or feedback, please reach out! Enjoy exploring your bookmarks!
