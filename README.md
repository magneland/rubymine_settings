# rubymine_settings

This is a RubyMine Settings Repository for macOS.

It allows you to sync AppFolio-specific settings to your local RubyMine installation.

It is read-only to prevent clobbering.

# Usage

From the official documentation:

    On each computer where you want your settings to be applied, select

    File | Manage IDE Settings | Settings Repository from the main menu.
    
    Specify the URL of the repository you've created, and click Overwrite Local.
    
    You can click Merge if you want the repository to keep a combination of the
    remote settings and your local settings.

    If any conflicts are detected, a dialog will be displayed where you can
    resolve these conflicts.

    If you want to overwrite the remote settings with your local settings,
    click Overwrite Remote.

For more information:
https://www.jetbrains.com/help/ruby/sharing-your-ide-settings.html#settings-repository
and:
https://www.jetbrains.com/help/ruby/settings-tools-settings-repository.html

# History

Previously, we used [dev_workstation](https://github.com/appfolio/dev_workstation) to both install and configure RubyMine.
However, the default config dir [changed](https://intellij-support.jetbrains.com/hc/en-us/articles/206544519-Directories-used-by-the-IDE-to-store-settings-caches-plugins-and-logs
) in 2020.1.
We could override the default config dir, but using a Settings Repository seems easier.
