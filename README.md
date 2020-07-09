# AirBand Project - Public Data Repository

This is a public source of data used for the AirBand Project. It's intended use is to offer a private way to share the public data concerning the rural broadband project. Partners can download the curated public data sets for their use. Additionally, partners may fork this repo of data, add to it and keep it private (if desired).

Coming but not available yet: Download, branch, co-mingle data intended for public use, and then issue a pull request to add to the public data set thus sharing unique private data with the remainder of the ISP community supporting rural internet projects.

This repo is not intended for binaries or source code.

## Datasets currently utilized for the rural broadband project

| Data Source                   | Useful Links |
| -----------                   | ------------|
|FCC Broadband Data             | https://opendata.fcc.gov/Wireline/Fixed-Broadband-Deployment-Data-Jun-2019-Status-V1/sgz3-kiqt |
|                               | http://gis-fcc.opendata.arcgis.com/ |
|FCC Antenna Structure Registration System| https://wireless2.fcc.gov/UlsApp/AsrSearch/asrRegistrationSearch.jsp
|Census Bureau                  | https://www.census.gov/programs-surveys/acs/data/data-via-ftp.html |
|                               | https://www.census.gov/programs-surveys/ahs/data.html |
|Data.gov                       | https://catalog.data.gov/dataset |
|                               | https://www.911.gov/pdf/911_Data_Information_Sharing_Strategic_Plan_Final.pdf |
|CAF -II Data                   | http://gis-fcc.opendata.arcgis.com/datasets/auction903-results-public?geometry=-272.849%2C5.379%2C46.018%2C55.444 |
|                               | https://caf2map.com/ |
|RDOF Data                      | http://gis-fcc.opendata.arcgis.com/datasets/rural-digital-opportunity-fund-auction-904-eligible-tracts |
|USDA Reconnect Grant Data/Map  | https://reconnect.usda.gov/s/ |
|                               | https://reconnect.usda.gov/s/rd-rdae-mapping-tool |
| Housing Address Points        | http://results.openaddresses.io/|
 |                              | https://github.com/openaddresses |


## Downloadable Data sets - Census 477 data (all states, not split)

| Description                   | Download link (Public Azure Blob Storage) |
| -------------                 | ------------------------------------------|
| Broadband 2018 block group    | https://atistoragerepo.blob.core.windows.net/airbandispdata/broadband_2018_blockgroup.geojson |
| Broadband 2018 county         | https://atistoragerepo.blob.core.windows.net/airbandispdata/broadband_2018_county.geojson |
| Broadband 2018 Tract          | https://atistoragerepo.blob.core.windows.net/airbandispdata/broadband_2018_tract.geojson |

## Current intended use of this data

AS the project evolves, data such as sourced above will continue to be integrated into visualization and analytics tools.

## Updates
5/27/2020: Added data sets broken down by state. All state data is in geojson form. 

5/13/2020: Census 477 Data uploaded to public Azure Blob Storage. Description - Census TIGER/Line joined to FCC477 (wireline only) for 2018. See table above for download links. Coming soon - all datasets split into separate state files. 

4/29/2020: No datasets are hosted in this repo. The list above represents a non-exhaustive list of data sets currently in use or being evaluated by the Airband team.

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.
