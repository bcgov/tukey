---

title: "Tukey Theme"
description: "Custom themes for DPDD projects"

---
# Keycloak Theme

This is a simple Keycloak theme for use with DPDD web properties and implements the simplified [AtlasKit Reduced UI Pack](https://atlaskit.atlassian.com/packages/css-packs/reduced-ui-pack). See the [Keycloak documentation on themes](https://www.keycloak.org/docs/latest/server_development/index.html#deploying-themes) to see how to install themes.

Currently this theme only reskins both the login and the login 2-factor auth code forms.

### Installation

If using Docker you can copy the contents of the `theme` folder to `/opt/jboss/keycloak/themes/tukey-theme`. Then in the admin theme tab you can assign `tukey-theme` to the login page.