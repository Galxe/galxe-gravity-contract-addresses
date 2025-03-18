# Galxe & Gravity Contract Addresses

This repository serves as a storage and reference for contract addresses used in Galxe and Gravity across different blockchain networks.

## Structure

The repository contains contract addresses for both mainnet and testnet environments, separated into internal (self-deployed/managed) and external (partner-deployed/integrated) contracts:

### Galxe Contracts
- `galxe/mainnet/internal.json` - Contains mainnet contract addresses deployed and managed by **Galxe** team
- `galxe/testnet/internal.json` - Contains testnet contract addresses deployed and managed by **Galxe** team
- `galxe/mainnet/external.json` - Contains mainnet contract addresses from partner projects integrated with **Galxe**
- `galxe/testnet/external.json` - Contains testnet contract addresses from partner projects integrated with **Galxe**
  
### Gravity Contracts
- `gravity/mainnet/internal.json` - Contains mainnet contract addresses deployed and managed by **Gravity** team
- `gravity/testnet/internal.json` - Contains testnet contract addresses deployed and managed by **Gravity** team
- `gravity/mainnet/external.json` - Contains mainnet contract addresses from partner projects integrated with **Gravity**
- `gravity/testnet/external.json` - Contains testnet contract addresses from partner projects integrated with **Gravity**

## Data Format

Each contract record contains the following fields:

1. `chain` - The blockchain network (e.g., GRAVITY_MAINNET, ETHEREUM, BSC, MATIC)
2. `type` - Contract type (e.g., SPACE_STATION, TOKEN_REWARD, TOKEN_STATION, L2_STANDARD_GATEWAY)
3. `address` - The deployed contract address
4. `description` - Additional information about the contract
5. `project` - Project name (e.g., Galxe, Gravity, SUCCINCT_SP1, LayerZero, Camelot)
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
