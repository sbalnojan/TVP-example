# Thinnest Viable Platform (TVP) Example using a Data Platform

Below the defintion of a TVP.

## Thinnest Viable Platform Definition

Examples of a Thinnest Viable Platform (TVP) as defined in the book Team Topologies.

> A TVP is a careful balance between keeping the platform small and ensuring that the platform is helping to accelerate and simplify software delivery for teams building on the platfom. (p.101, _Team Topologies_)

This material is based on some of the ideas in the book _Team Topologies_ by Matthew Skelton [@matthewskelton](https://github.com/matthewskelton) and Manuel Pais [@manupaisable](https://github.com/manupaisable).

## Example of a TVP for DataModels-as-a-Service

Our imaginary company looks like your typical med sized company, 100+ developers, a few business analysts & SQL-savvy people in departments like sales, marketing. Obviously, for these business analysts, just hacking SQL queries into a GUI ain't perfect. They create reports & dashboards to improve decision making in their departments.

To help them better deliver on that, we just decided to build a thin "platform", to simplify & accelerate their work,
(which is to create a basis for improved decisions).

---

### Imaginary Corp DataModels-as-a-Service

![Image Corp Logo](images/image_corp_logo.jpg)

We use [dbt](https://docs.getdbt.com/docs/introduction) to manage our _Data Models_. Use the following workflow to create your new model:

- Test your SQL with your favourite SQL-tool
- Create a new model in the repository [data-models](https://www.google.com)
- Follow the instructions in the [data-models](https://www.google.com) repository to test your model
- Create a PR. It will be reviewed & deployed by team [data-platform](https://www.google.com)

Use the following resources to build your model

- We follow the EL (T) framework. We thus dump all source data as raw data into the "raw" schema.
- You can find the documentation, which you will need, here [dbt-source-models](https://www.google.com)
- We use [dbt tests](https://docs.getdbt.com/docs/building-a-dbt-project/tests) to test the models. Read them up and create one or two for your model!

Our Service Agreement:

- This service/platform is run by team [data-platform](https://www.google.com).
- We review PRs within 3 working days.
- We run models every 1 hr.
- We react to incidents within 4 working hours (between 9am-5pm).

Roadmap:

- Q2: Provide a wrapper around the [data-models](https://www.google.com) repository to test your model
  & automatically deploy models that do not exceed a runtime of 15 mins. (automatic PR approval,
  to speed up your work.)
- Q3: Integrate data-models support into a GUI to reach business analysts without git knowledge.

---
