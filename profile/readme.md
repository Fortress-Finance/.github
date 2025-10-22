# Fortress Finance

A production-ready multi-asset yield vault with ETH-only investment/redemption, DAO governance, and automated yield generation. Fortress Finance represents a revolutionary approach to decentralized finance by creating a diversified cryptocurrency portfolio that users can access through a single ETH investment, while maintaining community-driven governance and sustainable yield generation.

## Core Philosophy

Fortress Finance is built on the principle that **diversification is the cornerstone of sustainable wealth creation**. Rather than forcing users to manage multiple cryptocurrency positions, we provide a single-entry point (ETH) that automatically diversifies across the three most promising blockchain ecosystems: Bitcoin, Ethereum, and Solana.

## Strategic Vision

Our strategy is designed to capture the long-term value appreciation of the three most established and promising blockchain networks while providing users with:

1. **Simplified Access**: Single ETH investment and redemption for diversified exposure
2. **Risk Mitigation**: Diversification across three major blockchain ecosystems
3. **Community Governance**: DAO-driven decision making for protocol evolution
4. **Sustainable Yield**: Automated yield generation that directly bolsters FORT token value
5. **Transparent Operations**: Open-source, auditable, and community-controlled

## Project Structure

This repository contains the smart contract implementation:

- **`contracts/`** - Smart contracts and deployment scripts


## Portfolio Strategy

### Investment Model: ETH-Only Simplified Access

Fortress Finance revolutionizes DeFi investment by eliminating the complexity of managing multiple cryptocurrency positions. Users need only ETH to gain exposure to a professionally managed, diversified portfolio, and they always receive ETH back when redeeming their FORT tokens, regardless of the underlying portfolio composition.

#### Core Investment Flow
1. **Single Entry Point**: Users deposit ETH into the Fortress vault
2. **Automatic Diversification**: Contract instantly converts ETH into a balanced portfolio (WBTC 65%, WETH 25%, WSOL 10%)
3. **Token Representation**: Users receive FORT tokens representing their proportional share
4. **Seamless Redemption**: FORT tokens are redeemed back to ETH by automatically selling the proportional asset allocation on DEX markets

#### Technical Implementation
- **Gas Optimization**: Batch transactions minimize gas costs for portfolio rebalancing
- **Slippage Protection**: Advanced algorithms ensure optimal execution prices
- **Liquidity Management**: Maintains 20% reserve for withdrawals at all times
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
- **Deployment Strategy**: 80% of the underlying portfolio assets (WBTC, WETH, WSOL) deployed for yield generation
- **Reserve Requirement**: 20% of portfolio assets maintained in contract for withdrawals
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

#### Withdrawal Mechanism
- **Proportional Asset Sales**: FORT token redemption triggers proportional sales of WBTC, WETH, and WSOL
- **DEX Market Execution**: Assets sold on Uniswap V3 and other DEXs for optimal pricing
- **ETH Conversion**: All proceeds automatically converted to ETH for user withdrawal
- **Single Asset Delivery**: Users always receive ETH, regardless of current portfolio composition
- **Automated Process**: No manual intervention required for withdrawal execution

#### Risk Mitigation
- **Protocol Diversification**: Spread across multiple established DeFi protocols
- **Continuous Monitoring**: Real-time tracking of protocol health and yields
- **Automated Rebalancing**: Dynamic adjustment based on market conditions
- **Emergency Procedures**: Rapid withdrawal from yield positions when needed
- **Audit Requirements**: Regular security audits of all integrated protocols

### Value Accrual Mechanism

#### How Yield Bolsters FORT Token Value
The automated yield generation system directly enhances the value of existing FORT tokens through a sophisticated value accrual mechanism:

**Direct Value Appreciation**
- **Yield Reinvestment**: Generated yield from Uniswap V3 and Aave V3 is automatically reinvested into the portfolio
- **Portfolio Growth**: As the underlying portfolio (WBTC, WETH, WSOL) grows from yield, each FORT token represents a larger share of the total value
- **Compound Effect**: Reinvested yields generate additional returns, creating exponential growth over time
- **No Dilution**: New yield is added to the existing portfolio without minting new FORT tokens, increasing the value per token

**Value Distribution Process**
1. **Yield Collection**: Automated systems collect yield from liquidity provision and lending activities
2. **Portfolio Rebalancing**: Yield is used to purchase additional WBTC, WETH, and WSOL at current market prices
3. **Value Accrual**: The increased portfolio value is reflected in the exchange rate between FORT tokens and ETH
4. **Token Holder Benefit**: Existing FORT token holders automatically benefit from the increased portfolio value

**Transparent Value Tracking**
- **Real-time Valuation**: Portfolio value is continuously calculated using Chainlink price feeds
- **Exchange Rate Updates**: FORT token exchange rate updates automatically as portfolio value changes
- **Yield Attribution**: All yield generated is attributed to the existing token supply
- **No Token Inflation**: FORT token supply remains constant while underlying value grows

**Long-term Value Creation**
- **Sustainable Growth**: Yield generation provides consistent, sustainable value appreciation
- **Market Independence**: Value growth is not dependent on FORT token price speculation
- **Compound Returns**: Reinvested yields create compound growth over time
- **Risk-Adjusted Returns**: Diversified yield sources provide stable, risk-adjusted returns

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
- **Phase 1 (0-6 months)**: MVP Core with WBTC, WETH, and WSOL integration
- **Phase 2 (6-18 months)**: Expansion & Liquidity with multi-strategy diversification  
- **Phase 3 (18-36 months)**: Decentralization & Governance with DAO implementation
- **Phase 4 (3-5 years)**: Fortress Reserve Asset positioning as global yield-bearing store of value

## Core Features

### Investment & Redemption
- **ETH-Only Interface**: Simplified user experience with single-asset investment and redemption
- **Instant Diversification**: Automatic conversion to balanced multi-asset portfolio (WBTC 65%, WETH 25%, WSOL 10%)
- **Proportional Redemption**: FORT tokens redeemed by selling proportional asset allocation on DEX markets
- **Single Asset Withdrawal**: Users always receive ETH back, regardless of underlying portfolio composition
- **Gas Optimization**: Batch transactions minimize user costs for both investment and redemption
- **Slippage Protection**: Advanced algorithms ensure optimal execution prices for both buying and selling

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
- **Automated Yield Generation**: 80% of portfolio assets deployed to Uniswap V3 and Aave V3
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

#### Upgradeable Contract Architecture

Fortress Finance implements the **UUPS (Universal Upgradeable Proxy Standard)** pattern, ensuring that the protocol can evolve and improve over time while maintaining user funds and state integrity. This upgradeable architecture provides several critical benefits:

**Why Upgradeability is Essential for Fortress Finance:**

1. **Security Enhancements**: Ability to patch vulnerabilities and implement security improvements without requiring users to migrate funds
2. **Feature Evolution**: Continuous improvement of yield strategies, governance mechanisms, and user experience
3. **Protocol Adaptation**: Response to changing market conditions and new DeFi opportunities
4. **Asset Protection**: Guaranteed preservation of user assets and portfolio state during upgrades
5. **Future-Proofing**: Ability to integrate new assets, strategies, and blockchain ecosystems

**Upgrade Safety Measures:**
- **State Preservation**: All user balances, portfolio allocations, and transaction history are preserved during upgrades
- **Asset Protection**: User funds are never at risk during the upgrade process
- **Governance Control**: Only the protocol owner can authorize upgrades, with future DAO governance planned
- **Comprehensive Testing**: Extensive test suites ensure upgrades maintain all existing functionality
- **Transparent Process**: All upgrades are publicly verifiable and auditable

**Technical Implementation:**
- **UUPS Pattern**: Uses OpenZeppelin's UUPS upgradeable proxy pattern
- **Implementation Contracts**: Separate implementation contracts for different versions
- **Proxy Storage**: All state variables stored in the proxy contract, not implementation
- **Function Preservation**: All existing functions continue to work after upgrades
- **New Features**: Upgrades can add new functions without breaking existing ones

### Core Contract Architecture

#### 1. FortressToken (Main Vault Contract)
- **Purpose**: Central ERC20 token representing shares in the Fortress portfolio
- **Key Functions**:
  - ETH deposit and FORT token minting
  - FORT token redemption with proportional asset sales
  - Automatic conversion of portfolio assets back to ETH
  - Portfolio rebalancing and asset management
  - Fee collection and distribution
- **Security Features**: Multi-signature controls, timelock delays, emergency pause

#### 2. Asset Management System
- **Portfolio Controller**: Manages asset allocation and rebalancing logic
- **Asset Registry**: Maintains list of supported assets and their configurations
- **Weight Manager**: Handles target allocation percentages and rebalancing triggers
- **Liquidity Manager**: Ensures sufficient liquidity for redemptions
- **Withdrawal Processor**: Handles proportional asset sales for FORT token redemptions
- **DEX Integration**: Manages asset sales on Uniswap V3 and other DEXs

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

The smart contracts are located in the `contracts/` directory. The project includes both standard and upgradeable versions:

### Contract Versions

#### Standard Contracts
- **`FortressToken.sol`**: Standard implementation with all core functionality
- **`mocks/`**: Mock contracts for testing (MockERC20, MockChainlinkPriceFeed, MockStrategy)

#### Upgradeable Contracts
- **`FortressTokenUpgradeable.sol`**: UUPS upgradeable implementation with all core functionality
- **`FortressTokenV2.sol`**: Version 2 with enhanced fee tracking and volume analytics
- **`FortressTokenV3.sol`**: Version 3 with advanced governance and user analytics

### Token Supply Management

#### Maximum Supply Limit
The FORT token has a **maximum supply of 1 billion tokens** (`MAX_SUPPLY = 1_000_000_000 * 10**18`). This limit is enforced in the `invest()` function to prevent unlimited token inflation and maintain the economic integrity of the protocol.

**Why 1 Billion Tokens?**
1. **Industry Standard**: 1 billion is a common maximum supply used by many successful DeFi tokens (Uniswap's UNI, Chainlink's LINK)
2. **Economic Flexibility**: Allows token prices to range from very small ($0.001) to very large ($1000+) while maintaining reasonable market cap ranges
3. **Psychological Appeal**: A round, easily understandable number that feels substantial but not infinite
4. **Precision**: 18 decimals with 1 billion tokens provides sufficient granularity for all calculations

**Implementation Details:**
- The `MAX_SUPPLY` constant is defined in all contract versions
- Enforcement occurs in the `invest()` function: `require(totalSupply() + fortAmount <= MAX_SUPPLY, "Maximum supply exceeded");`
- This check happens **before** minting tokens, ensuring no supply overflow
- The limit is preserved across contract upgrades (V1 → V2 → V3)
- Users can still redeem tokens when at maximum supply
- New investments become possible again after redemptions reduce total supply

**Economic Implications:**
- Provides a clear upper bound for token supply, preventing hyperinflation
- Creates scarcity value as the protocol approaches maximum capacity
- Maintains predictable economics for long-term planning
- Ensures the protocol remains sustainable even with massive adoption

### Deployment Options

#### Standard Deployment
```bash
npm run deploy
```

#### Upgradeable Deployment
```bash
npx hardhat run scripts/deploy-upgradeable.js --network <network>
```

#### Contract Upgrade
```bash
npx hardhat run scripts/upgrade.js --network <network>
```

### Testing

#### Standard Tests
```bash
npm test
```

#### Upgrade Tests
```bash
npx hardhat test test/UpgradeTest.test.js
```

See the [contracts README](./contracts/README.md) for detailed information about:

- Contract architecture
- Deployment instructions
- Testing procedures
- Security considerations
- Upgrade procedures


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
- **Value Accrual**: Automatic value appreciation through yield reinvestment
- **Portfolio Representation**: Direct representation of portfolio value
- **Liquidity Access**: Seamless conversion to underlying assets

#### Fee Structure
- **Investment Fee**: 0.15% on ETH deposits (covers gas and facilitation costs)
- **Redemption Fee**: 0.15% on ETH withdrawals (covers gas and slippage)
- **Management Fee**: 1.5% annual fee on total portfolio value
- **Performance Fee**: 15% of excess yield above 10% annual return

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

