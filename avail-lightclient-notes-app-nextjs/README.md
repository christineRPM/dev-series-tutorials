# Building a Simple Next.js App with Avail Light Client

A hands-on tutorial that demystifies blockchain Data Availability (DA) and Light Clients through building a practical application. Instead of diving into complex topics like rollups and validity proofs, we focus purely on understanding how Data Availability works by building a simple notes app that interacts directly with Avail's DA layer through a Light Client.

## 🎯 Tutorial Focus

This tutorial isolates two key blockchain concepts:
- **Data Availability (DA)**: Learn how data gets stored and verified on Avail's DA layer
- **Light Clients**: Understand how Light Clients enable trustless data verification without running a full node

## 📝 What You'll Build

A decentralized notes application that demonstrates DA and Light Client concepts:
- Submit messages directly to Avail's DA layer
- Verify data availability using your local Light Client
- Monitor Light Client synchronization status
- Track block confirmations for your messages
- Handle network issues with automatic retries
- Maintain message history with local backup

The tutorial breaks down into four main parts:

1. **Basic Next.js Setup**
   - Setting up a clean UI for message input and display
   - Preparing for Light Client integration

2. **Light Client Integration**
   - Understanding Light Client architecture
   - Implementing real-time Light Client status monitoring
   - Handling Light Client connection states
   - Managing synchronization status

3. **Data Availability Interaction**
   - Submitting data to Avail's DA layer
   - Understanding transaction formats and encoding
   - Implementing proper error handling
   - Monitoring transaction status

4. **Enhanced Features**
   - Implementing block confirmation tracking
   - Building a robust retry mechanism
   - Managing message history
   - Handling network disconnections

## 🚀 Getting Started

### Prerequisites

- Node.js 18.17 or later
- Basic familiarity with React and Next.js
- A code editor
- An Avail Light Client running locally

### Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/avail-dev/dev-series-tutorials.git
```

2. Navigate to the project:
```bash
cd dev-series-tutorials/avail-lightclient-notes-app-nextjs
```

3. Install dependencies:
```bash
npm install
```

4. Start your Avail Light Client:
```bash
curl -sL1 avail.sh | bash -s -- --app_id YOUR_APP_ID --network turing --identity ~/.avail/identity/identity.toml
```

5. Run the development server:
```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to see your app in action!

## 📚 New to Avail?

Before starting, make sure to:
1. [Create an Avail Account](https://docs.availproject.org/user-guides/accounts)
2. [Get test tokens from the faucet](https://docs.availproject.org/docs/build-with-avail/interact-with-avail-da/faucet)
3. [Learn about App IDs](https://docs.availproject.org/docs/build-with-avail/interact-with-avail-da/app-id)
4. [Understand Light Clients](https://docs.availproject.org/docs/operate-a-node/run-a-light-client/Overview)

## 🔍 Learn More

- [Full Tutorial](https://blog.availproject.org/p/9f596a5e-954f-4001-9351-9a859905cb75/)
- [Avail Documentation](https://docs.availproject.org/)
- [Light Client API Documentation](https://docs.availproject.org/api-reference/avail-lc-api)
- [Data Availability Primer](https://blog.availproject.org/avails-core-features-explained)

## 🤝 Contributing

We welcome contributions! Feel free to:
- Report bugs
- Suggest enhancements
- Submit pull requests

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](../LICENSE) file for details.
