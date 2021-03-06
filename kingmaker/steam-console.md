<!-- TITLE: Using Steam to Download Previous Versions -->

[&larr; Pathfinder: Kingmaker](/kingmaker)

If you want to see more resources like this, [become a Patreon supporter!](https://www.patreon.com/fireundubh) 

# Using Steam to Download Previous Versions
## Step by Step

1. With Steam running, press `Win+R` and enter this URL: `steam://nav/console` ([link](steam://nav/console)).
2. Enter the following command: `download_depot <app_id> <depot_id> <manifest_id>` (refer to the Reference tables below)
3. The depot will begin downloading. You should receive a notification when the download is complete.

The depot will likely download to: `C:\Program Files (x86)\Steam\steamapps\content\app_640820\depot_640821\` (or wherever Steam is installed)

Once downloaded, you can move the depot anywhere.

## Syntax

```
download_depot <app_id> <depot_id> <manifest_id> [<delta_manifest_id>]
```

Parameter | Required | Description
--- | --- | ---
`app_id` | `true` | the game's App ID
`depot_id` | `true` | the Depot ID corresponding to a content package (e.g., binaries, game assets)
`manifest_id` | `true` | the Manifest ID corresponding to a version of the content package
`delta_manifest_id` | `false` | the Manifest ID corresponding to a previous version of the content package

If the `delta_manifest_id` argument is not omitted, Steam will download only the differences between the target manifest and delta manifest.

### Example

Download the game content:

```
download_depot 640820 640821 6741447117850778077
```

## Optional

### Change the download path

You cannot change the path to which the depot downloads; however, you can "trick" Steam into downloading depots wherever you want using Junction Points.

What are Junction Points? Junction Points are a type of symbolic link unique to the NTFS file system.

If Steam was installed on your `C:` drive, and you wanted to download the depot to `D:`, you would do the following:

1. Delete the `app_640820` folder, if any, in `C:\Program Files (x86)\Steam\steamapps\content`.
2. Create a folder on `D:` named `app_640820`, such as `D:\app_640820`.
3. In a cmd shell, type: `mklink /J "C:\Program Files (x86)\Steam\steamapps\content\app_640820" "D:\app_640820"`
4. Then, run the `download_depot` command in the Steam Console.

If you do not know how to open the cmd shell, press `Win+R`, type `cmd`, and press `Enter`.

## Reference

### App and Depots

Type | Value | Description
:--- | :--- | :---
App ID | `640820` | Pathfinder: Kingmaker
Depot ID | `640821` | Pathfinder: Kingmaker Content

### Depot: _Pathfinder: Kingmaker Content_

Manifest ID | Version | Date | Size (GB) | Timezone
:--- | :--- | :--- | ---: | :---
`513119536492443724` | 1.1.2 | 2018-11-29 | 10-28-54 | UTC
`568166937022414569` | 1.1.1 Hotfix | 2018-11-23 | 20-59-52 | UTC
`6841280346056458271` | 1.1.1 Hotfix | 2018-11-23 | 12-33-13 | UTC
`8410446097109498345` | 1.1.1a | 2018-11-22 | 12-42-13 | UTC
`3237457528724341205` | 1.1.1 | 2018-11-16 | 23-57-42 | UTC
`3970314610931200324` | 1.1.0 | 2018-11-16 | 08-01-20 | UTC
`3557071040295278012` | 1.0.16 | 2018-11-09 | 11-56-40 | UTC
`8850094342751214757` | 1.0.15 | 2018-11-01 | 09-51-03 | UTC
`6772569451919678332` | 1.0.14 | 2018-10-29 | 11-00-34 | UTC
`332037904899851076` | 1.0.13 | 2018-10-25 | 10-31-50 | UTC
`6319724708078102732` | 1.0.12 | 2018-10-24 | 10-31-45 | UTC
`6843022900013123261` | 1.0.11 | 2018-10-22 | 10-20-05 | UTC
`4137201467282432792` | 1.0.10 | 2018-10-18 | 09-55-03 | UTC
`3329346642708156469` | 1.0.9 | 2018-10-16 | 11-47-06 | UTC
`7773343900112385919` | 1.0.8c | 2018-10-12 | 18-21-28 | UTC
`4551845841087663139` | 1.0.8b | 2018-10-11 | 15-07-55 | UTC
`5750998838144035341` | 1.0.7 | 2018-10-09 | 13-38-33 | UTC
`3625063316203614488` |  | 2018-10-08 | 19-33-21 | UTC
`403950949019027651` |  | 2018-10-07 | 14-22-42 | UTC
`946625482595150857` |  | 2018-10-07 | 13-17-17 | UTC
`6336459653349909543` | 1.0.6 | 2018-10-05 | 15-50-10 | UTC
`7894022154904016667` | 1.0.5 | 2018-10-05 | 09-08-33 | UTC
`4920380694923421717` |  | 2018-10-03 | 04-47-08 | UTC
`6358573070219561752` | 1.0.4 | 2018-10-02 | 16-30-02 | UTC
`229482041491868730` | 1.0.3 | 2018-09-29 | 18-17-02 | UTC
`2451367926564256244` | 1.0.2 | 2018-09-28 | 18-13-51 | UTC
`1412067188604596331` | 1.0.1 | 2018-09-27 | 16-48-23 | UTC
`336132831154623931` |  | 2018-09-25 | 14-20-24 | UTC
`6741447117850778077` |  | 2018-09-25 | 14-02-04 | UTC

## Other Depots and Manifests

You can [find additional depots and manifests](https://steamdb.info/app/640820/depots/) at SteamDB.