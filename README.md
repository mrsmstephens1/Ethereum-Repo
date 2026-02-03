# Ethereum Repo

Một dự án tập trung vào phát triển và triển khai các giải pháp trên mạng lưới Ethereum.

## 🚀 Tính năng chính
* **Smart Contracts:** Các hợp đồng thông minh được viết bằng ngôn ngữ Solidity.
* **Scripts:** Các kịch bản hỗ trợ deploy và tương tác với blockchain.
* **Testing:** Hệ thống unit test đảm bảo tính bảo mật và chính xác của hợp đồng.

## 🛠 Công nghệ sử dụng
* [Solidity](https://soliditylang.org/)
* [Hardhat](https://hardhat.org/) hoặc [Foundry](https://book.getfoundry.sh/)
* [Ethers.js](https://docs.ethers.org/v6/) / [Web3.js](https://web3js.readthedocs.io/)

## 📦 Cài đặt

1. **Clone repository:**
   ```bash
   git clone [https://github.com/mrsmstephens1/Ethereum-Repo.git](https://github.com/mrsmstephens1/Ethereum-Repo.git)
   cd Ethereum-Repo
2. Cài đặt thư viện:
   Bash
   npm install
   # hoặc
   yarn install
3. Cấu hình môi trường: Tạo file .env dựa trên file .env.example và điền các thông tin cần thiết (Private key, API Key Infura/Alchemy).

 💡 Cách sử dụng
   Biên dịch (Compile)
   Bash:
   npx hardhat compile
   
  Chạy Test
   Bash
    npx hardhat test
    
  Triển khai (Deploy)
  Bash
  npx hardhat run scripts/deploy.js --network goerli

📄 Giấy phép
  Dự án này được cấp phép theo tiêu chuẩn MIT License.
  ---


