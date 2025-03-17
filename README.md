# Galxe & Gravity Contract Addresses

This repository serves as a storage and reference for contract addresses used in Galxe and Gravity across different blockchain networks.

## Structure

The repository contains contract addresses for both mainnet and testnet environments:

- `galxe/mainnet/internal.json` - Contains internal mainnet contract addresses for Galxe
- `galxe/testnet/internal.json` - Contains internal testnet contract addresses for Galxe
- `gravity/mainnet/internal.json` - Contains internal mainnet contract addresses for Gravity
- `gravity/testnet/internal.json` - Contains internal testnet contract addresses for Gravity
- `gravity/mainnet/external.json` - Contains external mainnet contract addresses for Gravity
- `gravity/testnet/external.json` - Contains external testnet contract addresses for Gravity

## Data Format

Each contract record contains the following fields:

1. `chain` - The blockchain network (e.g., ETHEREUM, BSC, MATIC)
2. `type` - Contract type (e.g., SPACE_STATION, TOKEN_REWARD, TOKEN_STATION, L2_STANDARD_GATEWAY)
3. `address` - The deployed contract address
4. `description` - Additional information about the contract
5. `project` - Project name (e.g., Galxe, Gravity, SUCCINCT_SP1)
6. `status` - Contract status (active/inactive/deprecated)

## Example Record

```json
{
  "chain": "ETHEREUM",
  "type": "SPACE_STATION",
  "address": "0x...",
  "description": "",
  "project": "Galxe",
  "status": "active"
}
```
