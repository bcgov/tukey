---

title: "Tukey Theme"
description: "Custom themes for DPDD projects"

---
# Keycloak Theme

This is a simple Keycloak theme for use with DPDD web properties and implements the simplified [AtlasKit Reduced UI Pack](https://atlaskit.atlassian.com/packages/css-packs/reduced-ui-pack). See the [Keycloak documentation on themes](https://www.keycloak.org/docs/latest/server_development/index.html#deploying-themes) to see how to install themes.

Currently this theme only reskins both the login and the login 2-factor auth code forms.

### Installation

If using Docker you can copy the `tukey-theme` and/or `tukey-theme-providers-only` directory and contents to `/opt/jboss/keycloak/themes`. Then in the admin theme tab you can assign `tukey-theme` to the login page.

## License

    Copyright 2020 Province of British Columbia

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at 

       (http://www.apache.org/licenses/)LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.