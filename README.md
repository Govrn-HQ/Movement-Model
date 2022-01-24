# Movement Model

Communities hub to set up and interact with their Govrn Movement Model

## What is the Movement Model?

The Govrn Movement Model is a govern-to-earn framework that enbales communities to create a reward system for community contributions. Communities create a list of "contribution" (e.g. Contributing to documentation, voting on proposals, etc) and assign a point value to that contribution. For example, you can see the Movement Model setup we use for the Govrn Communitiy [here](https://github.com/Govrn-HQ/foundation/blob/main/Govrn-Movement-Model.csv).

## The Community Folder

There is one important section for you to know, the communities folder. For every community using a Govrn Movement Model, we have a folder setup with their Reward Framework and all reported contributions.

Additionally, the communities folder contains Movement Model Framework templates for communities as a starting place as they set up their Movement Model Framework.

## How do contributions get reported?

The single source of truth of "cosidered" contributions (contributions that are used for reward calculations) is what is submitted to each communities' respective Github file. This is done via a community submitting a PR to the repo.

For ease we've created two tools, a Discord Bot and Community Approval Portal, for communities to reduce operating effort:

1. Govrn Discord Bot - Kevin Malone: The Govrn Discord Bot goes by the name of Kevin Malone. Kevin can be loaded into your community server, and allows users to self report their contributions. When using Kevin Malone, we can automatically generate the approval file for communities to approve reported transactions.
2. Community Approval Portal: Once contributions are reported, community leaders can go into our approval portal to check contributions for legitamacy and approve community contributions. By using our approval portal, we're able to automatically generate the PR request for communities to merge once they've completed their approval process.

## How to setup your own Movement Model?

Setting up your own Movement Model is simple and easy.

1. Navigate to the Communities folder
2. Fork the Repo
3. Navigate to the "Movement Model Template Folder"
4. Create a copy of the folder and rename the new folder with the title of your community
5. We have several Movement Model Starter Templates to choose from. Choose the one that most closely aligns with your community and customize as needed.
6. Once you're happy with your initial Movement Model Framework, all you have to do is join the Govrn eco-system by adding yourself as a Govrn Community!
   1. To do this, first make a fork of the Govrn Foundations Repo
   2. Then, add your community to the `govrn_communities.csv` file.
   3. The information we need is **the name of your communitiy** and **the file pathway**. The file pathway is the everything that comes after `github.com` in the url of the website of your repo! (for example the Govrn one is: `Govrn-HQ/Movement-Proposals/tree/main/communities/Govrn`)

The Govrn team will review the PR in the order we recieve them to ensure they are set up correctly. Once it passed out tests, we will merge it into our Repo and your community will be all set up to start using adding contributions to receive rewards!
