**Rust Chat Server — Run Instructions**
```markdown
## 🚀 Rust Chat Server — Run Instructions

### 1. Clone the repository
    git clone <repo-url>
    cd rust-chat-server

### 2. Create the SQLite database
    sqlite3 chat.db < chat_database.sql

### 3. Build the server
    cargo build --release --bin server

### 4. Run the server
    ./target/release/server
