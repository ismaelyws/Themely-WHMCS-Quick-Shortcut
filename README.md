# Themely WHMCS Quick Shortcut

#### Add a shortcut to Themely in the Quick Shortcuts panel of WHMCS.

## Installation Instructions

Follow the instructions below.

**Step 1**

[Download](https://github.com/ismaelyws/Themely-WHMCS-Quick-Shortcut/archive/master.zip) the contents of this repository.

**Step 2**

Upload the `/img` and `/templates` folders (and files) to following directory `/WHMCS_ROOT/modules/servers/cpanel/`

Important Note: If you have already modified the overview.tpl file, follow Step #1 and modify the overview.tpl file by adding the following code after line 215.

	<!-- THEMELY QUICK SHORTCUT START -->
	<div class="col-sm-3 col-xs-6" id="cPanelThemely">
	    <a href="clientarea.php?action=productdetails&amp;id={$serviceid}&amp;dosinglesignon=1&amp;app=themely" target="_blank">
	        <img src="modules/servers/cpanel/img/wordpress.png" />
	        One-Click WordPress Installer
	    </a>
	</div>
	<!-- THEMELY QUICK SHORTCUT END -->

## Get Help/Support

To get assistance with the Themely WHMCS hook or to suggest new features; here's how you can reach us:

[Create new issue on Github](https://github.com/ismaelyws/themely-whmcs-hook/issues) (click the green **New Issue** button)

[Chat with us on Discord](https://discord.gg/f3m2Pmp)

Send an email to `hans@themely.com`

Call or text on Whatsapp `+1 (514) 883-0132`

Time Zone: Eastern Standard Time (GMT -4)

Spoken & written languages: English, Français, Español (un poquito)

Office Location: Montreal, Canada