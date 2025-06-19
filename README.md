# Module Kowal Theme for Magento 2

    ``kowal/module-admin-theme``

- [Main Functionalities](#markdown-header-main-functionalities)
- [Installation](#markdown-header-installation)


## Main Functionalities
Szablon Highline dla Magento 2

## Installation
\* = in production please use the `--keep-generated` option

### Type: Composer

1. **The module is available in a composer repository:**

2. **Add the composer repository to the configuration:**
   ```bash
   composer config repositories.admin.theme vcs https://github.com/kowalco/magento-2-admin-theme


3. **Add an access token for the private GitLab repository:**
   ```bash
   composer config --global --auth github-oauth.github.com <YOUR_TOKEN>

4. **Install the module using Composer:**
   ```bash
   composer require kowal/module-admin-theme

5. **Apply database updates:**
   ```bash
   php bin/magento setup:upgrade
6. **Flush the cache:**
   ```bash
   php bin/magento cache:flush