# My First dApp - Mood Contract 🎭

Welcome to my first decentralized application! This project is a simple web3 dApp that allows users to set and get their mood on the Ethereum blockchain (Sepolia testnet). It's a learning project that demonstrates basic interaction with smart contracts using Solidity and web3 technologies.

This project was built following the LearnWeb3 Freshman Track tutorial: [Build your first dApp on Ethereum](https://learnweb3.io/degrees/ethereum-developer-degree/freshman/build-your-first-d-app-on-ethereum/)

## 🌟 Features

- Set your mood on the blockchain
- Retrieve your stored mood
- Interactive web interface
- MetaMask integration
- Deployed on Sepolia testnet

## 🔧 Technologies Used

- Solidity (Smart Contract)
- HTML/JavaScript (Frontend)
- Viem (Ethereum JavaScript library)
- MetaMask (Web3 wallet)
- Ethereum Sepolia Testnet

## 📋 Prerequisites

Before you begin, ensure you have met the following requirements:
- MetaMask wallet installed in your browser
- Some Sepolia testnet ETH for gas fees (available from faucets)
- A modern web browser

## 🚀 Getting Started

1. Clone this repository:
```bash
git clone [your-repository-url]
cd mood-contract
```

2. Open `index.html` in your web browser
3. Connect your MetaMask wallet when prompted
4. Make sure you're connected to Sepolia testnet
5. Start setting and getting moods!

## 📝 Contract Details

The smart contract is deployed on Sepolia testnet at:
`0x20E1ea1B8B368Db4260394CD7481c263db6912A2`

### Contract Functions

```solidity
// Set a new mood
function setMood(string memory _mood) public

// Get the current mood
function getMood() public view returns (string memory)
```

## 🎮 How to Use

1. **Setting Your Mood**:
   - Enter your mood in the text input
   - Click "Set Mood"
   - Confirm the transaction in MetaMask
   - Wait for transaction confirmation

2. **Getting Your Mood**:
   - Click "Get Mood"
   - Your current mood will be displayed

## 🧪 Testing

To test the dApp:
1. Ensure you're connected to Sepolia testnet
2. Try setting different moods
3. Verify you can retrieve the mood
4. Check transaction history in MetaMask

## 🎓 Learning Resources

This project was built while learning from:
- [LearnWeb3's Ethereum Developer Degree](https://learnweb3.io/degrees/ethereum-developer-degree/)
- [Ethereum.org documentation](https://ethereum.org/developers)
- [Solidity documentation](https://docs.soliditylang.org/)
- [Viem documentation](https://viem.sh/)

## 📈 Future Improvements

- Add user authentication
- Store multiple moods per user
- Add timestamp for mood entries
- Implement mood history
- Add emoji support
- Create a more sophisticated UI

## 👥 Contributing

As this is a learning project, I welcome any suggestions or improvements! Feel free to:
1. Fork the repository
2. Create a new branch
3. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

Special thanks to:
- LearnWeb3 for their excellent tutorial and learning platform
- The Ethereum community
- Web3 developers who share their knowledge
- My mentors and fellow students

---
*This is my first blockchain project as a student learning web3 development through LearnWeb3's Freshman track. Any feedback or suggestions are greatly appreciated!*
