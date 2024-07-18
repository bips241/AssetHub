# AssetHub Project

![AssetHub Logo](client/src/constants/images/Logo.jpg)

## Overview

This decentralized application (DApp) enables users to register and manage assets like land and vehicles on the Ethereum blockchain. It utilizes smart contracts for secure, transparent, and tamper-proof asset registration. The frontend, built with React.js, provides an intuitive user interface, making it accessible to users interacting with the Ethereum blockchain.

## 🚀 Features

### Asset Registration

Users can seamlessly register their assets, providing essential details such as location, ownership, and asset-specific information. The registration process ensures transparency and immutability by leveraging Ethereum smart contracts.

### Marketplace Integration

The DApp includes a decentralized marketplace where users can buy, sell, or trade registered assets. Smart contracts facilitate secure and trustless transactions, ensuring the integrity of asset ownership transfers.

### Auctions and Renting

To enhance flexibility, the project introduces features for asset auctions and renting. Users can participate in auctions to bid on assets, and there's an option to rent assets for a specific duration. These functionalities are governed by smart contracts, promoting trust and security.

### User Authentication and Profiles

A robust authentication system secures user accounts, allowing them to access personalized profiles. Users can track their registered assets, transaction history, and participate in community discussions.

### Responsive UI with Bootstrap

The frontend boasts a responsive design, ensuring a seamless user experience across various devices. Bootstrap is employed for its clean, mobile-friendly components and grid system.

## 🛠️ Future Enhancements

- **User Notifications:** Implement a notification system to alert users about successful registrations, auction bids, and other relevant activities.

- **Enhanced Marketplace Features:** Introduce advanced marketplace features such as a reputation system, detailed asset listings, and a decentralized review system.

- **Integration with External APIs:** Connect the DApp to external APIs for real-time asset data, enhancing the accuracy of registered information.

- **Multi-chain Support:** Explore the possibility of extending the DApp to support multiple blockchains, providing users with more choices and interoperability.

## 🧰 Tech Stack

The AssetHub project is built using the following technologies:

- **Frontend:**
  - React.js
  - Web3.js
  - Bootstrap

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB

- **Blockchain:**
  - Ethereum

- **Other Tools:**
  - Truffle Suite
  - IPFS
  - JWT (JSON Web Tokens)
  - Cloudinary


---

## 🚨 Important Notice 🚨

> **Please Note:**
> - The website might take **2 to 3 minutes** to load due to some technical issues such as bugs or optimization problems. Please be patient.
> - For the best experience, use the website in **desktop site mode** if accessing it from a phone.

---

## 🛠️ Test User Credentials 🛠️

To facilitate easy access for interviewers and others reviewing the project, you can use the following test login credentials:

| **Username** | **Password** |
|--------------|--------------|
|    `test`    | `test@1234`  |

---



## Project Structure

```

project-root/
│
├── client/
│   ├── node_modules/
│   ├── public/
│   │   ├── ... (public files)
│   │
│   ├── src/
│   │   ├── components/
│   │   ├── constants/
│   │   ├── App.js
│   │   ├── App.css
│   │   ├── index.js
│   │   ├── index.css
│   │   ├── routes.js
│   │   ├── contractConfig.js
│   │   └── ...
│   │
│   ├── .env
│   ├── .gitignore
│   ├── package.json
│   ├── package-lock.json
│   └── README.md
│
├── server/
│   ├── node_modules/
│   ├── public/
│   │   ├── ... (public files)
│   │
│   ├── src/
│   │   ├── controllers/
│   │   ├── db/
│   │   ├── middlewares/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── utils/
│   │   ├── app.js
│   │   ├── constants.js
│   │   └── index.js
│   │
│   ├── .env
│   ├── .gitignore
│   ├── .prettierrc
│   ├── package.json
│   ├── package-lock.json
│   └── README.md
│
├── contract/
│   ├── build/
│   ├── contracts/
│   ├── migrations/
│   ├── test/
│   ├── truffle-config.js
│   └── ...
│
└── README.md

```

## Website Hosting

The website is hosted on the following platforms:

- [AssetHub Vercel App](https://assethubweb.vercel.app/)
- [HubAsset Vercel App](https://hubasset.vercel.app/)

## Insights

- **Total Lines of Code:** ![Lines of Code](https://img.shields.io/tokei/lines/github/devayanm/AssetHub)
- **Contributors:** ![Contributors](https://img.shields.io/github/contributors/devayanm/AssetHub)
- **Repository Size:** ![Repository Size](https://img.shields.io/github/repo-size/devayanm/AssetHub)
- **Last Commit:** ![Last Commit](https://img.shields.io/github/last-commit/devayanm/AssetHub)

## Prerequisites

1. Node.js: [Install Node.js](https://nodejs.org/)

2. Truffle Suite: [Install Truffle](https://www.trufflesuite.com/truffle)

3. Ganache: [Install Ganache](https://www.trufflesuite.com/ganache)

Got it! Here's the updated "Getting Started" section with instructions to replace the placeholder URL in the frontend `.env` file:

```markdown
## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/devayanm/AssetHub.git
   cd AssetHub
   ```

2. **Install dependencies for the client:**

   ```bash
   # Install Truffle globally
   npm install -g truffle

   # Install project dependencies for the client
   cd client
   npm install
   ```

3. **Install dependencies for the server:**

   ```bash
   # Install project dependencies for the server
   cd ../server
   npm install
   ```

4. **Configure Environment Variables:**

   - Create a `.env` file in the `client` directory.

   - Add your backend hosted URL for the client in the client's `.env` file:

     ```env
     REACT_APP_BACKEND_URL=https://your-backend-hosted-url.com/api/v1
     ```

   - Create another `.env` file in the `server` directory and add the following environment variables:

     ```env
     PORT=8000
     MONGODB_URI=mongodb+srv://your_username:your_password@cluster0.anjoog4.mongodb.net
     CORS_ORIGIN=*
     CLOUDINARY_CLOUD_NAME=your_cloud_name
     CLOUDINARY_API_KEY=your_api_key
     CLOUDINARY_API_SECRET=your_api_secret
     CLOUDINARY_URL=cloudinary://your_cloudinary_url
     ACCESS_TOKEN_SECRET=your_access_token_secret
     ACCESS_TOKEN_EXPIRY=1d
     REFRESH_TOKEN_SECRET=your_refresh_token_secret
     REFRESH_TOKEN_EXPIRY=10d
     ```

6. **Start the React app:**

   ```bash
   # Start the React app
   cd ../client
   npm start
   ```

7. **Start the server:**

   ```bash
   # Start the server
   cd ../server
   npm run dev
   ```

8. **Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to access the DApp.**

## Testing

Run the Truffle tests:

```bash
truffle test
```

## Contributing

If you would like to contribute to this project, please open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
