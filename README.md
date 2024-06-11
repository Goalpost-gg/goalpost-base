![Goalpost Logo](https://goalpost.nyc3.cdn.digitaloceanspaces.com/images/logo_small.png)

# [GOALPOST.gg](https://alpha.goalpost.gg)

[<img src="https://upload.wikimedia.org/wikipedia/commons/5/5a/X_icon_2.svg" height=30 width=30 />](https://x.com/G0ALPOST) [<img src="https://goalpost.nyc3.cdn.digitaloceanspaces.com/icons/discord_icon.svg" height=30 width=30 />](https://discord.gg/goalpost) [<img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" width=30 height=30/>](https://t.me/irwynks)

GOALPOST is an exciting player-versus-player (PVP) card game inspired by the traditional Chinese card game "In Between," it combines strategic betting with psychological gameplay to create a fun and engaging experience. Built for speed, security, and scalability on the SOLANA blockchain, GOALPOST ensures fairness, transparency, and low-cost transactions, making it an ideal platform for both casual and competitive gamers.

[Presentation Videos](https://drive.google.com/drive/folders/14pxDRxYOePSnAUyLSKaHZArlfNIWr_dz?usp=sharing)

[GOALPOST.gg BONKathon Alpha](https://alpha.goalpost.gg)

[GOALPOST.gg Investor Pitch Deck](https://www.beautiful.ai/player/-O-52hsWA7NKHB7yk0iR/Goalpost-Private-Sales-FULL-DECK-I-DRAFT)

[Frontend Repository](https://github.com/goalpost-gg/goalpost-frontend)

[Backend Repository (restricted access)](https://github.com/goalpost-gg/goalpost-backend)

> Please reach out to us on telegram or discord should you have any issues accessing or have questions regarding the GOALPOST repositories.

## Motivation

### Onboarding the next billion

As builders, it is our mission to onboard the next billion to the blockchain. We believe this is possible through the creation of highly engaging, dopamine inducing social games built on top of Solana's massive speed and scalability. Blockchain games are currently synonymous with clunky experiences and gameplay - we are intent on changing this preconception.

### A social gaming platform

Unlike other blockchain games, GOALPOST offers a social, interactive experience where players can compete, collaborate, and earn together. Its engaging mechanics ensure high levels of excitement and satisfaction, fostering long-term player retention. Tie in the community based battlepass and seasonal leaderboards, and you have the perfect recipe for a truly community centric, highly social gaming environment.

## How to play?

![Goalpost Bonk Table](https://goalpost.nyc3.cdn.digitaloceanspaces.com/github/bonk_preview.png)

The purpose of the game is straightforward: at the beginning of the game, a player is randomly chosen to start. During each player's turn, three cards are displayed on the table - two cards face up and one card face down. The player whose turn it is must guess if the value of the face-down card falls between the values of the two face-up cards, winning double of their bet if correct. The game operates with a standard 52-card deck, ensuring that while the chances of guessing correctly are high, they are never guaranteed, maintaining an element of excitement and unpredictability in every round.

🔘 Setup: Each game starts with players choosing a table and joining the game by contributing to a communal pot. The ante fee depends on the table they select, ensuring options that suit every player's budget. Each table can accommodate up to 8 players.

🔘 Betting: Players take turns betting on whether the next card drawn will fall between two cards they have been dealt

🔘 Bet Options: Players can choose to place a minimum bet, half the pot, the entire pot, or a custom amount within the set limits. They can also skip their turn if they think the odds are not in their favor.

🔘 Outcome: If the player's guess is correct, they win according to their wager. If not, they lose their bet, and it stays in the communal pot.

🔘 Game Cycle: The game continues in this cycle until the pot is cleared, creating a dynamic and engaging experience where strategy and anticipation are key.

## Building for BONKathon

With the BONKathon coming up, we decided to prioritize the addition of SPL tokens as in game currency to GOALPOST.gg, integrating it into our fee structure and building the experience around the branding. This also gave us the opportunity to take a look at expanding our collaboration with other established blue chip communities with their own community tokens.

GOALPOST is still in active development, and while we have done our utmost to ensure that the current version of the game is bug free for the hackathon, we're sure that there are some that might have slipped through!

GOALpost is currently on devnet.

## Current Implementation

The current version of GOALPOST is the culmination of continuous iteration on feedback received from our alpha testers throughout the closed alpha that began at the close of the Colosseum Hackathon. We have been focusing on polishing the user experience and gameplay while steadily making progress on our roadmap milestones. Below is a brief outline of the current featureset that has been implemented:

### 💳 Seamless Onboarding with Hot Wallets

Players can simply sign in with their discord/email accounts to get started in no time. Every player is given a hot wallet that they can top-up with SOL or other tokens on Solana to play with. The hot wallet system is implemented using the [squads.so multisig SDK](https://docs.squads.so/squads-v3-docs/development/sdk), making it possible to delegate control of these wallets to GOALPOST.

### 🎨 Community Branded Tables

We currently have 3 community partnerships, for which we have implemented community branded tables. Revenue from these tables is shared with the respective communities.

### 💥 Custom Token Integration

In addition to wagering with SOL, our players can now jump into the fray with BONK!

### 🗞️ Aggregated Transactions

GOALPOST makes use of an aggregation framework on the backend to periodically settle the transactions between players and the table pot, reducing the transaction overhead.

### 🤖 A.I. Players

Our A.I. player feature introduces a "play on demand" model to fill liquidity gaps and keep tables active, ensuring a vibrant gaming environment at all times, for both PVP & PVE. Our A.I. implementation makes it possible to have different "personalities" for each on demand player, from full on degen to card shark.

## Next Phase

### 🎲 Switchboard VRF

VRF (Verifiable Random Function) implementation is critical for ensuring the fairness and transparency of the game. Our next step in moving out of alpha will be to integrate on-chain randomization using Switchboard VRF, allowing players to verify the fairness of each game round on-chain to enhance player confidence, leading to greater player retention and engagement.

### 🔑 Matrica Integration

We have secured a partnership with Matrica, and will be integrating their API to create a seamless onboarding process for communities, while making it easy for new users to join and start playing. This collaboration is an integral part

### 🔩 Solana Program

With the proof of concept having served it's purposed, we will be developing a custom solana program to take over the hot wallet/gameplay transaction creation, management, and authority delegation for GOALPOST. Not only will this reduce fee overheads, but it will also allow us to open source our user backend logic and make it possible for other developers and teams to build on top of our technology.

### 🔏 Security Audit

Once the platform is thorougly tested, we will be employing the services of a security auditing team to thoroughly test our platform and vet our technology before moving GOALPOST onto solana mainnet.

## Feature Roadmap

### 🗝️ Private Tables

Due to popular demand, we will adding room/table password and token/NFT gating functionality for user created tables, making it possible to host private games and events.

### 💰 In-game Currency

More than just a point system, playing the game will allow you to earn in-game currency that can be used to level up your experience in GOALPOST, be it through the battlepass or the asset marketplace.

### 🔗 Affiliate and Referral Programs

Introducing an affiliate and referral program where players can earn rewards for bringing new users to the game and leveragign word-of-mouth marketing to grow our user base.

### 👓 Spectator Mode

We will be implementing a spectator mode to allow players to join in on the action and watch their friends (or foes) play GOALPOST while cheering them on. We are also currently discussing the addition of a sidebetting feature to the spectator mode to allow players to place bets on game outcomes, adding an additional layer of excitement and strategy.

### 🏛️ In-Game Asset Marketplace

We aim to build an in-game asset marketplace where players can buy, sell, and trade in-game assets, such as cards, tables, and cosmetics. This will organically promote a vibrant in-game economy, providing players with opportunities to profit and enhance their gaming experience.

### ⚔️ Battle Pass System

GOALPOST will feature a deep battlepass system where players can complete daily and weekly challenges to earn rewards such as tokens, NFTs, and in game assets to customize their tables. In addition to the basic battlepass, we intend on leveraging the full potential of our itegration with Matrica to offer community based battlepass progression, unlockable through NFT/token ownership across multiple chains.

### 🏆 Seasonal Leaderboards:

Keeping in line with creating socially interactive events, we will be introducing seasonal community leaderboards with rewards for top performing communities and individuals in order to foster a competitive environment, motivating players to improve their skills and stay active in the game. Players will be able to choose a community/faction to represent for the season based on their on-chain asset ownership.

### 🏷️ Whitelabeled Tables

Providing branded tables for partners and KOLs to expand the game’s reach through exclusive experiences and special events.

### 🪙 Tokenized Tables w/ cNFTs

Players will be able to create, customize, and own a limited number tokenized tables that will be featured in GOALPOST. Using assets from the in game store, players will be able to enhance their tokenized table to offer, for example, reduced fees, or even different modes. These tokenized tables will be fully tradeable: this creates a player-driven economy where table owners can earn revenue and influence the game environment.

### 🎓 Goalpost Academy:

We plan on launching Goalpost Academy, a suite of videos and tools to teach people how to build an audience and become creators on social platforms, will drive user adoption by empowering users to become Goalpost affiliates and create quality content with our pre-trained GPT models.

## Challenges Moving Forward

### Marketing and Scaling

We will be promoting organic growth of our platform by following a tight release schedule based around building momentum from the alpha testing phase and events with other communities. Below is a brief overview of our immediate timeline heading towards the end of this year:

#### 🎯 Alpha Testing Phase

Focus on bringing alpha testers to play the game on devnet, followed by a private beta tournament with MonkeDAO and Dead King Society on mainnet within the next two weeks.

#### 🏆 Community Tournaments

Organize a larger tournament this summer with 16 communities, scaling the engagement and reach.

#### 📈 Market Consolidation

During the summer, continue to consolidate the community, onboard more white-label partners, and refine the product-market fit.

#### 🎉 Marketing Campaigns

Launch a wild marketing campaign in September, culminating in a launch party in Singapore and the introduction of the core collection and Druids auctions.

#### 🖥️ Web2 Integrations

We are currently in talks with online web2 casinos interested in using Goalpost with their audiences to bridge the gap between web2 and web3 markets. Collaborations with these platforms are scheduled to begin Q4 into Q1 2025.

### Legal Ramifications

Our monetization and tokenomic model is currently being audited to obtain a complete understanding of the legal implications of GOALPOST, especially with regards to the wagering aspect. We will be refactoring GOALPOSTs undelying economic model based on the outcome of this audit (should it be necessary).

## Our Partnerships

We are actively looking for new partnerships that will help us promote GOALPOST while bringing value to all involved parties and communities.

<img src="https://goalpost.nyc3.cdn.digitaloceanspaces.com/icons/monkedao_square.jpg" height=128 /> <img src="https://goalpost.nyc3.cdn.digitaloceanspaces.com/icons/dks.jpeg" height=128 /> <img src="https://goalpost.nyc3.cdn.digitaloceanspaces.com/icons/matrica_light.png" height=127 />

In this spirit, we have formed strategic partnerships with other Solana-based projects (like MonkeDAO, Dead King Society, and Matrica) to foster a collaborative environment with shared events, revenue-sharing models, and cross-promotion to expand the GOALPOST community.

<img src="https://goalpost.nyc3.cdn.digitaloceanspaces.com/icons/bonk_logo.png" height=120 />

We would LOVE to discuss a potential partnership with bonk_inu!!!

## The Core Team

| <img src="https://goalpost.nyc3.cdn.digitaloceanspaces.com/pfps/niko.gif" height=128 width=128 /> | <img src="https://goalpost.nyc3.cdn.digitaloceanspaces.com/pfps/chris.gif" height=128 width=128 /> | <img src="https://goalpost.nyc3.cdn.digitaloceanspaces.com/pfps/irwynks.jpg" height=128 width=128 /> | <img src="https://goalpost.nyc3.cdn.digitaloceanspaces.com/pfps/gaby.jpg" height=128 width=128 /> |
| :-----------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------: |
|                                          Niko (Founder)                                           |                                            Chris (CEO)                                             |                                            Irwynks (CTO)                                             |                                            Gaby (COO)                                             |

# Thank You!

We would like to thank everyone involved in the organization of this edition of BONKathon for the opportunity to showcase GOALPOST.gg, as well as the judges for their consideration! Should you have any questions or encounter any issues trying out the game, please do not hesistate to contact us through telegram or discord!

[<img src="https://upload.wikimedia.org/wikipedia/commons/5/5a/X_icon_2.svg" height=30 width=30 />](https://x.com/G0ALPOST) [<img src="https://goalpost.nyc3.cdn.digitaloceanspaces.com/icons/discord_icon.svg" height=30 width=30 />](https://discord.gg/goalpost) [<img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" width=30 height=30/>](https://t.me/irwynks)
