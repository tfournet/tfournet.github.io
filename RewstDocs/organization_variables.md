# What are organization variables? 

ORG variables are used to apply values at the organization and sub-org layers. A managing organization's organization variables inherit to sub-organizations unless the sub-org has the same variable defined, in which case it will be overriden by that value.

Organization variables are referred to by `{{ ORG.VARIABLES.<variable_name> }}`

# ORG Variables used in Rewst Crates & Workflows

| Variable                    | Use                                                   | Valid Values            |
| ---                         | ---                                                   | ---                     |
| `primary_identity_provider` | Specify where users are created for the organization. | `on_prem` or `Azure_AD` |
