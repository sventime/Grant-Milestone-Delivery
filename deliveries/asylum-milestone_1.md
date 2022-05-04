# Milestone Delivery :mailbox:

**The [invoice form :pencil:](https://docs.google.com/forms/d/e/1FAIpQLSfmNYaoCgrxyhzgoKQ0ynQvnNRoTmgApz9NrMp-hd8mhIiO0A/viewform) has been filled out correctly for this milestone and the delivery is according to the official [milestone delivery guidelines](https://github.com/w3f/Grants-Program/blob/master/docs/milestone-deliverables-guidelines.md).**  

* **Application Document:** [Asylum](https://github.com/w3f/Grants-Program/tree/master/applications/asylum.md).
* **Milestone Number:** e.g. 1

**Context**

The first milestone covers:
 - the on-chain pallets implementation of NFT-item standards;
 - web app integrated with on-chain to configure NFT-items and basic Game entities.

**Deliverables**

| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 0a. | License | [Asylum UI](https://gitlab.com/asylum-space/asylum-ui/-/blob/main/LICENSE), [Asylum Item NFT](https://gitlab.com/asylum-space/asylum-item-nft/-/blob/main/LICENSE) | All Asylum projects have MIT license| 
| 0b.  | Documentation |[Asylum Core Pallet](https://gitlab.com/asylum-space/asylum-item-nft/-/blob/main/pallets/asylum-core/README.md), [Asylum Game Distribution System Pallet](https://gitlab.com/asylum-space/asylum-item-nft/-/blob/main/pallets/asylum-game-distribution/README.md)| Core module utilises [`RMRK`](https://rmrk-team.github.io/rmrk-substrate/#/pallets/rmrk-core) and [`pallet_uniques`](https://docs.rs/pallet-assets/latest/pallet_uniques/) and manages NFT semanthics, metadata and tranferability. Game Disctribution System module maganes the Game entity: metadata, game pass, associated game client.| 
| 0c.  | Testing Guide |[Asylum pallets testing guide](https://gitlab.com/asylum-space/asylum-item-nft/-/blob/main/docs/testing-guide.md), [Asylum UI testing guide]()|<ol>There are 3 options to interact with Asylum node: <li>PolkadotJS app </li> <li>Asylum UI/Connection Library npm package</li> <li>Asylum UI/Game Developer console web app</li></ol> | 
|1.| Item standard definition | [Asylum entities relations diagram](https://gitlab.com/asylum-space/asylum-item-nft/-/blob/main/docs/img/asylum-flow-diagram.png) | Template, Interpretation, Tag and Item relation provides a possibility to create in-game items with multiple visual and mechanics represantation |
|2.| Asylum Core Pallet | [Asylum Core Pallet](https://gitlab.com/asylum-space/asylum-item-nft/-/blob/main/pallets/asylum-core) | Asylum Core Pallet provides NFT items transferability and ability to manage items meatadata and represantation in different contexts |
|3.| Connection Library | [Asylum UI/Connection Library](https://gitlab.com/asylum-space/asylum-ui/-/tree/main/packages/connection-library) | Asylum Connection Library is an npm package, written in typescript, which ease integration with Asylum pallets providing clear API|
|4.| Web Application | [Asylum UI/Game developers console](https://gitlab.com/asylum-space/asylum-ui/-/tree/main/packages/game-developers-console) | Web app, written in React and designed for game developers to create and manage Asylum entities: create item templates, manage interpetations, mint NFTs.|
