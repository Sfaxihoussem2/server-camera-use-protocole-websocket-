# WebSocket Server

This project is a simple WebSocket server built with Node.js and Express. It allows real-time communication between multiple clients.

## Features
- Supports multiple WebSocket clients.
- Broadcasts messages from one client to all connected clients.
- Removes disconnected clients from the list.
- Serves an HTML file (\`client.html\`) to establish WebSocket communication.

## Installation
1. **Clone the repository:**
   \`\`\`sh
   git clone <repository-url>
   \`\`\`
2. **Navigate to the project folder:**
   \`\`\`sh
   cd <project-folder>
   \`\`\`
3. **Install dependencies:**
   \`\`\`sh
   npm install
   \`\`\`

## Usage
1. **Start the WebSocket server:**
   \`\`\`sh
   node server.js
   \`\`\`
2. **Access the client:**
   Open a browser and go to:  
   \`\`\`
   http://localhost/client
   \`\`\`

## Ports
- WebSocket Server: \`40\`
- HTTP Server: \`80\`

## Dependencies
- Node.js
- Express
- WebSocket

## License
This project is licensed under the MIT License.

---

### Author
Developed by [Your Name]
`;

fs.writeFileSync('README.md', readmeContent, 'utf8');
console.log('README.md file has been created successfully.');
