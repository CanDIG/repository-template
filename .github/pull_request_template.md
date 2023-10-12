<!--- This is a template for a standard PR against the develop branch of the repo, if you are making a stable release PR, append '?template=stable_pr_template.md' to the end of your URL above ^ --->

<!--- Please name your pull request with the Jira ticket referende (DIG-[0-9]*) it is fixing and a descriptive title --->

# Ticket(s)
<!--- List any related Jira tickets here --->

-

# Description
<!--- Describe the change that was made and anything the reviewer should be aware of --->



# Related
<!--- List any related PRs or information here if any exist. --->

-

# To test
<!--- Describe what is needed to test the change --->

## Screenshots (if appropriate)

### Before PR

### After PR

## To do/Tickets to be made before merging branch

-

## Types of Change(s)

-   [ ] 🪲 Bug fix (non-breaking change that fixes an issue)
-   [ ] ✨ New feature (non-breaking change that adds functionality)
-   [ ] 💥 Breaking change (fix or feature that would cause existing functionality to change)
  - Which other services does it affect?
    - [ ] authx
    - [ ] data-portal
    - [ ] ingest
    - [ ] clinical ETL
    - [ ] federation
    - [ ] htsget-app
    - [ ] katsu
    - [ ] CanDIG OPA
    - [ ] Query

## Has it been tested for:

-   [ ] My change requires a change to the documentation
-   [ ] I have updated the documentation accordingly
-   [ ] Prettier linter doesn't return errors
-   [ ] Locally tested
  - [ ] using stable release
  - [ ] using develop branches
-   [ ] Dev server tested
-   [ ] Production tested when merging into stable/production branch
