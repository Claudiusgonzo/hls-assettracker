## Contents

Outline the file contents of the repository. It helps users navigate the codebase, build configuration and any related assets.

| File/folder       | Description                                |
|-------------------|--------------------------------------------|
| `src`             | Sample source code.                        |
| `.gitignore`      | Define what to ignore at commit time.      |
| `CHANGELOG.md`    | List of changes to the sample.             |
| `CONTRIBUTING.md` | Guidelines for contributing to the sample. |
| `README.md`       | This README file.                          |
| `LICENSE`         | The license for the sample.                |

## Starter Kit Challenge

This Starter Kit is intended to help healthcare organizations manage physical assets like beds and equipment criticial to the COVID effort. 
1. Healthcare organization wants a means of quickly capturing state (availabile, used for COVID patient, used for non-COVID patient, under maintenance) and location of assets.
  1. start with beds and ventilators, but could include other assets
2. Healthcare organization wants a means of querying for location of assets that meet specified criteria.
3. Healthcare organizaton wants a means of reporting on asset availability.
4. Healthcare organization wants to be able to share (export) data with other providers.
5. Healthcare organization wants to be able to import data from other providers.

## Desired Skills & Technologies

- UI development - was thinking about a Power App that could be used cross-platform, but open to other thoughts. (Another thought was a bot!)
- Web API - was thinking about a collection of Azure Functions that represent reading/writing to the data store.
- data store - was thinking "no-SQL" store, but Azure SQL Database is nice small, cheap option as well.
- Power BI - starter reports that allow them to quickly visualize asset availability, location, etc.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
