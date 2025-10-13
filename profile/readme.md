# Fortress Finance

A production-ready multi-asset yield vault with ETH-only investment/redemption, DAO governance, and automated yield generation. Fortress Finance represents a revolutionary approach to decentralized finance by creating a diversified cryptocurrency portfolio that users can access through a single ETH investment, while maintaining community-driven governance and sustainable yield generation.

## Core Philosophy

Fortress Finance is built on the principle that **diversification is the cornerstone of sustainable wealth creation**. Rather than forcing users to manage multiple cryptocurrency positions, we provide a single-entry point (ETH) that automatically diversifies across the three most promising blockchain ecosystems: Bitcoin, Ethereum, and Solana.

## Strategic Vision

Our strategy is designed to capture the long-term value appreciation of the three most established and promising blockchain networks while providing users with:

1. **Simplified Access**: Single ETH investment for diversified exposure
2. **Risk Mitigation**: Diversification across three major blockchain ecosystems
3. **Community Governance**: DAO-driven decision making for protocol evolution
4. **Sustainable Yield**: Automated yield generation through DeFi protocols
5. **Transparent Operations**: Open-source, auditable, and community-controlled

## Project Structure

This repository contains two main components:

- **`contracts/`** - Smart contracts and deployment scripts
- **`dapp/`** - Next.js frontend application for interacting with the vault

## Quick Start

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Git

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd fortress-finance

# Install all dependencies (contracts + dapp)
npm run install:all
```

### Development

```bash
# Start both contracts and dapp in development mode
npm run dev:contracts  # In one terminal
npm run dev:dapp      # In another terminal

# Or run both concurrently (if you have concurrently installed)
npx concurrently "npm run dev:contracts" "npm run dev:dapp"
```

### Building

```bash
# Build everything
npm run build:all

# Build individual components
npm run build:contracts
npm run build:dapp
```

### Testing

```bash
# Run all tests
npm run test:all

# Run individual test suites
npm run test:contracts
npm run test:dapp
```

## Portfolio Strategy

### Investment Model: ETH-Only Simplified Access

Fortress Finance revolutionizes DeFi investment by eliminating the complexity of managing multiple cryptocurrency positions. Users need only ETH to gain exposure to a professionally managed, diversified portfolio.

#### Core Investment Flow
1. **Single Entry Point**: Users deposit ETH into the Fortress vault
2. **Automatic Diversification**: Contract instantly converts ETH into a balanced portfolio
3. **Token Representation**: Users receive FORT tokens representing their proportional share
4. **Seamless Redemption**: FORT tokens can be redeemed back to ETH at any time

#### Technical Implementation
- **Gas Optimization**: Batch transactions minimize gas costs for portfolio rebalancing
- **Slippage Protection**: Advanced algorithms ensure optimal execution prices
- **Liquidity Management**: Maintains sufficient liquidity for redemptions
- **Price Oracle Integration**: Real-time pricing ensures accurate valuations

### Strategic Asset Allocation

Our portfolio allocation is based on extensive research into blockchain ecosystem fundamentals, market capitalization, and long-term growth potential:

#### Primary Holdings (65% - WBTC)
- **Asset**: Wrapped Bitcoin (WBTC)
- **Rationale**: Bitcoin remains the digital gold standard and primary store of value
- **Market Position**: Largest cryptocurrency by market cap and institutional adoption
- **Risk Profile**: Lower volatility, established store of value
- **Growth Drivers**: Institutional adoption, regulatory clarity, limited supply

#### Secondary Holdings (25% - WETH)
- **Asset**: Wrapped Ethereum (WETH)
- **Rationale**: Leading smart contract platform with dominant DeFi ecosystem
- **Market Position**: Second-largest cryptocurrency with highest developer activity
- **Risk Profile**: Medium volatility, high utility and adoption
- **Growth Drivers**: Layer 2 scaling, institutional DeFi adoption, EIP-1559 deflationary mechanism

#### Growth Holdings (10% - WSOL)
- **Asset**: Wrapped Solana (WSOL)
- **Rationale**: High-performance blockchain with growing ecosystem
- **Market Position**: Emerging smart contract platform with unique advantages
- **Risk Profile**: Higher volatility, high growth potential
- **Growth Drivers**: Low fees, high throughput, growing DeFi ecosystem

### Yield Generation Strategy

#### Automated Yield Deployment
- **Primary Protocols**: Automated liquidity provision to Uniswap V3 and Aave V3
- **Deployment Ratio**: 80% of TVL deployed for yield generation
- **Reserve Requirement**: 20% of TVL maintained in contract for withdrawals
- **Automation**: Fully automated yield optimization and rebalancing
- **Protocol Selection**: Community-governed selection of approved yield protocols

#### Liquidity Provision Strategy
- **Uniswap V3**: Concentrated liquidity provision for optimal capital efficiency
- **Aave V3**: Lending assets to earn interest on stable, high-quality collateral
- **Dynamic Allocation**: Automated rebalancing based on yield opportunities
- **Risk Assessment**: Continuous monitoring of protocol health and yields
- **Gas Optimization**: Batch operations to minimize transaction costs

#### Withdrawal Protection System
- **Daily Withdrawal Limit**: Maximum 5% of TVL can be withdrawn within 24 hours
- **Circuit Breaker**: Automatic activation when daily limit is exceeded
- **Emergency Reserve**: 20% liquidity buffer always maintained in contract
- **Gradual Unwinding**: Large withdrawals processed over multiple days
- **Community Override**: DAO can temporarily adjust limits in emergencies

#### Risk Mitigation
- **Protocol Diversification**: Spread across multiple established DeFi protocols
- **Continuous Monitoring**: Real-time tracking of protocol health and yields
- **Automated Rebalancing**: Dynamic adjustment based on market conditions
- **Emergency Procedures**: Rapid withdrawal from yield positions when needed
- **Audit Requirements**: Regular security audits of all integrated protocols

### Governance and Risk Management

#### DAO Governance Structure
- **Voting Power**: Proportional to FORT token holdings
- **Proposal Types**: Protocol upgrades, parameter changes, emergency actions
- **Voting Periods**: 7-day voting periods for standard proposals
- **Quorum Requirements**: Minimum participation thresholds for validity
- **Execution Delays**: Timelock mechanisms for security

#### Risk Management Framework
- **Portfolio Limits**: Maximum concentration limits for individual assets
- **Rebalancing Triggers**: Automatic rebalancing when allocations drift >5%
- **Circuit Breakers**: Emergency stops for extreme market conditions
- **Insurance Fund**: Reserve fund for covering potential losses
- **Audit Requirements**: Regular third-party security audits

## Roadmap

📋 **[View our comprehensive development roadmap →](./roadmap.md)**

Our roadmap outlines the strategic development path across four phases:
- **Phase 1 (0-6 months)**: MVP Core with WBTC, WETH, and Gold integration
- **Phase 2 (6-18 months)**: Expansion & Liquidity with multi-strategy diversification  
- **Phase 3 (18-36 months)**: Decentralization & Governance with DAO implementation
- **Phase 4 (3-5 years)**: Fortress Reserve Asset positioning as global yield-bearing store of value

## Core Features

### Investment & Redemption
- **ETH-Only Interface**: Simplified user experience with single-asset investment
- **Instant Diversification**: Automatic conversion to balanced multi-asset portfolio
- **Seamless Redemption**: One-click conversion back to ETH
- **Gas Optimization**: Batch transactions minimize user costs
- **Slippage Protection**: Advanced algorithms ensure optimal execution

### Portfolio Management
- **Dynamic Rebalancing**: Automatic portfolio rebalancing based on target allocations
- **Price Oracle Integration**: Real-time Chainlink price feeds for accurate valuations
- **Liquidity Management**: Maintains 20% reserve for withdrawals at all times
- **Withdrawal Limits**: Maximum 5% of TVL can be withdrawn within 24 hours
- **Circuit Breakers**: Automatic activation when withdrawal limits are exceeded
- **Emergency Controls**: Timelock-based emergency withdrawal system

### Governance & Control
- **DAO Governance**: Community-driven decision making through FORT token voting
- **Proposal System**: Structured process for protocol upgrades and parameter changes
- **Timelock Security**: Delayed execution for critical protocol changes
- **Multi-signature Requirements**: Enhanced security for administrative functions
- **Transparent Operations**: All governance activities publicly auditable

### Yield Generation
- **Automated Yield Generation**: 80% TVL deployed to Uniswap V3 and Aave V3
- **Yield Deployment**: Strategic capital deployment across verified DeFi protocols
- **Risk Management**: Comprehensive due diligence and risk assessment
- **Performance Tracking**: Real-time yield and performance monitoring
- **Fee Structure**: Transparent fee management with community oversight

### Security & Compliance
- **Multi-layer Security**: Comprehensive security architecture with multiple protection layers
- **Audit Requirements**: Regular third-party security audits and code reviews
- **Access Controls**: Role-based access control with proper permission management
- **Emergency Procedures**: Rapid response mechanisms for crisis situations
- **Compliance Framework**: Built-in compliance and regulatory considerations

## Supported Assets

### Core Portfolio
- **WBTC**: Wrapped Bitcoin - 65% allocation
  - **Decimals**: 8
  - **Price Feed**: Chainlink BTC/USD price feed
  - **Role**: Primary store of value asset

- **WETH**: Wrapped Ethereum - 25% allocation
  - **Decimals**: 18
  - **Price Feed**: Chainlink ETH/USD price feed
  - **Role**: Smart contract platform and DeFi exposure

- **WSOL**: Wrapped Solana - 10% allocation
  - **Decimals**: 9
  - **Price Feed**: Chainlink SOL/USD price feed
  - **Role**: High-performance blockchain exposure

## Technical Architecture

### System Overview

Fortress Finance is built on a modular, upgradeable architecture that prioritizes security, efficiency, and user experience. The system consists of multiple interconnected smart contracts that work together to provide seamless portfolio management and yield generation.

### Core Contract Architecture

#### 1. FortressToken (Main Vault Contract)
- **Purpose**: Central ERC20 token representing shares in the Fortress portfolio
- **Key Functions**:
  - ETH deposit and FORT token minting
  - FORT token redemption and ETH withdrawal
  - Portfolio rebalancing and asset management
  - Fee collection and distribution
- **Security Features**: Multi-signature controls, timelock delays, emergency pause

#### 2. Asset Management System
- **Portfolio Controller**: Manages asset allocation and rebalancing logic
- **Asset Registry**: Maintains list of supported assets and their configurations
- **Weight Manager**: Handles target allocation percentages and rebalancing triggers
- **Liquidity Manager**: Ensures sufficient liquidity for redemptions

#### 3. Automated Yield System
- **Protocol Integration**: Direct integration with Uniswap V3 and Aave V3
- **Yield Optimizer**: Automated yield optimization and rebalancing algorithms
- **Liquidity Manager**: Manages concentrated liquidity positions on Uniswap V3
- **Lending Manager**: Handles automated lending operations on Aave V3
- **Risk Monitor**: Continuous monitoring of protocol health and yields

#### 4. Oracle and Pricing System
- **Price Oracle Manager**: Integrates with Chainlink price feeds
- **Price Validation**: Ensures price feed accuracy and staleness protection
- **Slippage Calculator**: Calculates optimal execution prices and slippage
- **Market Data**: Real-time market data for portfolio valuation

#### 5. Withdrawal Protection System
- **Daily Limit Controller**: Enforces 5% daily withdrawal limit
- **Circuit Breaker**: Automatic activation when limits are exceeded
- **Reserve Manager**: Maintains 20% liquidity buffer at all times
- **Gradual Unwinding**: Processes large withdrawals over multiple days
- **Emergency Override**: DAO-controlled emergency withdrawal procedures

#### 6. Governance and Control
- **DAO Controller**: Manages governance proposals and voting
- **Timelock Controller**: Implements delayed execution for critical functions
- **Access Control**: Role-based permissions for different system functions
- **Emergency Manager**: Handles emergency situations and crisis response

### Technical Specifications

#### Smart Contract Standards
- **ERC20**: Standard token interface for FORT tokens
- **ERC165**: Interface detection for strategy compatibility
- **OpenZeppelin**: Battle-tested security libraries and patterns
- **Chainlink**: Decentralized price oracle integration

#### Gas Optimization
- **Batch Operations**: Grouped transactions to minimize gas costs
- **Storage Optimization**: Efficient data structures and storage patterns
- **Proxy Patterns**: Upgradeable contracts with minimal gas overhead
- **Circuit Breakers**: Prevent excessive gas consumption during emergencies

#### Security Architecture
- **Multi-signature Wallets**: Critical functions require multiple signatures
- **Timelock Delays**: Delayed execution for governance and emergency functions
- **Access Controls**: Role-based permissions with proper privilege separation
- **Audit Trails**: Comprehensive logging and event emission for transparency

#### Integration Points
- **DEX Integration**: Seamless integration with major decentralized exchanges
- **Lending Protocols**: Integration with established DeFi lending platforms
- **Yield Farming**: Automated yield farming across verified protocols
- **Cross-chain Bridges**: Future support for multi-chain asset management

## Smart Contracts

The smart contracts are located in the `contracts/` directory. See the [contracts README](./contracts/README.md) for detailed information about:

- Contract architecture
- Deployment instructions
- Testing procedures
- Security considerations

## Frontend Application

The Next.js frontend application is located in the `dapp/` directory. See the [dapp README](./dapp/README.md) for information about:

- Application features
- Development setup
- Deployment instructions
- User interface components

## Security Considerations

### Access Control
- Owner-only functions for critical operations
- Guardian system for emergency approvals
- Pause functionality for emergency situations

### Input Validation
- Zero address checks
- Amount validation
- Fee rate limits
- Weight constraints

### Oracle Security
- Price staleness checks
- Negative price protection
- Round ID validation

### Economic Security
- Circuit breaker protection
- Rebalancing mechanisms
- Fee structure limits

## Economic Model

### Token Economics

#### FORT Token Utility
- **Governance Rights**: Voting power proportional to token holdings
- **Yield Participation**: Share in generated yield from automated DeFi activities
- **Portfolio Representation**: Direct representation of portfolio value
- **Liquidity Access**: Seamless conversion to underlying assets

#### Fee Structure
- **Investment Fee**: 0.5% on ETH deposits (covers gas and facilitation costs)
- **Redemption Fee**: 0.25% on ETH withdrawals (covers gas and slippage)
- **Management Fee**: 2% annual fee on total portfolio value
- **Performance Fee**: 20% of excess yield above 10% annual return

#### Revenue Generation
- **DeFi Yield**: Returns from automated liquidity provision and lending
- **Yield Farming**: Returns from deployed capital in DeFi protocols
- **Trading Fees**: Small margins on portfolio rebalancing
- **Management Fees**: Ongoing fees for portfolio management services

### Risk Management

#### Portfolio Risk
- **Diversification**: Spread across three major blockchain ecosystems
- **Correlation Analysis**: Regular monitoring of asset correlations
- **Volatility Management**: Circuit breakers for extreme market conditions
- **Liquidity Risk**: Maintained reserves for redemption demands

#### Operational Risk
- **Smart Contract Risk**: Comprehensive testing and auditing
- **Oracle Risk**: Multiple price feed validation and staleness checks
- **Governance Risk**: Transparent decision-making and community oversight
- **Regulatory Risk**: Compliance framework and legal considerations

## Testing Strategy

### Comprehensive Test Suite

Our testing approach ensures the highest level of security and reliability through multiple layers of validation:

#### 1. Unit Testing
- **Contract Functions**: Individual function testing with edge cases
- **Mathematical Operations**: Precision testing for calculations and rounding
- **State Management**: Testing state transitions and data integrity
- **Access Control**: Permission and role-based access testing

#### 2. Integration Testing
- **End-to-End Flows**: Complete user journey testing
- **Cross-Contract Interaction**: Testing contract interactions and dependencies
- **Oracle Integration**: Price feed integration and validation testing
- **External Protocol Integration**: Testing with real DeFi protocols

#### 3. Security Testing
- **Vulnerability Scanning**: Automated security vulnerability detection
- **Penetration Testing**: Manual security testing and attack simulation
- **Economic Attack Testing**: Testing against economic exploits and manipulation
- **Governance Attack Testing**: Testing governance mechanisms and attack vectors

#### 4. Performance Testing
- **Gas Optimization**: Testing gas consumption and optimization
- **Load Testing**: Testing under high transaction volumes
- **Stress Testing**: Testing system behavior under extreme conditions
- **Scalability Testing**: Testing system performance as it scales

### Test Coverage Goals

- **Code Coverage**: >95% line coverage for all smart contracts
- **Branch Coverage**: >90% branch coverage for decision points
- **Function Coverage**: 100% coverage of all public and external functions
- **Integration Coverage**: Complete coverage of all user flows and scenarios

## Deployment

### Smart Contracts

```bash
# Deploy to localhost
cd contracts && npm run deploy:local

# Deploy to Sepolia testnet
cd contracts && npm run deploy:sepolia

# Deploy to mainnet
cd contracts && npm run deploy:mainnet
```

### Frontend Application

```bash
# Build and start production server
cd dapp && npm run build && npm run start

# Deploy to Vercel (recommended)
cd dapp && npx vercel --prod
```

## License

MIT License - see LICENSE file for details

## Development Approach

### Phase 1: Foundation (Current)
- **Strategy Definition**: Comprehensive strategy documentation and technical specifications
- **Architecture Design**: Detailed system architecture and contract design
- **Security Planning**: Security-first development approach with comprehensive testing
- **Community Building**: Building community around the Fortress Finance vision

### Phase 2: Core Development
- **Smart Contract Development**: Building the core FortressToken and supporting contracts
- **Testing Implementation**: Comprehensive test suite development and validation
- **Security Auditing**: Third-party security audits and code reviews
- **Frontend Development**: User-friendly interface for portfolio management

### Phase 3: Launch Preparation
- **Testnet Deployment**: Extensive testing on testnet environments
- **Community Testing**: Beta testing with community members
- **Documentation**: Complete user and developer documentation
- **Launch Strategy**: Coordinated mainnet launch and initial liquidity

### Phase 4: Growth and Evolution
- **Feature Expansion**: Additional assets and strategies based on community feedback
- **Cross-chain Integration**: Multi-chain support and asset management
- **Advanced Governance**: Enhanced DAO features and community tools
- **Institutional Integration**: Tools and features for institutional users

## Contributing

We welcome contributions from the community! Here's how you can get involved:

### Development
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes with comprehensive tests
4. Ensure all tests pass (`npm test`)
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to your branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

### Documentation
- Improve existing documentation
- Add examples and tutorials
- Translate documentation to other languages
- Create video tutorials and guides

### Community
- Join our Discord community
- Participate in governance discussions
- Help other users and developers
- Report bugs and suggest improvements

## Support

### Community Support
- **Discord**: Join our community Discord for real-time support
- **GitHub Issues**: Report bugs and request features
- **Documentation**: Comprehensive guides and API documentation
- **Community Forums**: Discussion and knowledge sharing

### Technical Support
- **Developer Documentation**: Complete technical documentation
- **API Reference**: Detailed API documentation and examples
- **Integration Guides**: Step-by-step integration tutorials
- **Best Practices**: Security and development best practices

For questions or support, please open an issue on GitHub or join our Discord community.

