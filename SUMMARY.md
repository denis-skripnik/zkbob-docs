# Table of contents

## 🦹 zkBob Overview

* [zkBob](README.md)
* [Basic Concepts](zkbob-overview/basic-concepts/README.md)
  * [Getting Started](zkbob-overview/basic-concepts/getting-started.md)
  * [Multichain Deployment](zkbob-overview/basic-concepts/multichain-deployment.md)
  * [Usage Statistics](zkbob-overview/basic-concepts/usage-statistics.md)
  * [Use Cases](zkbob-overview/basic-concepts/use-cases/README.md)
    * [Employee Salary](zkbob-overview/basic-concepts/use-cases/employee-salary.md)
    * [Vendor Purchasing](zkbob-overview/basic-concepts/use-cases/vendor-purchasing.md)
  * [Development Timeline](zkbob-overview/basic-concepts/development-timeline.md)
  * [zk Privacy Solution Comparison](zkbob-overview/basic-concepts/zk-privacy-solution-comparison.md)
* [zkBob Pools](zkbob-overview/zkbob-pools/README.md)
  * [USDC Pool on Polygon](zkbob-overview/zkbob-pools/usdc-pool-on-polygon.md)
  * [USDC Pool on Optimism](zkbob-overview/zkbob-pools/usdc-pool-on-optimism.md)
  * [ETH Pool on Optimism](zkbob-overview/zkbob-pools/eth-pool-on-optimism.md)
* [Fees](zkbob-overview/fees/README.md)
  * [Unspent note handling](zkbob-overview/fees/unspent-note-handling.md)
* [Deposit & Withdrawal Limits](zkbob-overview/deposit-and-withdrawal-limits.md)
* [Compliance & Security](zkbob-overview/compliance-and-security/README.md)
  * [TRM Labs Integration](zkbob-overview/compliance-and-security/trm-labs-integration.md)
* [Conferences, Workshops, Videos](zkbob-overview/conferences-workshops-videos/README.md)
  * [International Videos](zkbob-overview/conferences-workshops-videos/international-videos.md)
* [Governance](zkbob-overview/governance.md)
* [BOB Stablecoin](zkbob-overview/bob-stablecoin.md)
* [zkBob FAQ](zkbob-overview/faq.md)

## 🦸♂ zkBob Application <a href="#zkbob-app" id="zkbob-app"></a>

* [UI Overview](zkbob-app/zkbob-app.md)
* [Account Creation](zkbob-app/account-creation/README.md)
  * [Login to an existing account](zkbob-app/account-creation/login-to-an-existing-account.md)
  * [Lost Password](zkbob-app/account-creation/lost-password.md)
  * [Metamask / Web3 Wallet Warning](zkbob-app/account-creation/metamask-web3-wallet-warning.md)
* [Deposits](zkbob-app/deposits.md)
* [Transfers](zkbob-app/transfers/README.md)
  * [Multitransfers](zkbob-app/transfers/multitransfers.md)
* [Withdrawals](zkbob-app/withdrawals/README.md)
  * [Native Token Conversion](zkbob-app/withdrawals/native-token-conversion.md)
* [Generate a Receiving Address](zkbob-app/generate-a-secure-address.md)
* [Optional KYC](zkbob-app/optional-kyc.md)
* [Get BOB](zkbob-app/get-bob.md)
* [zkBob Direct Deposits](zkbob-app/zkbob-direct-deposits.md)
* [Support ID](zkbob-app/support-id.md)
* [Integrated Services](zkbob-app/integrated-services.md)
* [Multilingual support](zkbob-app/multilingual-support/README.md)
  * [Português](zkbob-app/multilingual-support/portugues.md)

## 👩⚕ Technical Implementation <a href="#implementation" id="implementation"></a>

* [zkBob Application Overview](implementation/high-level-overview.md)
* [Deployed Contracts](implementation/deployed-contracts.md)
* [Smart Contracts](implementation/contracts-and-circuits/README.md)
  * [zkBob Pool Contract](implementation/contracts-and-circuits/the-pool-contract/README.md)
    * [Transaction Calldata](implementation/contracts-and-circuits/the-pool-contract/transaction-calldata.md)
  * [Bob Token Contract](implementation/contracts-and-circuits/token-contract.md)
  * [Verifier contracts](implementation/contracts-and-circuits/verifier-contracts.md)
  * [Operator Manager Contract](implementation/contracts-and-circuits/operator-manager-contract/README.md)
    * [Mutable Operator Manager](implementation/contracts-and-circuits/operator-manager-contract/mutable-operator-manager.md)
  * [Voucher (XP) Token Contract](implementation/contracts-and-circuits/voucher-token-contract.md)
* [Accounts and Notes](implementation/account-and-notes/README.md)
  * [Accounts](implementation/account-and-notes/accounts.md)
  * [Notes](implementation/account-and-notes/notes.md)
* [Relayer Node](implementation/relayer-node/README.md)
  * [Relayer Operations](implementation/relayer-node/relayer-operations.md)
  * [Optimistic State](implementation/relayer-node/optimistic-state.md)
  * [REST API](implementation/relayer-node/rest-api.md)
* [zkBob Keys](implementation/zkbob-keys/README.md)
  * [Address derivation](implementation/zkbob-keys/address-derivation.md)
  * [Ephemeral keys](implementation/zkbob-keys/ephemeral-keys.md)
* [zkSNARKs & Circuits](implementation/zksnarks-and-circuits/README.md)
  * [Transfer verifier circuit overview](implementation/zksnarks-and-circuits/transaction-verifier-circuit.md)
* [zkBob Merkle Tree](implementation/untitled/README.md)
  * [The Poseidon Hash](implementation/untitled/the-poseidon-hash.md)
* [Elliptic Curve Cryptography](implementation/elliptic-curve-cryptography.md)
* [Transaction Overview](implementation/transaction-overview/README.md)
  * [Common Structure](implementation/transaction-overview/common-structure.md)
  * [Memo Block](implementation/transaction-overview/untitled-1/README.md)
    * [Memo Block Encryption](implementation/transaction-overview/untitled-1/memo-block-encryption.md)
  * [Transaction Types](implementation/transaction-overview/transaction-types.md)
  * [Nullifiers](implementation/transaction-overview/the-nullifiers.md)
  * [Signing a Transaction](implementation/transaction-overview/signing-a-transaction.md)
  * [The Transaction Lifecycle](implementation/transaction-overview/the-transaction-lifecycle.md)
* [Client Library SDK](implementation/client-library-sdk/README.md)
  * [Configuration](implementation/client-library-sdk/configuration/README.md)
    * [Initializing the client](implementation/client-library-sdk/configuration/initializing-the-client/README.md)
      * [Client Configuration](implementation/client-library-sdk/configuration/initializing-the-client/client-configuration.md)
    * [Attaching a User Account](implementation/client-library-sdk/configuration/attaching-a-user-account/README.md)
      * [Account Configuration](implementation/client-library-sdk/configuration/attaching-a-user-account/account-configuration.md)
    * [Switching Between Pools](implementation/client-library-sdk/configuration/switching-between-pools.md)
  * [Account-less Mode Operations](implementation/client-library-sdk/account-less-mode-operations/README.md)
    * [Converting Token Amounts](implementation/client-library-sdk/account-less-mode-operations/converting-token-amounts.md)
    * [Transaction Fees](implementation/client-library-sdk/account-less-mode-operations/transaction-fees.md)
    * [Transaction Constraints](implementation/client-library-sdk/account-less-mode-operations/transaction-constraints.md)
    * [Using the Delegated Prover](implementation/client-library-sdk/account-less-mode-operations/using-the-delegated-prover.md)
    * [Getting the State](implementation/client-library-sdk/account-less-mode-operations/getting-the-state.md)
    * [Gift Cards](implementation/client-library-sdk/account-less-mode-operations/gift-cards.md)
    * [Helpers](implementation/client-library-sdk/account-less-mode-operations/helpers.md)
    * [Versioning](implementation/client-library-sdk/account-less-mode-operations/versioning.md)
  * [Full Mode Operations](implementation/client-library-sdk/full-mode-operations/README.md)
    * [Balances and History](implementation/client-library-sdk/full-mode-operations/balances-and-history.md)
    * [Shielded Addresses](implementation/client-library-sdk/full-mode-operations/shielded-addresses.md)
    * [Account State](implementation/client-library-sdk/full-mode-operations/account-state.md)
    * [Fee Estimations](implementation/client-library-sdk/full-mode-operations/fee-estimations.md)
    * [Transaction Configuration](implementation/client-library-sdk/full-mode-operations/transaction-configuration.md)
    * [Sending Transactions](implementation/client-library-sdk/full-mode-operations/sending-transactions.md)
    * [Transaction Maintenance](implementation/client-library-sdk/full-mode-operations/transaction-maintenance.md)
    * [Direct Deposits](implementation/client-library-sdk/full-mode-operations/direct-deposits.md)
    * [Gift Cards Maintenance](implementation/client-library-sdk/full-mode-operations/gift-cards-maintenance.md)
    * [Ephemeral Deposits](implementation/client-library-sdk/full-mode-operations/ephemeral-deposits.md)
    * [Other Routines](implementation/client-library-sdk/full-mode-operations/other-routines.md)
  * [Common Types](implementation/client-library-sdk/common-types.md)
  * [Full Functions List](implementation/client-library-sdk/full-functions-list.md)
  * [Utilities](implementation/client-library-sdk/utilities.md)

## 👩🏫 Deployment

* [Trusted Setup Ceremony](deployment/trusted-setup-ceremony.md)
* [Contract Deployment](deployment/contracts-deployment.md)
* [Relayer Subsystem](deployment/relayers-subsystem.md)

## 👷♂ Roadmap

* [On the Roadmap](roadmap/on-the-roadmap.md)
* [Exploratory Features](roadmap/exploratory-features/README.md)
  * [XP (Experience Points)](roadmap/exploratory-features/xp/README.md)
    * [XP-based Auctions](roadmap/exploratory-features/xp/xp-based-auctions.md)
  * [Multi-chain Custom Rollup Deployment](roadmap/exploratory-features/multi-chain-custom-rollup-deployment.md)
  * [Round-robin Operator Manager](roadmap/exploratory-features/round-robin-operator-manager.md)
  * [Compounding](roadmap/exploratory-features/compounding.md)

## 🧑💻 Jobs

* [Zero-Knowledge Researcher & Protocol Developer](jobs/zero-knowledge-researcher-and-protocol-developer.md)

## 🧩 Resources

* [Visual Assets](resources/visual-assets.md)
* [Hackathons](resources/hackathons/README.md)
  * [zkBob Cloud](resources/hackathons/zkbob-cloud.md)
* [Release Notes](resources/release-notes/README.md)
  * [October 11, 2023](resources/release-notes/october-11-2023.md)
  * [July 13, 2023](resources/release-notes/july-13-2023.md)
  * [June 13, 2023](resources/release-notes/june-13-2023.md)
  * [March 28, 2023](resources/release-notes/march-28-2023.md)
  * [January 30, 2023](resources/release-notes/january-30-2023.md)
  * [January 16, 2023](resources/release-notes/january-16-2023.md)
  * [January 2, 2023](resources/release-notes/january-2-2023.md)
  * [Releases 2022](resources/release-notes/releases-2022.md)
* [Security Audit](resources/security-audit.md)
* [Github](https://github.com/zkbob)
* [Link tree](https://linktr.ee/zkbob)
