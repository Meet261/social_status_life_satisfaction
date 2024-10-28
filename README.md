# social_status_life_satisfaction
https://mybinder.org/v2/gh/Meet261/social_status_life_satisfaction/HEAD
Launch Online [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Meet261/social_status_life_satisfaction/HEAD)

| **File Name**              | **Dependencies**                                                                                  | **Reproducibility Status** | **Issue/Obstacle**                                                                                                                                                                                        | **Suggested Solution**                                                                                                                                          |
|----------------------------|--------------------------------------------------------------------------------------------------|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `stadyl_analyses.R`         | `haven`, `psych`, `dplyr`, `car`, `ggplot2`, `interactions`, `lm.beta`, `reghelper`, `Hmisc`     | Not Reproducible            | The dataset is read from a local path (`/Users/maria/Documents/projects/_collabs/anticip_status/data/StadyL_Study2.sav`). This path is specific to a local machine and not accessible in Binder.             | Upload the dataset to a public repository (e.g., OSF) and download it during the Binder setup using a `postBuild` file with the `wget` command.                 |

## Acknowledgments

This project uses data and resources from [Social Status and Life Satisfaction: The Role of Future Expectations](https://osf.io/r4wg2/). We acknowledge the contributions of the authors of the original project. Please refer to the [Social Status and Life Satisfaction: The Role of Future Expectations](https://osf.io/r4wg2/) for more details.

