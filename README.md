# SysAd Test Module
This is the sys ad task for Developers BCWT

Here, we need a Tezos node setup.  

1. Access the server at IP  `44.234.109.19`
2. SSH into Server using the key inside the zip file.
3. Follow the instructions here: https://www.tezos.org.sg/guide-to-setting-up-a-tezos-node/
4. Modify Document `docs/maintainence_plan.md` in this repo for a set of proposals for ensuring 100% uptime and include any sample scripts in the `sample_scripts` folder that you would propose to use to keep node going.

The overall goal of this node is to provide 100% uptime, areas we need to look into are for [4]:

* Ensuring systems administrations team is up to date on Node Operations
* Documenting commands/startup state
* Log Rotation Plans
* RPC Access securely (If available)
* Nginx (or other access details and plan)
* Public services surrounding node.


# Bonus Points
* 'De-Dockerize' the node in order to have lower level access.
* Write a script for getting node metrics into a secure but semi-open scope of requesters.
* Explain what Tezos is... :)

