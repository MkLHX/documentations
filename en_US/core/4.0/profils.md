The Profile page allows you to configure certain behavior of
User-specific Jeedom : home page themes of the
desktop version, mobile version, graphics… It allows
also to change your password.

You can find it at the top right by clicking on the snowman icon
then Profile (followed by your username).

themes
======

The themes panel allows you to adjust interface parameters :

-   **Desktop** : themes to use in desktop mode, be careful only the
    default theme is officially supported by Jeedom

-   **Color mobile** : allows to choose the interface color
    (here everything is supported)

-   **Desktop Graphics** : allows you to define the default theme for
    graphics in desktop mode

-   **Mobile Graph** : allows you to define the default theme for
    mobile graphics

-   **Opacity by Dashboard widgets** : allows to give opacity
    (between 0 and 1) widgets on the dashboard

-   **Opacity by Design widgets** : allows to give opacity
    (between 0 and 1) widgets on designs

-   **Opacity by View widgets** : allows to give opacity (between
    0 and 1) widgets on the views

-   **Opacity by Mobile widgets** : allows to give opacity
    (between 0 and 1) mobile widgets

Interface
---------

Allows you to define certain interface behaviors :

-   **General**

    -   **Show menus** : tell Jeedom to display the panel
        left, when it exists, as a reminder this panel is
        available on most plugin pages, as well as
        page of scenarios, interactions, objects….

-   **Default page** : default page to display when
    desktop / mobile connection

-   **Default object on the dashboard** : default display object
    upon arrival on the dashboard / mobile

-   **Default view** : view to display by default when arriving on
    the dashboard / mobile

-   **Default design** : design to display by default when
    the arrival on the dashboard / mobile

    -   **Full screen** : default display in full screen when
        the arrival on the designs

-   **Dashboard**

    -   **Unfold the scenario panel** : allows to make visible
        by default the scenario menu (on the right) on the dashboard

    -   **Unfold the objects panel** : allows to make visible by
        default the objects menu (on the left) on the dashboard

-   **View**

    -   **Unfold the view panel** : allows to make visible by
        default views menu (left) on views

security
--------

-   **2-step authentication** : allows to configure
    2-step authentication (as a reminder, this is a changing code
    displayed every X seconds on a mobile application, type
    google authentificator). Note that double authentication will only be requested for external connections. For local connection the code will therefore not be requested. Important if during the configuration of the double authentication you have an error check that jeedom (see on the health page) and your phone are at the same time (1 min difference is enough so that it does not work)

-   **Password** : allows you to change your password (do not
    forget to retype it below)

-   **User hash** : your user API key

### Active sessions

Here you have the list of your currently connected sessions, their ID,
their IP as well as the date of last communication. Clicking on
&quot;Logout&quot; will log out the user. Attention if it is on
a registered device this will delete the recording.

### Registered device

Here you find the list of all registered devices (which are
connect without authentication) to your Jeedom and the date of
last use. Here you can delete the recording of a
peripheral. Attention it does not disconnect it but will just prevent
its automatic reconnection.

Notifications
-------------

-   **User notification command** : Default command for
    join you (message type command)
