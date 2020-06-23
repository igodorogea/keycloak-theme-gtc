# GTC custom theme for keycloak login page

### Installation

1. Put theme files inside `{keycloak.install.dir}/themes/gtc`. You can download archive and extract it or clone the repo directly.
1. Restart keycloak, so it will detect changes.
1. To change the theme open the Admin Console, select your realm from the drop-down box in the top left corner. Under Realm Settings click Themes. Choose `gtc` in the select box next to `Login Theme`. Then save changes.

### Setup Microsoft SSO

In order to create an identity provider open the Admin Console, select your realm from the drop-down box in the top left corner, then click the Identity Providers left menu item.  
In the drop down list box, choose Microsoft provider. This will bring you to the configuration page. You should add `Client ID`
and `Client Secret` then save. The button will appear automagicaly on login page.
