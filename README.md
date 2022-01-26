# Movement Model

Community hub to set up and interact with their Govrn Movement Model

## What is the Movement Model?

The Govrn Movement Model is a govern-to-earn framework that enbales communities to create a reward system for community contributions. Communities create a list of "contributions" (e.g. Contributing to documentation, voting on proposals, etc) and assign a point value to each contribution. For example, you can see the Movement Model setup we use for the Govrn Communitiy [here](https://github.com/Govrn-HQ/foundation/blob/main/Govrn-Movement-Model.csv).

## Getting Started

For every community using a Govrn Movement Model, we have a repo set up with their Reward Framework and all reported contributions. To start, have your community's GitHub account fork this repo(Govrn-HQ/Movement-Proposals). It contains the structure (repo organization) and content (Movement Model Framework templates) for communities as a starting place as they set up their Movement Model Framework.

## How do contributions get reported?

The single source of truth of "considered" contributions (contributions that are used for reward calculations) is what is submitted to each community's respective Github repo. This is done via weekly automated PRs to the community's repo.

For ease we've created two tools, a Bot and Community Approval Portal, for communities to reduce operating effort:

1. Govrn Discord Bot - Kevin Malone: The Govrn Discord Bot goes by the name of Kevin Malone. Kevin can be loaded into your community server, and allows users to self report their contributions. When using Kevin Malone, we can automatically generate the approval file for communities to approve reported transactions.
2. Community Approval Portal: Once contributions are reported, community leaders can go into our approval portal to check contributions for legitamacy and approve community contributions. By using our approval portal, we're able to automatically generate the PR request for communities to merge once they've completed their approval process.

## How to set up your own Movement Model?

Setting up your own Movement Model is simple and easy!

1. Fork this Repo
2. Set up your contribution and reward framework.  We have two templates to choose from: `activity_types_CollegeClub_starter.csv` and `activity_types_GrantDAO_starter.csv` for inspiration.  Choose the one that most most closely aligns with your community and customize as needed. **We just ask that you rename your final framework `activity_types.csv`**.  Feel free to delete the unused templates for clarity. (Also note, Task ID column is internal for us, so please leave blank.  The `Active` column denotes a boolean where 1 means those engagements are currently rewardable, and 0 means they have been paused or deprecated.)
3. Set up your contributor type framework.  Do this by navigating to `point_ranges.csv`and adjusting the point ranges your community wants associated with each contributor type.  Don't hesitate to ping us in discord to discuss what might make sense for your community here - it can really vary :)
4. Once you're happy with your initial Movement Model Framework, all you have to do is join the Govrn ecosystem by adding yourself as a Govrn Community!
   1. To do this, first make a fork of the [Govrn Foundations Repo](https://github.com/Govrn-HQ/foundation/tree/main/communities)
   2. Then, add your community to the `govrn_communities.csv` file.
   3. The information we need is **the name of your communitiy** and **the repo pathway**. The repo pathway is everything that comes after `github.com/` in the url of the website of your repo! (for example the Govrn one is: `Govrn-HQ/Movement-Proposals`)

The Govrn team will review the PR in the order we recieve them to ensure they are set up correctly.  Once it passes our tests, we will fork your Repo and send some initial PRs and your community will be all set up to start adding contributions to receive rewards!

Note: If any of the GitHub processes are new for you, we are GitHub enthusiasts and would be more than happy to hop on a call and work through it together :)
