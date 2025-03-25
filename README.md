[![Board Status](https://dev.azure.com/rajadsh/f7850c39-4ba9-4ae1-813a-efddc6fa8e13/df782807-438c-4a06-b2df-c649fb14e61f/_apis/work/boardbadge/d4cc1c98-4bfb-4c7d-ab5b-368e84f7931a)](https://dev.azure.com/rajadsh/f7850c39-4ba9-4ae1-813a-efddc6fa8e13/_boards/board/t/df782807-438c-4a06-b2df-c649fb14e61f/Microsoft.RequirementCategory)
# Airflow DAGs for dbt

> The code in this repository is meant to accompany [this blog post](https://astronomer.io/blog) on beginner and advanced implementation concepts at the intersection of dbt and Airflow.

To run these DAGs locally:
1. Download the [Astro CLI](https://github.com/astronomer/astro-cli)
2. Download and run [Docker](https://docs.docker.com/docker-for-mac/install/)
3. Clone this repository and `cd` into it.
4. Run `astro dev start` to spin up a local Airflow environment and run the accompanying DAGs on your machine.

We are currently using a [sample `manifest.json`](https://github.com/fishtown-analytics/dbt-docs/blob/master/data/manifest.json) file pulled from the dbt docs, but if you would like to try these dags with your own dbt workflow, feel free to copy and paste your `manifest.json` file into the `dags/dbt/target/` directory.