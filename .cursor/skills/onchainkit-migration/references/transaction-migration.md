# Transaction Migration: OnchainKit Transaction to wagmi

Replace OnchainKit's `Transaction`, `TransactionButton`, `TransactionStatus`, and related components with direct wagmi transaction hooks.

*This migration guide is under development. Check back for updates.*

## What OnchainKit's Transaction Components Do

OnchainKit provides:
- `<Transaction />` -- container that manages transaction lifecycle
- `<TransactionButton />` -- button that submits the transaction
- `<TransactionStatus />` -- displays transaction status (pending, success, error)
- `<TransactionSponsor />` -- handles gas sponsorship via paymaster
- `<TransactionToast />` -- toast notifications for transaction events

## wagmi Equivalents

The core wagmi hooks for transactions:
- `useSendTransaction()` -- send a basic ETH transfer or raw transaction
- `useWriteContract()` -- call a contract function
- `useWaitForTransactionReceipt()` -- wait for confirmation
- `useEstimateGas()` -- estimate gas before sending

## Placeholder

Detailed migration instructions and component code will be added here once the transaction migration pattern is finalized and tested.
