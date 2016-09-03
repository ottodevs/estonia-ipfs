Demo for linking Estonian e-residency to IPFS.

### Prerequisites

Make sure you have your Estonian e-residency card attached, installed the necessary software, and are running a local IPFS node.

### How to build

Just run

    mvn clean install jetty:run

To build and run the demo.

Then open **http://localhost:8081** in your browser.

### TODO

 * Use JWS instead of quick&dirty signature
 * Figure out how relying party can get the IPNS address
 * Can the ID card's certificate or serial number (together with a secret) somehow be cryptographically linked to my IPFS address?
