# OmniOne Digital ID

**OmniOne Digital ID** is an open source project that aims to drive global adoption and expansion of self-sovereign identity through a secure identity system based on the technology that built the Republic of Korea's national mobile ID.

**OmniOne Digital ID** is an open source decentralized identifier (DID) designed to provide developers with the tools they need to integrate self-sovereign identity management into their applications, built to be secure, scalable, and interoperable by adhering to the latest DID standards.

## Goals

- We aim to provide a digital identity authentication system through the OPEN DID platform based on trust and responsibility to various members of the digital world.
- Through this, we reduce social costs and enable the socially excluded from the infrastructure to fulfill their “social responsibility for realizing human values.”

## Structure
The OPEN DID system consists of a Trust Environment for establishing a trust chain between participating entities, a Wallet for storing and managing various certificates based on Digital ID, a Digital ID that includes various certificates, and Security for data protection.

- **Trust Environment**: The components of OPEN DID define and develop methods for establishing a chain of trust between components to build a trust environment based on Digital IDs.
- **Wallet**: Define the lifecycle of the wallet and e-signs and develops the architecture for key management, storage management, access control management, and security management of the wallet.
- **Digital ID**: Define a data model based on W3C’s Decentralized Identifier and Verifiable Credentials specifications.
- **Security**: Ensures a level of security that ensures the authenticity, confidentiality, and integrity of data exchanged between OPEN DID components.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js** (version 14 or later)
- **npm** (version 6 or later)
- **Git** (for cloning the repository)
- A basic understanding of decentralized identities and blockchain technology is recommended.

### Installation

To install OmniOne, follow these steps:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/yourusername/OmniOne.git
    cd OmniOne
    ```

2. **Install Dependencies**:

    ```bash
    npm install
    ```

### Usage

OmniOne Digital ID provides a set of commands to manage DIDs. Below are some basic usage examples:

- **Start the DID Service**:

    To start the OmniOne DID service:

    ```bash
    npm start
    ```

- **Create a New DID**:

    To create a new DID:

    ```bash
    npm run create-did
    # Output: did:omni:123456789abcdefghi
    ```

- **Resolve an Existing DID**:

    To resolve and retrieve details of an existing DID:

    ```bash
    npm run resolve-did did:omni:123456789abcdefghi
    # Output: { "@context": "https://www.w3.org/ns/did/v1", "id": "did:omni:123456789abcdefghi", ... }
    ```

### Examples

Here’s how you can use OmniOne Digital ID in your project:

- **Integrating with a Web Application**: OmniOne can be integrated into a web application to enable users to authenticate using their DIDs.
- **Cross-Chain DID Resolution**: Utilize OmniOne's interoperability features to resolve DIDs across different blockchain networks.

### Contributing

We welcome and appreciate contributions from the community! To contribute to OmniOne Digital ID:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a Pull Request.

Please ensure that your code adheres to our [contribution guidelines](CONTRIBUTING.md) and is covered by tests where appropriate.

### License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
Apache License 2.0 : http://www.apache.org/licenses/LICENSE-2.0


### Acknowledgments

OmniOne Digital ID was made possible thanks to the contributions of the open-source community and the support of various partners.

### Contact

For further inquiries or support, please contact us at [technical@omnione.com](mailto:technical@omnione.net).

## Additional Resources

- **Documentation**: Detailed documentation is available in the [docs](docs) folder.
- **Issue Tracking**: Please report issues or request features via the [GitHub Issues](https://github.com/yourusername/OmniOne/issues) page.
- **Community Discussions**: Join our [community forum](https://opendid.omnione.net/community) to discuss OmniOne and decentralized identity.

## Roadmap

OmniOne Digital ID is under active development. Here are some features we're planning to add:

- **Support for additional DID methods**
- **Enhanced privacy features**
- **Integration with more blockchain networks**
- **Improved scalability and performance**

Stay tuned for updates!


