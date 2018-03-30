<!-- TITLE: Using Steam to Download Previous Versions -->

If you want to see more resources like this, [become a Patreon supporter!](https://www.patreon.com/fireundubh) 

# Using Steam to Download Previous Versions
## Step by Step

1. With Steam running, press `Win+R` and enter this URL: `steam://nav/console` ([link](steam://nav/console)).
2. Enter the following command: `download_depot <app_id> <depot_id> <manifest_id>`
3. The depot will begin downloading. You should receive a notification when the download is complete.

The depot will likely download to: `C:\Program Files (x86)\Steam\steamapps\content\app_379430\depot_379432\` (or wherever Steam is installed)

Once downloaded, you can move the depot anywhere.

## Optional

### Change the download path

You cannot change the path to which the depot downloads; however, you can "trick" Steam into downloading depots wherever you want using Junction Points.

What are Junction Points? Junction Points are a type of symbolic link unique to NTFS file systems.

If Steam was installed on your `C:` drive, and you wanted to download the depot to `D:`, you would do the following:

1. Delete the `app_379430` folder in `C:\Program Files (x86)\Steam\steamapps\content`.
2. Create a folder on `D:` named `app_379430`, such as `D:\app_379430`.
3. In a cmd shell, type: `mklink /J "C:\Program Files (x86)\Steam\steamapps\content\app_379430" "D:\app_379430"`
4. Then, run the `download_depot` command in the Steam Console.

## Reference

### Arguments

Type | Value | Description
--- | --- | ---
App ID | `379430` | Kingdom Come: Deliverance
Depot ID | `379432` | goldmaster
Manifest ID | `5725479270789300781` | Version 1.4 (without HD textures) - March 29, 2018 – 23:16:26 UTC 
Manifest ID | `8087559557021397984` | Version 1.4 (with HD textures) - March 29, 2018 – 20:34:19 UTC
Manifest ID | `5914698958093409181` | Version 1.3.4 - March 23, 2018 – 18:52:42 UTC
Manifest ID | `2336283802842258594` | Version 1.3.3 - March 14, 2018 – 12:05:18 UTC
Manifest ID | `5466979519765255293` | Version 1.3.2 - March 10, 2018 – 17:01:41 UTC
Manifest ID | `6648306801271692541` | Version 1.3.1 - March 9, 2018 – 18:02:55 UTC
Manifest ID | `5922355296132692872` | Version 1.3 - March 9, 2018 – 15:23:15 UTC
Manifest ID | `189591112647295182`| Version 1.2.5 (likely game + OST) - February 21, 2018 – 16:55:57 UTC
Manifest ID | `5015448431446448432` | Version 1.2.5 - February 20, 2018 – 16:07:25 UTC
Manifest ID | `7728356487649391633` | Version 1.2 - February 13, 2018 – 19:09:01 UTC
Manifest ID | `1574197374724500814` | Version 1.1 - February 13, 2018 – 08:01:41 UTC

### Depots and Manifests

You can [find additional depots and manifests](https://steamdb.info/app/379430/depots/) at SteamDB.