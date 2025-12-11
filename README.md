
## 🚀 Rust Chat Server — Run Instructions

### 1. Clone the repository
\`\`\`bash
git clone <repo-url>
cd rust-chat-server
\`\`\`

### 2. Create the SQLite database
\`\`\`bash
sqlite3 chat.db < chat_database.sql
\`\`\`

### 3. Build the server (release mode)
\`\`\`bash
cargo build --release --bin server
\`\`\`

### 4. Run the server
\`\`\`bash
./target/release/server
\`\`\`
