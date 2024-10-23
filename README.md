# URL Shortener

This project is a simple URL shortener service.

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/REDLANTERNDEV/url-shortener/
   ```
2. Navigate to the project directory:
   ```sh
   cd url-shortener
   ```
3. Install the dependencies:
   ```sh
   npm install
   ```

### Configuration

Create a `.env` file in the root directory of the project and add the following environment variables:

```plaintext
DB_URL=your_mongodb_connection_string
```

- `DB_URL`: The connection string for your MongoDB database.

### Running the Application

Start the server:

```sh
npm run dev
```

The application will be running at `http://localhost:5000`.

### License

This project is licensed under the MIT License.
