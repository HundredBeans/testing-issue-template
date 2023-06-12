_TODO: Replace all TODO sections and examples with relevant notes, and go through each item the checklist BEFORE submitting this PR. Delete this top TODO._

## Proposed Changes
_TODO: The 2 sections below should be the message when this PR is squash merged._

#### Code changes
_TODO: What changes have you made with this PR? Where were those changes?_
- Added `createPerson` mutation to the _person-service_
- Created new webhook route handler for the X integration
- Removed invalid field `names` from graphql `people` query
- Added tests for the graphql people query
- Added README to the review service

#### Issues affected
_TODO: Which GitHub issues does this PR affect?_
- Fixes #0000
- Partially addresses #0001

## Additional Info
_TODO (optional): Any additional information to add?_

## Screenshots and/or Loom video
_TODO (optional): Add screenshots of changes, and/or a Loom video demonstrating those changes._

## Testing Plan
_TODO: Provide a systematic approach the reviewer can follow to validate your changes. It should be thorough and roughly mirror your own testing process._

## Deployment Plan
_TODO: List services to be deployed, and backfills to be run. If services need to be deployed in a certain order, or with certain conditions, note these._

- [ ] Update EXP schemata by updating exp branch to master
- [ ] `nj deploy route frontend`
- [ ] `nj deploy route-graphql -i`
- [ ] `nj deploy function person -m`

## Checklist

_TODO: Please make sure your code is compliant with point in the checklist. Check each box._

#### Basics
- [ ] Code abides by the code [Style Guide](https://api.nicejob.com/docs/engineering/style-guide)
- [ ] Touched `.js` files have been converted to `.ts` and types added where reasonable
- [ ] All unit, integration, and end-to-end tests are passing in affected services and modules
- [ ] Local QA is complete
- [ ] No debugging `console.log()` statements
- [ ] Commented-out code removed
- [ ] Common code lives in [one of two places](https://api.exp.nicejob.com/docs/engineering/style-guide#2:~:~:text=2.2%20%2D%20Common%20code%20lives%20in%20one%20of%20two%20places%3A&text=2.2%20%2D%20Common%20code%20lives%20in%20one%20of%20two%20places)
- [ ] Unused code removed (imports, functions, styles, etc - if it's not used anywhere, it's not in this PR)

#### Documentation
- [ ] Documentation added where appropriate

#### Tests
- [ ] Unit, integration, and end-to-end tests added where appropriate
