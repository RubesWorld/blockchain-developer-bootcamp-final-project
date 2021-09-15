# Blockchain-developer-bootcamp-final-project

## Simple Explanation
A blockchain solution to optimize the contractual transactions within the Waste Management Industry. A platform where the entire waste management lifecycle is on a public ledger, from manifest creation to load pick-up to drop-off validation. 

## Industry Background
The Waste Management industry is a billion dollar industry that will never cease to exist. Garbage is forever. The relationships within the industry are highly contractual. Landfills (1) make contracts with waste collection companies (2) who make contracts with local municipalities and commercial businesses that server as their accounts(3). There are instances in which a waste management company may handle both the garbage drop-off at the landfill and the collection and transportation of the garbage. Generally, the contracts are as follows:

Landfills make an agreement with a waste collection company that ALL of their garbage will go to the land fill for a specific period of time. When the contract ends, the companies negotiate the rate per tonnage of trash and send invoices to the waste collection companies on a monthly basis as the garbage is weighed and dropped off at the landfill. 

This means the garbage producer wants to keep their numbers low while the landfill wants to see the tonnage high, as it leads to a higher invoice payment for them. Here is the conflict of interest factor that is required for a blockchain platform.

## The Status Quo
The current system heavily relies on employees to verify that these transactions happen using paperwork that must be verified by multiple parties. The waste collection HQ sends manifests, or pick-up orders, to the truck drivers who then complete their routes for the day. Each garbage collector picks up the garbage and then heads to the landfill to make drop-offs. If a truck driver has 10 routes, they will do 10 visits to the landfill per day. 

When a truck driver arrives to the scale house at the landfill, they drive on the scale, take their paper manifest document that has their account number to the scale house worker where the truck & load are verified and the weight is entered into the database and written on the document. At the end of the month, the waste collection company sends invoices to each account that has a total of their tonnage for the month.

## The Blockchain Solution
- [x] Database Needed
- [x] Multiple Writers
- [x] Writers have conflict of interests
- [x] Can't rely on a trusted 3rd party

This platform would be a consortium, as it wouldn't need to be public, but would be closed between a government agency, the garbage accounts and the waste management company. 

There are efficiencies that could come to this industry that could improve operational and processing time, lower operational cost and have a reliable ledger for government agencies to validate and reward proper garbage disposal.

# Project Scope 
For this project, I will be focusing on the validity of a smart contract being created when a weight is confirmed and being executed when that specific weight threshold is reached from a connected scale. 


## Workflow
1. A Driver enters his credentials to enter the system and view his garbage assignments 
2. The Driver scans in to pick-up the garbage load weight
3. The smart contract is created based on this particular weight stating that the financial transaction will occur if and only if this weight threshold is met
4. The Driver arrives to the scale house and scans. The weight is verified and the smart contract is executed between the account and the waste management company. 